# Tutorial For Incoming CSE15L Students
## How To Install VScode
To install Visual Studio Code, go to VScode website:https://code.visualstudio.com/, and follow the instruction to download and install it on your computer. This software is available for all major operating system, including MacOS for Macs and Windows for PCs. Once the installation is complete, you should be able to open a window that appear like this<img width="1026" alt="截屏2023-04-06 下午3 02 51" src="https://user-images.githubusercontent.com/130001791/230502689-f8e81594-6c3f-4bfb-b58c-16ec4b326cdc.png"><br>
Once you see your screen appeared something liket this, you have successfully installed VScode. Congratulations!
## Remotely Connected
  First, reset your CSE15L password:CSE15L have course-specific account. Go to "https://sdacs.ucsd.edu/~icc/index.php" to look up your account and reset password(we are resetting CSE15L course password, DO NOT reset your AD passord!) <br><br>
  Second, remotely Connected. In order to work on a remote computer over the Internet, you will have to use VScode/terminal to establish a connection.
Next, launch a terminal within VScode by pressing Ctrl or Command + ` or selecting Terminal → New Terminal from the menu. Your command will resemble the following:*ssh cs15lsp23zz@ieng6.ucsd.edu* (include that "ssh" in your command), but with the zz substituted with the letters specific to your course account(include that "ssh" in your command).<br><br>
Then you will get message " are you sure you want to continue connecting (yes/no/[fingerprint])?". Just type "Yes".<br><br>
Then the command line is asking your password. Type your CSE15L password you resetted. The password will be hiden on your screen, don't hesitate, you are typing in!<br><br>
After you typed in the correct password, you will see something like this <img width="509" alt="截屏2023-04-06 下午3 48 08" src="https://user-images.githubusercontent.com/130001791/230507637-4b994777-6eed-455b-86b9-ea34e64079c0.png"><br>
Cheers, you have remotely connected to a comuputer in CSE basement! Now any command you run will also run on that computer.
## Try Some Commands
If you see something like this,<br>
<img width="344" alt="截屏2023-04-06 下午4 45 50" src="https://user-images.githubusercontent.com/130001791/230513313-05350816-3331-4cde-9447-05fa0917d5bf.png"><br>
you can try the commands we learnt in lecture2 on your computer!<br><br>
You may try<br>
> cd~<br>
> ls -lat<br>
> cd<br>
> pwd<br>
> ls <directory>, where <directory> is "/home/linux/ieng6/cs15lsp23/cs15lsp23abc", where the "abc" is one of the other group members’ username
<br><br>

*I wish I could bring you a screenshot of interesting commands I have tried, but I did not know why the CSE basement does not allow me to log in again with the same password and account name I used in lab time. I'm trying to figure it out! Fingers crossed.*

# Congratulations! You Finished This Tutorial! Wish You Have a Wonderful Journey in CSE15L
