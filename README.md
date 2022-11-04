# Exercises:
Create console application and push it to your git. Code for each exercise put in separated method (static, separate it in new class, as you want) and push also to your repo.

### 1. [1.november]
Write a method that receives one integer positive number and returns **true** if number has the same value if it is read from right to left, otherwise it returns **false**.

*Example*:  
*Input*: 150; *Output*: false  
*Input*: 181; *Output*: true  
*Input*: 1; *Output*: true  
*Input*: 11; *Output*: true  
*Input*: 19; *Output*: false

### 2. [2.november]
Write a method that receives one string that consists only **R** and **S** characters (in Upper Case) and returns maximum number of perfect substrings. 
Perfect substring is one that consists the same number of **R** and **S** characters. Characters in string can not be skipped to create more substrings. Time complexity must be O(n).

*Example*:  
*Input*: "RSRRSSRSRS"; *Output*: 4  
*Input*: "RSRRRSSRSS"; *Output*: 2  
*Input*: "SSSSRRRR"; *Output*: 1

Constraints:
* string length is between 2 and 100
* characters are **R** or **S**
* string is balanced

### 3. [3.november]  
Write a method that receives one string and returns **true** if sentence is pangram, and **false** if it is not. Sentence is pangram if consists every letter of the English alphabet. 

*Example*:  
*Input*: "prodynabelgrade"; *Output*: false  
*Input*: "jackamazedafewgirlsbydroppingtheantiqueonyxvas"; *Output*: true   
*Input*: "twodrivenjockshelpfaxmybigquiz"; *Output*: true

Constraints:  
* string length is between 1 and 1000
* string consists only lowercase English letters, without spaces

### 4. [4.november]  
Write a method that receives two strings and returns **true** if first string is subsequence of second string, in other case it returns **false**. String is subsequence of second string in case all its characters are part of that second string, without changing order of characters. Characters don't have to be next to each other.

*Example*:  
*Input*: firstString="abc", secondString="ahbgdc"; *Output*: true  
*Input*: firstString="axc", secondString="ahbgdc"; *Output*: false  
*Input*: firstString="", secondString="ahbgdc"; *Output*: true  

Constraints:  
* 0 <= firstString.length <= 100
* 0 <= secondString.length <= 1000
* firstString and secondString consist only of lowercase English letters.
