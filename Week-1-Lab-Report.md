1.) **Download VS Code** 
  * Follow this [Link](https://code.visualstudio.com/Download)
  * Download version depending on what system you are on
  * An agreement textbox will apear. Click on "I accept this agreement" and click "next"
  * Select which folder you want to save the file to. You can browse to chose, or select the default path
  * You will then be prompted with additional tasks that can be performed, such as creating a desktop icon. Most aren't important, but to make things easier checkmark the desktop icon. Now you may select install.
  * Click finish
  * Open up VS Code. Your screen should look like this:
   <img width="1440" alt="Screen Shot 2023-01-14 at 2 53 20 PM" src="https://user-images.githubusercontent.com/45737807/212500674-dbc92b9f-f436-4858-a0aa-262354526288.png">
   Notes: I didn't do this step exactly because I already had VS Code installed from last quarter, so I can't provide images of every single step.
   
   
2.) **Remote Connecting**
  * Bring up the terminal
   <img width="1440" alt="Screen Shot 2023-01-14 at 3 03 11 PM" src="https://user-images.githubusercontent.com/45737807/212500861-953fde86-067f-4d64-b69b-10c3d5aa509a.png">
  * Type the following command into the terminal (without the $), with the zz replaced with your own unique combination of characters
     `$ ssh cs15lwi23zz@ieng6.ucsd.edu`
  * Note: If you don't know your account numbers, you can look it up [here](https://sdacs.ucsd.edu/~icc/index.php)
  * If this is your first time attempting remote access, then you will be prompted with a question. Type in 'yes' into the terminal
  * You must then provide your password that you use to log into school accounts. If this does not work, you can reset your password by following these [steps](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)
  * Your screen should then look like this:
   <img width="1440" alt="Screen Shot 2023-01-14 at 3 21 09 PM" src="https://user-images.githubusercontent.com/45737807/212501302-d11025c3-67a1-4b3f-a33c-82c7cbe2fd02.png">
3.) Commands
  * The following are some of the commands you can try out in the terminal.
  * `pwd` - This commands prints out the path to your working directory
  * `cd [Directory_Name]` - Replace Directory_Name with the directory of your choice, and it will change your working directory to said directory.
  * `cd ~` - This command sets your working directory to the home directory
  * `ls` - This command lists out all the contents of the working directory, except for hidden files and content.
  * `ls -a` - This command lists out all the contents of the working directory, including hidden files and content.
  * `ls -lat` - This command lists out all the contents kf the working directory, including hidden files and content, sorted by time.
  * `top` - This command produces a list of current running processes.
   <img width="1440" alt="Screen Shot 2023-01-16 at 9 33 07 PM" src="https://user-images.githubusercontent.com/45737807/212817867-92c4de26-0b32-476a-8b0e-392933a3b700.png">
