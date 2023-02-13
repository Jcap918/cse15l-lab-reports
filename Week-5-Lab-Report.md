**Find COMMAND**

**-iname**

`$ find -iname PATTERN`

  This works like how normal find works. It looks through the files to look for a file that matches with the pattern provided. The only difference between 
  -iname and -name is that iname ignores capitilization, and treats lower cases and upper cases as the same.
  
  Example
  
  `find -iname "BERLITZ2"`
  
<img width="915" alt="Screenshot 2023-02-13 at 12 55 43 PM" src="https://user-images.githubusercontent.com/45737807/218573221-6dea180a-3d58-4096-9a2a-7be907b25f28.png">
   <span style="background-color: #000000">find -iname "BErlItZ2"</span>
<img width="915" alt="Screenshot 2023-02-13 at 1 00 45 PM" src="https://user-images.githubusercontent.com/45737807/218573545-a24fd1bc-4e25-42d5-8371-ab4296da91e2.png">
