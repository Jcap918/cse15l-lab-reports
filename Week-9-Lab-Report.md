## **Done Quick Lab**

I could have completed the tasks in Lab Report 4 much quicker if we were allowed access to Bash Scripts. In order to do this,
I would have created two Bash scripts. The first one I named "Quick.sh"
<img width="1035" alt="Screenshot 2023-03-12 at 1 58 21 PM" src="https://user-images.githubusercontent.com/45737807/224573361-81bd5f8b-cb12-4d58-a33d-841d356ffef9.png">

1.) It first removes any directories with the name "Done-Quick-Lab".

2.) Then the script clones the forked github repositroy in a directory titled "Done-Quick-Lab", and changes directories into the newly created directory.

3.) The script then compiles and runs the test files to show that there is a test failing. Afterwards, it executes nano on ListExamples.java file in order to be
able to edit the file and fix the error. 

4.) I wasn't able to automate this part. I tried installing xdotool to be able to automate key presses, but wasn't able to make it work. So then the steps would be the same as 
normal. 

`<ctrl>w index1<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><right><right><right><right><right><right><delete>2`, `<ctrl>o<enter>`, `<ctrl>x`

I pressed ctrl-w to launch search mode within nano, then typed index1 to find the index1 that was supposed to be an index2. It didn't point me to 
the right one, so I pressed ctrl-w enter 6 times to search for the correct one. I didn't type index1 because it used the search word from the previous search. 
Once I found it, I pressed the right arrow 6 times to go to the end of the word. Then, I deleted the last character of the word, the "1", and replaced it with a 2. 
I then pressed ctrl-o to save the file, and pressed enter to replace the original file with the new fixed file. Then I pressed ctrl-x to exit.

Once the edit has been made, I run the second bash script, "done.sh".

<img width="1035" alt="Screenshot 2023-03-12 at 2 10 20 PM" src="https://user-images.githubusercontent.com/45737807/224573891-f8ca465a-7bba-47c6-9277-2a05ab32a40f.png">

5.) This bash script runs compiles the files to account for the fix, then runs the test file. it will run properly now because the file is fixed.

6.) git add ListExamples.java is executed to add the file to the commit

7.) git commit -am "Fixed" commits the changes made, and adds a message "Fixed" to explain that the file should work properly now.

8.) git push origin main pushes the commit onto the github directroy. 


## **Putting it together**

<img width="1035" alt="Screenshot 2023-03-12 at 2 17 46 PM" src="https://user-images.githubusercontent.com/45737807/224574279-3ee0864f-f11f-461d-82d2-f45f5d1aaaad.png">

This shows what the terminal looks like after running "quick.sh". It shows that the tests were run and failed. I then fixed the error normally, and ran the next bash script

<img width="1035" alt="Screenshot 2023-03-12 at 2 19 59 PM" src="https://user-images.githubusercontent.com/45737807/224574378-b41b98d8-f465-4e77-98f4-9c3c84897db1.png">

This shows the commited being pushed.
