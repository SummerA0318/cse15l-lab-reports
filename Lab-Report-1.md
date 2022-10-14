## Step 1: download VS Code:

People can download the app from https://code.visualstudio.com/. Since I have previously downloaded it, I have a screenshot of my previous codes.

![step1](https://user-images.githubusercontent.com/114268165/193391609-1548eed3-77bd-44e4-a191-c2c96d7d4ed2.jpg)


## Step 2: Remote connecting

I followed this tutorial [link](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit) How to Reset your Password to change my password first with chrome. Then I open the app terminal on my mac. I use the ssh command which can login to the remote account by `ssh cs15lfa22pr@ieng6.ucsd.edu` to login to my remote account with my new password. The "cs15lfa22pr@ieng6.ucsd.edu" is the name of my remote server on a UCSD computer while "cs15lfa22pr" is my username specific for this class.

Using the ssh command to login to my remote computer

![image](https://user-images.githubusercontent.com/114268165/193387757-0edf2fad-0554-44aa-ac12-06729532f11f.jpg)


## Step 3: run commands

I tried several commands and understand what they do.

Pwd: shows you the current directory you’re in

Ls: shows all files in the current directory

Ls -a: shows all files including the hidden ones in the current directory

Cd: change directory to somewhere I need

Trying different commands

![image](https://user-images.githubusercontent.com/114268165/193388235-7a959267-159e-4973-bc12-24b5fde976b9.jpg)
 
 
## Step 4: Move file with scp

First I create a WhereAmI.java file, which has the following codes:
```
class WhereAmI {
  public static void main(String[] args) {
    System.out.println(System.getProperty("os.name"));
    System.out.println(System.getProperty("user.name"));
    System.out.println(System.getProperty("user.home"));
    System.out.println(System.getProperty("user.dir"));
  }
}
```
I save it and run it on my local computer by `javac WhereAmI.java` `java WhereAmI`. Then I use scp command which can copy a file from local computer to remote computer by `scp WhereAmI.java cs15lfa22pr@ieng6.ucsd.edu:~/`. "WhereAmI.java" is the file I want to copy onto the remote computer, and "cs15lfa22pr@ieng6.ucsd.edu" is the remote computer I want to copy onto, ":~/" means I copy the file into the default path on the remote computer. Then I login to my remote account by ssh command again and save and run the WhereAmI file by `javac WhereAmI.java` `java WhereAmI` again. I found that the os.name, username, user home and user directory of local computer and remote computer are all different which shows that I am really on two different computers with two different accounts. It seems that getProperty is a built-in function that can get some basic information for the computer and account.

The process of changing the WhereAmI file and then run it in remote computer takes me 1 minute 40 seconds. If I do it 100 times, I would spend about 2 hours and a half.

Save and run the WhereAmI file on my local computer
![image](https://user-images.githubusercontent.com/114268165/193388640-81748461-a1ad-4a74-bad3-7cc54b47eaa0.jpg)

Using the scp command to copy the WhereAmI file onto the remote computer
![image](https://user-images.githubusercontent.com/114268165/193388860-3d70d416-2816-435c-b42c-0fda7b33d4f0.jpg)

Sava and run the WhereAmI file on the remote computer
![image](https://user-images.githubusercontent.com/114268165/193389314-26b96349-e952-48b9-ae4d-0a6fffc0e066.jpg)


## Step 5: Setting ssh key

To not repeating my password everytime, I create a ssh key on my local computer by command `ssh-keygen` and I get the following reponse from terminal:
```
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key:
```
I enter the directory "/Users/yubinglin/.ssh/id_rsa" to save the key, then terminal shows something like:
```
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key: /Users/yubinglin/.ssh/id_rsa
Enter passphrase: 
Enter same passphrase again: 
Your identification has been saved in /Users/yubinglin/.ssh/id_rsa.
Your public key has been saved in /Users/yubinglin/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:jZaZH6fI8E2I1D35hnvGeBePQ4ELOf2Ge+G0XknoXp0 linyubing@linyubingdeMacBook-Pro.local
The key's randomart image is:
+---[RSA 3072]----+
|                 |
|       . . + .   |
|      . . B o .  |
|     . . B * +.. |
|      o S = *.B. |
|       = = O.*.*+|
|        + * *.BE+|
|           +.+.o |
|             ..  |
+----[SHA256]-----+
```
The key image is generated randomly. Then I login to my remote computer by the ssh command again and use command `mkdir .ssh` to make sure their is a ".ssh" folder in my remote computer so that the key files are in pair. Then I use scp command `scp /Users/yubinglin/.ssh/id_rsa.pub cs15lfa22pr@ieng6.ucsd.edu:~/.ssh/authorized_keys` to copy the key on my local computer to be on my remote computer. Finally I no longer need to enter my password and can just login to my remote computer!

This time the process of changing the WhereAmI file and then run it in remote computer takes me 1 minute 10 seconds. I save half a minute on the same process!

Login without entering password
![image](https://user-images.githubusercontent.com/114268165/193389669-f930e00a-fb56-426b-8878-5d417ba9730b.jpg)

## Step 6: Running multiple commands on the same line

To use remote running more pleasant, I start to put the codes together in one line to decrease the run time.

I use the commands on the sam eline `javac WhereAmI.java; ssh cs15lfa22pr@ieng6.ucsd.edu "cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI"`. The commands are composed by firstly `javac WhereAmI.java;` on my local computer to save my changes in the file. Then `ssh cs15lfa22pr@ieng6.ucsd.edu` to login to my remote computer. Since there's no need to enter a password, I can continue to write commands on the same line that can run on the remote computer. Thus I continue to copy WhereAmI and OtherMain the two files by `cp WhereAmI.java OtherMain.java;`. At last I run the WhereAmI file by `java WhereAmI` and get the output. The ";" is used to seperate each command and '""' the quotation mark is used to contain all the commands that runs on the remote computer. When all the commands finish running, I am still on my local computer because the nested commands only allow me to operate on the remote computer instead of really login and stay on it.

This time I spent 3 seconds running these commands together.

Running multiple commands on the same line
![image](https://user-images.githubusercontent.com/114268165/193389973-66ee814e-3751-4b11-aebf-bde25f2ba2ed.jpg)


