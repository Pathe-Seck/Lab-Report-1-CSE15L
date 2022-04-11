# Hello! Today I'm going to be teaching you how to sign gain remote access through your course-specific account and be able to use it efficiently!


## Step 1: Installing VScode
  The first step in getting remote access is to install VScode. Once VS code is      installed you are going to go ahead and just open the application and be ready to use the terminal to login to you course-specific account. The screenshot below is the screen that you should be seeing if VScode is installed correctly. 

<img width="1440" alt="emptyvs" src="https://user-images.githubusercontent.com/102937267/162676460-5fa3bf90-4d20-4f18-9593-ae8e92039471.png">

## Step 2: Gaining Remote Access
  Now that you have VScode opened it's time to get access to your account! What you want to do is hit Ctrl and ' on your computer or click on terminal and new terminal option. Once that happens you are going to be using the course specific account that should look something like $ ssh cs15lsp22zz@ieng6.ucsd.edu. Then you will be just entering your password and you should be able to login just fine.
  
<img width="1440" alt="step1" src="https://user-images.githubusercontent.com/102937267/162676693-9908d6dc-0b16-464c-8a3d-9e1eaac1a04b.png">

## Step 3: Let's Try Out Some Commands
  Let's try out a few commands to get a little more comfortable with the environment. Here are a few commands that are very useful to try out.
  * cd ~
  * cd
  * ls -a
  * ls -lat
  * ls
 
<img width="1440" alt="step2" src="https://user-images.githubusercontent.com/102937267/162676748-0e9c32e0-fdbc-4661-9c27-bb70d946ff8c.png">
 
 ## Step 4: Moving Files With scp
   scp is a commmand that is used on your computer instead of through a remote computer. scp allows you to  be able to copy the file from your computer to another computer. You'll want to format the command to look like this: scp <file_name>.java cs15lsp22zz@ieng6.ucsd.edu:~/
   
<img width="1440" alt="step5" src="https://user-images.githubusercontent.com/102937267/162676810-2c8a0baa-f929-44cb-a54d-10a5a2c2a1ac.png">
   
 ## Step 5: Setting An SSH Key 
   ssh keys are a very easy way of avoiding you having to enter your password every single time you want to login. ssh keys allow you to be able avoid logging in and instead creates two files one being the public key and the other being the private key. In order to access this you need to type ssh-keygen.
    
<img width="1440" alt="laststep" src="https://user-images.githubusercontent.com/102937267/162676865-97054331-f5d0-435f-86fa-7b04f36f1896.png">
    
## Step 6: Optimizing Remote Running
   In addition to being able to have a ssh key to make logging in much easier, you can also use alot of other commands to make remote running very smooth. It is also very important that you become familiar with each of the steps above so that remote running becomes a piece of cake. 
  
  Here are a few tips to make your life easier: 
  * $ ssh cs15lsp22afh@ieng6.ucsd.edu "ls", the ls allows you to be able to list the       home directory on the remote server as son as you log in.
  * ";" using semicolons allows you to be able to run multiple different commands on       the same line
  * Using the up arrow allows you to be able to recall the last command that was run.
    
