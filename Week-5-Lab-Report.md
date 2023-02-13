# **Find COMMAND**

## **-iname**

   `$ find -iname PATTERN`

   > This works like how normal find works. It looks through the files to look for a file that matches with the pattern provided. The only difference between -iname and -name is that iname ignores capitilization, and treats lower cases and upper cases as the same.
  
  > Source: I found this command using `$ man find` in the terminal
  
  Example
  
  `$ find -iname "BERLITZ2"`
  
<img width="915" alt="Screenshot 2023-02-13 at 12 55 43 PM" src="https://user-images.githubusercontent.com/45737807/218573221-6dea180a-3d58-4096-9a2a-7be907b25f28.png">

   `$ find -iname "BErlItZ2"`
   
<img width="915" alt="Screenshot 2023-02-13 at 1 00 45 PM" src="https://user-images.githubusercontent.com/45737807/218573545-a24fd1bc-4e25-42d5-8371-ab4296da91e2.png">

## **-size**

`$ find -size n`

> This looks for files of a certain size, with a + indicating greather than, a - indicating less than, K being shorthand for KB, M being shorthand for MB, and G being shorthand for GB. 

> Source: https://linuxhandbook.com/find-command-examples/

Example

  `$ find -size +200k` Looks for files bigger than 200KB

<img width="986" alt="Screenshot 2023-02-13 at 2 26 06 PM" src="https://user-images.githubusercontent.com/45737807/218588592-02a8d5c5-52ad-43dc-875c-72ddfd52e89b.png">

  `$ find -size -50k` Looks for files smaller than 2KB
  
  <img width="986" alt="Screenshot 2023-02-13 at 2 28 53 PM" src="https://user-images.githubusercontent.com/45737807/218589037-e3ee4f12-b12c-447f-929f-e1420aec0993.png">
  
 ## **-atime/-amin**
  
  `$ find -atime n`
  
  `$ find -amin n`
  
  > This looks for files that were accessed according to n, which corresponds to days when using -atime, and minutes when using -amin. + indicates greater than, - indicates less than
  
 > Source: https://linuxhandbook.com/find-command-examples/
  
  Example
  
  `$find -atime -1` Looks for files accesed less than 1 day ago, aka today
  
  <img width="986" alt="Screenshot 2023-02-13 at 2 38 10 PM" src="https://user-images.githubusercontent.com/45737807/218590481-1606073f-84a3-4ef4-9ea8-af779a05e1b9.png">
  
  `$ find -amin -1` Looks for files accessed less than 1 minute ago
  
  <img width="986" alt="Screenshot 2023-02-13 at 2 46 02 PM" src="https://user-images.githubusercontent.com/45737807/218591675-cb89b7ed-b687-4b6c-a825-32fcddc6e60d.png">

## **-type**

`$ find -type c`

> This looks for files of type c, where c can be replaced by f to look for a regular file, or replaced by d to look for a directory. 

> Source: https://opensource.com/article/18/4/how-use-find-linux

Example 

`$ find -type d` Looks for and lists out all directories inside current directory, written_2.

<img width="986" alt="Screenshot 2023-02-13 at 3 01 25 PM" src="https://user-images.githubusercontent.com/45737807/218594476-3a101146-c7c8-48fc-8712-915d50ecd019.png">

`$ find "non-fiction -type d` Looks for and lists out all directories that start with "non-fiction".

<img width="986" alt="Screenshot 2023-02-13 at 3 06 47 PM" src="https://user-images.githubusercontent.com/45737807/218595017-ba468a65-9af6-4f07-95f1-73f0a9e9e244.png">
