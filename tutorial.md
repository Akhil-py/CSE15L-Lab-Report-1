# CSE 15L Tutorial

Welcome to CSE 15L! This is a short tutorial on how to get started with this lab. We will be covering how to:
- Install Visual Studio Code
- Remotely connect to a computer in the CSE basement using ieng6
- Trying some commands on the client and server


## Installing Visual Studio Code

First head to [https://code.visualstudio.com/download](https://code.visualstudio.com/download).
Here you will find different installations for Visual Studio Code for different operating systems (Windows, macOS, Ubuntu, etc.) 

![image](Download VSC.png)

Download the installation for your operating system. In my case it's Windows.

Next, run the .exe installer and follow the instructions.

![image](VSC installer.png)

Once the installation is complete you can now open Visual Studio Code, and you should see a screen like this:

![image](https://user-images.githubusercontent.com/61783850/212567994-cb69c515-25b1-47dd-ba59-04ad49150ccf.png)

You have now installed Visual Studio Code!


## Establishing a remote connection using ieng6

If this is the first time using your CSE 15L account, lookup your account at [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php) and reset your password to activate your account. You will use this password to login to the remote server. (Warning: Your tritonlink password will also be reset)

Before leaving this page, note the last 3 letters of your CSE 15L account ID. You will need this in the future.

![image](https://user-images.githubusercontent.com/61783850/212568657-09ae65b8-adf9-4530-9dd1-8e0825a355c4.png)

Install Git at [https://gitforwindows.org/](https://gitforwindows.org/), run the .exe installer, and follow the instructions you see on the window. Once you have successfully downloaded and installed git, open Visual Studio Code and hold Crtl + \` to open the terminal.

![image](https://user-images.githubusercontent.com/61783850/212559746-a0f429a9-3f07-4dc0-8d86-5611bd528dc0.png)

Next open the command palette using Crtl + Shift + P and type "Select Default Profile". Then select Git Bash fom the options. On the top right side of the terminal window, click on the + icon. This will open a new Git Bash terminal. Give it a few seconds to load.

You should now see something like this:

![image](https://user-images.githubusercontent.com/61783850/212559973-b37f7db2-6e6a-4742-bd9e-14969d7c1e76.png)

Next, to establish a connection with the server, type `$ ssh cs15lwi23zz@ieng6.ucsd.edu` in your terminal. Do not hit enter just yet. Replace the "zz" with the letters from your CSE 15L account as noted above, and then press enter.

If this is your first time establishing a connection to the server, you should see a message like this: 
`ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? `

Type `yes` and press enter. Then type in your password and press enter (you won't see it when typing for privacy reasons).

If successful, your terminal should look similar to this:

![image](https://user-images.githubusercontent.com/61783850/212567301-1e4a43ab-4544-4c09-98ac-a0e0d57344ae.png)

Great! Your terminal is now connected to a computer in the CSE basement! Any commands you run on the terminal will run on this computer.


## Running Commands

You can now run commands on the remote computer. Try it out. Here are some examples.

![image](https://user-images.githubusercontent.com/61783850/212567776-2150190d-d3e4-49a5-9fa7-6898575445e8.png)

Also try running some commands on your local computer. To close the remote connection, type `exit` in the terminal.
