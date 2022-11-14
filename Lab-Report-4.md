
## Part 1

The task I pick is to change the name of the start parameter and its uses to base in DocSearchServer.java, the vim commands my group come up with is `vim DocSearchServer.java<Enter>/start<Enter>dwibase<Esc>ndwibase<Esc>ndwibase<Esc> :wq<Enter>`

First we open the terminal and enter the directory where the DocSearchServer.java file is stored. Then we enter `vim DocSearchServer.java` and press `Enter` to open the file in vim. The cursor is at the first character now.
  
<img width="765" alt="截屏2022-11-13 下午11 01 17" src="https://user-images.githubusercontent.com/114268165/201596884-5452f7ae-1ded-45bd-a488-fd5123e11d7d.png">

Then we enter `/start` and press `Enter` to search for the word "start" in the file. The cursor moves to the first "start" in the file.

<img width="764" alt="截屏2022-11-13 下午11 01 34" src="https://user-images.githubusercontent.com/114268165/201597165-6ebefafc-074f-4604-b32c-013604f62d75.png">

Then we enter `dw` which deletes a word from the position of the curosr, which in this case is the word "start".

<img width="759" alt="截屏2022-11-13 下午11 01 50" src="https://user-images.githubusercontent.com/114268165/201597279-cc939bc6-baf0-4f47-bebd-dd9ffb5d2ed1.png">

Then we enter `i` to enter Insert mode with a "-- INSERT --" at the bottom of the screen.

<img width="765" alt="截屏2022-11-13 下午11 02 09" src="https://user-images.githubusercontent.com/114268165/201597400-f3e62e5f-5607-4953-b4f8-8ba0aaf755b9.png">

Then we enter the word "base". Now we replace the first "start" with "base" in the file. After that we press `Esc` to exit the insert mode. The "-- INSERT --" at the bottom of the screen disappears.

<img width="763" alt="截屏2022-11-13 下午11 02 29" src="https://user-images.githubusercontent.com/114268165/201597536-2c2bdd56-1c23-4fb0-ba1f-147050f9c1d0.png">

Then we press `n` again to search for the next "start" in the file.

<img width="763" alt="截屏2022-11-13 下午11 02 41" src="https://user-images.githubusercontent.com/114268165/201597818-3ac0d400-6c2c-4a46-a0ad-8349f6ed66db.png">

We enter `dw` to delete the next "start".

<img width="764" alt="截屏2022-11-13 下午11 02 52" src="https://user-images.githubusercontent.com/114268165/201597931-60042449-3907-422d-b476-a0a120291e63.png">

We press `i` to enter insert mode and enter "base" again.

<img width="763" alt="截屏2022-11-13 下午11 03 18" src="https://user-images.githubusercontent.com/114268165/201598001-939f9e1c-e4ca-4212-8639-2f47989acb56.png">

We press `Esc` to exit insert mode and press `n` to jump to the next "start".

<img width="763" alt="截屏2022-11-13 下午11 03 35" src="https://user-images.githubusercontent.com/114268165/201598624-f9596907-35a1-45be-88de-ef9099a8c3d5.png">

We press `dw` to delete the "start" and press `i` to enter insert mode.

<img width="765" alt="截屏2022-11-13 下午11 03 51" src="https://user-images.githubusercontent.com/114268165/201598700-63c7e1d2-5b65-4968-b015-91d9686ef150.png">

We enter "base" and press `Esc` to exit the insert mode. Now we've replaced all the word "start" in the method to "base".

<img width="759" alt="截屏2022-11-13 下午11 04 06" src="https://user-images.githubusercontent.com/114268165/201598777-1b6f438c-00eb-427a-ba8b-b4613d27c5b7.png">

We enter `:wq` and then press `Enter` to save and exit the file.

<img width="763" alt="截屏2022-11-13 下午11 04 24" src="https://user-images.githubusercontent.com/114268165/201598906-c2a1dc89-4476-4eb5-8618-ac0c723d8513.png">
<img width="765" alt="截屏2022-11-13 下午11 04 38" src="https://user-images.githubusercontent.com/114268165/201599166-3f275648-384b-4d7c-a6d2-0f1e49dfc585.png">

## Part 2

