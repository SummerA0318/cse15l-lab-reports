Step 1: download VS Code:

People can download the app from https://code.visualstudio.com/. Since I have previously downloaded it, I have a screenshot of my previous codes.

![step1](https://user-images.githubusercontent.com/114268165/193391609-1548eed3-77bd-44e4-a191-c2c96d7d4ed2.jpg)


Step 2: Remote connecting

I followed this tutorial [link](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit) How to Reset your Password to change my password first with chrome. Then I login to my remote account with my new password.

![image](https://user-images.githubusercontent.com/114268165/193387757-0edf2fad-0554-44aa-ac12-06729532f11f.jpg)


Step 3: run commands

I tried several commands and understand what they do.

Pwd: shows you the current directory you’re in

Ls: shows all files in the current directory

Ls -a: shows all files including the hidden ones in the current directory

Cd: change directory to somewhere I need

![image](https://user-images.githubusercontent.com/114268165/193388235-7a959267-159e-4973-bc12-24b5fde976b9.jpg)
 
 
Step 4: 

First I create a WhereAmI.java file, save it and run it on my local computer then use scp command to copy it onto my remote computer. Then I login to my remote account and save and run the WhereAmI file. I found that the os.name, username, user home and user directory of local computer and remote computer are all different which shows that I am really on two different computers with two different accounts. It seems that getProperty is a built-in function that can get some basic information for the computer and account.

The process of changing the WhereAmI file and then run it in remote computer takes me 1 minute 40 seconds. If I do it 100 times, I would spend about 2 hours and a half.

![image](https://user-images.githubusercontent.com/114268165/193388640-81748461-a1ad-4a74-bad3-7cc54b47eaa0.jpg)
![image](https://user-images.githubusercontent.com/114268165/193388860-3d70d416-2816-435c-b42c-0fda7b33d4f0.jpg)
![image](https://user-images.githubusercontent.com/114268165/193389314-26b96349-e952-48b9-ae4d-0a6fffc0e066.jpg)


Step 5:

To not repeating my password everytime, I create a ssh key by command ssh-keygen. Since I save the key in directory /Users/yubinglin/.ssh/id_rsa, I login to my remote computer and use command mkdir .ssh to make sure the key files are in pair. Then I scp the key on my local computer to be on my remote computer. Finally I no longer need to enter my password and can just login to my remote computer!

This time the process of changing the WhereAmI file and then run it in remote computer takes me 1 minute 10 seconds. I save half a minute on the same process!

![image](https://user-images.githubusercontent.com/114268165/193389669-f930e00a-fb56-426b-8878-5d417ba9730b.jpg)

Step 6:

To use remote running more pleasant, I start to put the codes together in one line to decrease the run time.

This time I spent 3 seconds running these commands together.

![image](https://user-images.githubusercontent.com/114268165/193389973-66ee814e-3751-4b11-aebf-bde25f2ba2ed.jpg)


