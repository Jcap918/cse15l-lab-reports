# **Step 4**
<img width="857" alt="Screenshot 2023-02-26 at 2 42 46 PM" src="https://user-images.githubusercontent.com/45737807/221441946-1140b51b-c570-4eb0-aaca-0f22870fafce.png">

**Keys Pressed:** `<ctrl>r s<enter>`
  
 I used ctrl-r to enter reverse-i-search mode, then I clicked s to search for ssh cs15lwi23anh@ieng6.ucsd.edu.
  It showed up after only needing to press s, so once it showed up, I click enter to execute the command. Then I was automatically logged into my account.
  
# **Step 5**
  <img width="857" alt="Screenshot 2023-02-26 at 2 44 38 PM" src="https://user-images.githubusercontent.com/45737807/221442004-1e8b8337-9dbf-4ec6-8bb5-b91d69b24ca7.png">

**Keys Pressed:** `<ctrl>r git<space>cl<enter>`

I Used ctrl-r once again to enter reveerse-i-search mode, then I typed `git cl` to search for git clone, and the first git clone result to pop up alread had 
my forked lab7 git directory, so I pressed enter to clone it. 

# **Step 6
<img width="857" alt="Screenshot 2023-02-26 at 2 50 49 PM" src="https://user-images.githubusercontent.com/45737807/221442281-d6b55452-762f-439c-beca-732543773712.png">

**Keys Pressed:** `cd l<tab><enter>`, `<ctrl>r javac<enter>`, `<ctrl>r java<space><enter>`

I used cd lab7/ to go into the directory I had copied, but pressed tab after pressing cd l to autocomplete the request. I then pressed ctrl-r to enter 
reverse-i-search mode, then I typed `javac` to look for `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` in order to compile all the files
Afterwards, I pressed ctrl-r once again to enter reverse0i-search mode, then typed `java ` to look for `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar
org.junit.runner.JUnitCore TestListExamples`to run the test file. 

# **Step 7**
<img width="857" alt="Screenshot 2023-02-26 at 3 26 40 PM" src="https://user-images.githubusercontent.com/45737807/221443841-43ce750d-0c6d-41dc-973e-c791237ea94c.png">

<img width="857" alt="Screenshot 2023-02-26 at 3 25 47 PM" src="https://user-images.githubusercontent.com/45737807/221443786-df65051c-0226-4ee2-981e-160142e633fd.png">

**Keys Pressed:** `nano<space>L<tab>j<tab><enter>`, `<ctrl>w index1<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter><ctrl>w<enter>
<ctrl>w<enter><ctrl>w<enter><right><right><right><right><right><right><delete>2`, `<ctrl>o<enter>`, `<ctrl>x`

I type `nano L`, then pressed tab to autocomplete. It only autocompleted to `nano ListExamples.` because there existed .class and .java files, and the 
autocomplete didn't know which one I wanted. so I pressed j to tell it I wanted the java file, then pressed tab, and enter to execute the command. Once I was
in the file, I pressed ctrl-w to launch search mode within nano, then typed index1 to find the index1 that was supposed to be an index2. It didn't point me to 
the right one, so I pressed ctrl-w enter 6 times to search for the correct one. I didn't type index1 because it used the search word from the previous search. 
Once I found it, I pressed the right arrow 6 times to go to the end of the word. Then, I deleted the last character of the word, the "1", and replaced it with a 2. 
I then pressed ctrl-o to save the file, and pressed enter to replace the original file with the new fixed file. Then I pressed ctrl-x to exit.

# **Step 8**
<img width="857" alt="Screenshot 2023-02-26 at 3 29 30 PM" src="https://user-images.githubusercontent.com/45737807/221443975-3ea81806-9ee8-43f2-9705-9bdfba3f5a3e.png">

**Keys Pressed:** `<ctrl>r javac<enter>`, `<ctrl>r java<space><enter>`

I pressed ctrl-r to enter reverse-i-search mode, then I typed `javac` to look for `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` in
order to compile all the files. Afterwards, I pressed ctrl-r once again to enter reverse0i-search mode, then typed `java ` to look for `java 
-cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples`to run the test file. The files were fixed, so no error popped 
up this time

# **Step 9**
<img width="1172" alt="Screenshot 2023-02-27 at 7 38 34 PM" src="https://user-images.githubusercontent.com/45737807/221749413-bea0e8c6-8e90-4c4f-9878-c450c49625e8.png">



**Keys Pressed:**  `git add L<tab>j<tab><enter>`, `git commit -m "fix"<enter>`, `git push origin main <enter>`

Once I had made the changes I wanted to make, I typed in git add to add the file I wanted to add to the commit list. I typed in L, then pressed tab to let it autofill, but it only filled up "ListExamples." because there was a .class file and a .java file. I pressed j then tab to autofill the .java one, and pressed enter to execute the command. Once I had added the file to the commit list, I commited it by typying git commit -m, and I put the message I wanted to show up on github inside the quotation marks, which was "fix", then pressed enter to execute the commit. Then finally, I pushed the changes onto github by typying git push origin main, then pressed enter to execture the command. 
