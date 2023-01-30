**Part 1**
The code:
<img width="995" alt="Screenshot 2023-01-30 at 1 02 12 PM" src="https://user-images.githubusercontent.com/45737807/215595088-80ef3cea-5952-46d4-9b3e-23a97d4f6018.png">

Succesful use of /add-message:
<img width="1340" alt="Screenshot 2023-01-30 at 1 09 01 PM" src="https://user-images.githubusercontent.com/45737807/215595688-6022c8cd-c5d5-4204-892b-75c314421db1.png">

Explanation:
The methods getPath and equals are called to compare the path to "/" and "/add-message". It's a match with "/add-message", so we then proceed and call getQuery and split to split the query, "s=Helllloooo", based on the delimeter =, putting the first half into index 0 of parameter and the second half into index 1. Then it calls equals to see if index 0 is equal to s. It is, so we proceed. It then calls equals again to check if the String we are adding everything to is empty. It is empty, so now the string we return is equal to "Helllloooo". Then we skip all the else if statements and return the returnString.<br/>
The values changed are returnString, changing from "" to "Helllloooo". It also fills the indexs of parameters with "s" in the first, and "Helllloooo" in the second.

Another Succesful use of /add-message
<img width="1340" alt="Screenshot 2023-01-30 at 1 12 24 PM" src="https://user-images.githubusercontent.com/45737807/215597049-3ebf6f7a-29a3-49e6-b5d5-619247ca5f2e.png">

Explanation:
The methods getPath and equals are called to compare the path to "/" and "/add-message". It's a match with "/add-message", so we then proceed and call getQuery and split to split the query, "s=this-is-working-properly", based on the delimeter =, putting the first half into index 0 of parameter and the second half into index 1. Then it calls equals to see if index 0 is equal to s. It is, so we proceed. It then calls equals again to check if the String we are adding everything to is empty. It is not empty, so it skips the first if, and goes to the next one. It adds "\n" and "this-is-working-properly" to the end of the running string, so  now the string we return is equal to "Helllloooo\nthis-is-working-properly". Then we skip all the else if statements and return the returnString.<br/>
The values changed are returnString, changing from "Helllloooo" to "Helllloooo\nthis-is-working-properly". It also fills the indexs of parameters with "s" in the first, and "this-is-working-properly" in the second.

Unseccesful use of /add-message
<img width="1340" alt="Screenshot 2023-01-30 at 1 21 22 PM" src="https://user-images.githubusercontent.com/45737807/215597832-e35b92a1-bdc7-4a7b-9fb1-14cccc289e8d.png">

Explanation:
The methods getPath and equals are called to compare the path to "/" and "/add-message". It's a match with "/add-message", so we then proceed and call getQuery and split to split the query, "ADWD=this-is-working-properly", based on the delimeter =, putting the first half into index 0 of parameter and the second half into index 1. Then it calls equals to see if index 0 is equal to s. It isn't, so we skip the if statement and go the the else part. It then returns "Not Valid"
Only the values of paramters is changed, index 0 is "ADWD" and index 0 is "this-is-working-properly"



**Part 2** <br/>
The faulty code:<br/>

    static int[] reversed(int[] arr) {
      int[] newArray = new int[arr.length];
      for(int i = 0; i < arr.length; i += 1) {
        arr[i] = newArray[arr.length - 1];
      }
    return arr;
    }
 
The Failure inducing code:<br/>

    @Test
    public void testReversed2() {
      int[] input1 = { 1, 2, 3};
      assertArrayEquals(new int[]{3, 2, 1 }, ArrayExamples.reversed(input1));
      }

Code that doesn't induce a failure:<br/>

    @Test
    public void testReversed() {
      int[] input1 = { };
      assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
    }
    
<img width="967" alt="Screenshot 2023-01-30 at 11 42 32 AM" src="https://user-images.githubusercontent.com/45737807/215579521-e797f655-f82c-4993-bd73-8126c009c6a6.png">


Fixed Code:<br/>

    static int[] reversed(int[] arr) {
       int[] newArray = new int[arr.length];
       for(int i = 0; i < arr.length; i += 1) {
         newArray[i] = arr[arr.length - 1 - i];
       }
     return newArray;
    }
    
<img width="856" alt="Screenshot 2023-01-30 at 12 27 32 PM" src="https://user-images.githubusercontent.com/45737807/215587778-076cd369-ed85-4e34-80f7-bbb4513d6de7.png">

    
Explanation:
The bug before was that it returned the old array instead of returning the new array it created. It also filled up the old array based on the 
values of the new array, when it should have been the other way around. A final error in the code was that it filled up arr with the fixed inde 'arr.length - 1' The new code fixes these errors by returning newArray instead of the input array arr. I also swapped arr and new Array in the loop so that newArray would be fixed based on the values of arr instead of it being the other way around. I also fixed the indexing, subtracting the variable 'i' from it so that the index would change depending on which execution the loop was on.
  
**Part 3** <br/>
I didn't know that you could host webservers locally, and I especially didn't know that you could create a way to do so with just VSCode.
I still don't really understand how it actually works, and what the code that we didn't touch actually does, but it feels as if though I just
researched a little bit more, I wouldn't have that much of a hard time figuring it out. I also didn't know all the ways of manipulating url paths, 
such as getPath or getQuery, but I now know that you can and what each of these do, and which parts of the url they return
