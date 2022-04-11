# Hello! Today I'm going to be teaching you how to sign gain remote access through your course-specific account and be able to use it efficiently!


1. ## Installing VScode
  The first step in getting remote access is to install VScode. Once VS code is      installed you are going to go ahead and just open the application and be ready to use the terminal to login to you course-specific account. The screenshot below is the screen that you should be seeing if VScode is installed correctly. 

![Image](http://emptyvs.png)

2. ## Gaining Remote Access
  Now that you have VScode opened it's time to get access to your account! What you want to do is hit Ctrl and ' on your computer or click on terminal and new terminal option. Once that happens you are going to be using the course specific account that should look something like $ ssh cs15lsp22zz@ieng6.ucsd.edu. Then you will be just entering your password and you should be able to login just fine.

![Image](http://step1.png)

3. ## Let's Try Out Some Commands
  Let's try out a few commands to get a little more comfortable with the environment. Here are a few commands that are very useful to try out.
  * cd ~
  * cd
  * ls -a
  * ls -lat
  * ls
 
 ![Image](http://step2.png)
 
 4. ## Moving Files With scp
   scp is a commmand that is used on your computer instead of through a remote computer. scp allows you to  be able to copy the file from your computer to another computer. You'll want to format the command to look like this: scp <file_name>.java cs15lsp22zz@ieng6.ucsd.edu:~/
   
   ![Image](http://step5.png)
   
 5. ## Setting An SSH Key 
    ssh keys are a very easy way of avoiding you having to enter your password every single time you want to login. ssh keys allow you to be able avoid logging in and instead creates two files one being the public key and the other being the private key. In order to access this you need to type ssh-keygen.
    
    ![Image](http://laststep.png)
    
6. ## Optimizing Remote Running
    
