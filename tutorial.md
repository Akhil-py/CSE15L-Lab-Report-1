# CSE 15L Tutorial

Welcome to CSE 15L! This is a short tutorial on how to get started with this lab. We will be covering how to:
- Install Visual Studio Code
- Remotely connect to a computer in the CSE basement using ieng6
- Trying some commands on the client and server


## Installing Visual Studio Code

First head to https://code.visualstudio.com/download.
Here you will find different installations for Visual Studio Code for different operating systems (Windows, macOS, Ubuntu, etc.) 

![image](Download VSC.png)

Download the installation for your operating system. In my case it was windows.

Next, run the .exe installer and follow the steps shown.

![image](VSC installer.png)


Once the installation is complete you can now open Visual Studio Code, and you should see a screen similar to this:


![image](VSC opened.jpg)

You have now installed Visual Studio Code!


## Establishing a remote connection using ieng6

If this is the first time using your CSE 15L account, lookup your account at https://sdacs.ucsd.edu/~icc/index.php and reset your password. (Note: Your tritonlink password will also be reset)

Install Git at https://gitforwindows.org/, run the .exe installer, and follow the instructions you see on the window. Once you have successfully downloaded and installed git, open Visual Studio Code and hold Crtl + \` to open the terminal.

![image](https://user-images.githubusercontent.com/61783850/212559746-a0f429a9-3f07-4dc0-8d86-5611bd528dc0.png)

Next open the command palette using Crtl + Shift + P and type "Select Default Profile". Then select Git Bash fom the options. On the top right side of the terminal window, click on the + icon. This will open a new Git Bash terminal. Give it a few seconds to load.

You should now see something like this.

![image](https://user-images.githubusercontent.com/61783850/212559973-b37f7db2-6e6a-4742-bd9e-14969d7c1e76.png)

Next to establish a connection with the server, type `$ ssh cs15lwi23zz@ieng6.ucsd.edu` in your terminal. Do not hit enter just yet. Replace the `zz` with the letters in your CSE 15L account. Hit enter now.

If this is your first time establishing a connection to the server, you should see a message like this: 
`ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? `

Type "yes" and press enter. Then type in your password and press enter (you won't see it when typing for privacy reasons).
