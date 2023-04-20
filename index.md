# Tutorial For Incoming CSE15L Students
## How To Install VScode
To install Visual Studio Code, go to VScode website: [VScode](https://code.visualstudio.com/) , and follow the instruction to download and install it on your computer. This software is available for all major operating system, including MacOS for Macs and Windows for PCs. Once the installation is complete, you should be able to open a window that appear like this<img width="1026" alt="截屏2023-04-06 下午3 02 51" src="https://user-images.githubusercontent.com/130001791/230502689-f8e81594-6c3f-4bfb-b58c-16ec4b326cdc.png"><br>
Once you see your screen appeared something liket this, you have successfully installed VScode. Congratulations!
## Remotely Connected
  First, reset your CSE15L password. Our course CSE15L have course-specific account. Go to [Account Lookup](https://sdacs.ucsd.edu/~icc/index.php) to look up your account and reset password(we are resetting CSE15L course password, DO NOT reset your AD passord! You can go to [CSE15l account](https://sdacs.ucsd.edu/cgi-bin/alloc-query) to reset your course specific account. <br><br>
  Second, remotely Connected. In order to work on a remote computer over the Internet, you will have to use VScode/terminal to establish a connection.
Next, launch a terminal within VScode by selecting Terminal → New Terminal from the menu. Your command will resemble the following:*ssh cs15lsp23zz@ieng6.ucsd.edu* (include that "ssh" in your command), but with the zz substituted with the letters specific to your course account.<br><br>
Then you will get message 
```
are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
Just type "Yes".<br><br>


Then the command line is asking for your password. Type your CSE15L password you resetted previously. The password will be hiden on your screen, don't worry, you are typing in!<br><br>
After you typed in the correct password, you will see something like this![145411680830562_ pic](https://user-images.githubusercontent.com/130001791/230543084-fe7dd9ef-b05d-4bc5-9269-c2dc34b881d4.jpg)
 <br>
Cheers, you have remotely connected to a comuputer in CSE basement! Now any command you run will also run on that computer.
## Try Some Commands
Now you can try the commands we learnt in lecture2 on your computer!<br><br>
You may try<br>
```
> cd
> ls -lat
> pwd
 ```
in which ```cd``` allows you to move between directories.```ls -lat``` show the full list or content of your directory. ```pwd``` gives the full path name of your current directory (from the root directory).<br>
As an example, here are some commands I tried on my computer:I typed ```ls -lat``` into command, it gives me the list of my directory![145391680830370_ pic](https://user-images.githubusercontent.com/130001791/230543260-fd86a8d6-eec4-4b5d-82ee-8feeaf7fee55.jpg)<br>
 In the following screenshot, I typed ```pwd``` into command, and it gives me the full path name of my current directory.<br>
  ![145401680830427_ pic](https://user-images.githubusercontent.com/130001791/230543289-cbd4e07a-b51a-4729-89c6-b86c6c6aa5d8.jpg)<br>
  In the following screenshot, I typed ```ls``` into command to display files I have, which returned me ```perl5```. Then I want to get into ```perl5``` and see what is inside, so I typed ```cd perl5```. It does not return me anything because there is literally nothing in ```perl5```. <img width="311" alt="截屏2023-04-19 下午8 43 07" src="https://user-images.githubusercontent.com/130001791/233252805-92fc891e-fea5-4616-b874-9e0eb174e344.png">
 <br>
However, we can check if we are in ```perl5``` using ```pwd``` which gives me the full path name.<br>
<img width="343" alt="截屏2023-04-19 下午8 39 15" src="https://user-images.githubusercontent.com/130001791/233252219-18564961-bbaf-4d9d-87bd-352b58e6c0d3.png"><br>
In the end of the path, we can see we are in ```perl5```, so we are done.

# Congratulations! You Finished This Tutorial! Wish You Have a Wonderful Journey in CSE15L
