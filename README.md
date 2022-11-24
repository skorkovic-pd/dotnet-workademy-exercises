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

Classname: **CheckIfNumberIsPalindrome**

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

Classname: **SplitStringInBalancedSubstrings**

### 3. [3.november]  
Write a method that receives one string and returns **true** if sentence is pangram, and **false** if it is not. Sentence is pangram if consists every letter of the English alphabet. 

*Example*:  
*Input*: "prodynabelgrade"; *Output*: false  
*Input*: "jackamazedafewgirlsbydroppingtheantiqueonyxvas"; *Output*: true   
*Input*: "twodrivenjockshelpfaxmybigquiz"; *Output*: true

Constraints:  
* string length is between 1 and 1000
* string consists only lowercase English letters, without spaces

Classname: **CheckIfSentenceIsPangram**

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

Classname: **CheckIfStringIsSubsequenceOfSentence**

### 5. [7.november] 
Write a method that receives array of integers and returns integer that is greatest common divisor of array (greatest common divisor of the smallest and the largest number in array of integers). 

*Example*:  
*Input*: [2,5,6,9,10]; *Output*: 2  
*Input*: [7,5,6,8,3]; *Output*: 1   
*Input*: [3,3]; *Output*: 3

Constraints:  
* numbers in array have value between 1 and 1000
* array has length between 2 and 1000

Classname: **GreatestCommonDivisorOfArray**

### 6. [8.november] 
Write a method that receives a string and returns index of first non repeated letter (character). Otherwise it returns -1. 

*Example*:  
*Input*: "prodyna; *Output*: 0  
*Input*: "thebestcompany"; *Output*: 1   
*Input*: "aabbcc"; *Output*: -1

Constraints:  
* string length is between 1 and 1000
* string consists only lowercase letters

Classname: **FirstNonRepeatedCharacter**

### 7. [9.november] 
Write a method that receives two strings and returned second one sorted by rule defined by the first string. First string has unique (non-repeated) letters. Both strings consist only of alphabet characters. If any character from the second string is not in first string it can be on any position in result (ordered) string.

*Example*:  
*Input*: "vbi", "ivbk"; *Output*: "vbik"  
*Input*: "ihgfedcba", "prodyna"; *Output*: "prodyna"   
*Input*: "cbafg", "abcd"; *Output*: "cbad"

Constraints:  
* order string has length between 1 and 26, and all characters are unique
* second string (string for ordering) has length between 1 and 200
* both strings consist lowercase English letters

Classname: **SortedStringByCustomRule**

### 8. [10.november] 
Write a method that receives an array of integers and returns true if array is continuous sequence, otherwise it returns false. Array is continuous sequence if its elements are ordered ascendingly or descendingly. Also neighboring elements can have the same values.

*Example*:  
*Input*: [3,4,5,5,5,6]; *Output*: true   
*Input*: [421,22,19,4,4,1]; *Output*: true   
*Input*: [2,5,8,7,8]; *Output*: false

Constraints:  
* array's length is between 1 and 1000
* array elements have value between 1 and 1000

Classname: **ArrayIsContinuousSequence**

### 9. [14.november] 
Write a method that receives a integer and returns value of Fib(n). Fib is function that calculates Fibonacci numbers - numbers of Fibonacci sequence where each element of sequence has value that is sum of the two preceding elements. First (Fib(0)) and second (Fib(1)) elements have values 0 and 1.

*Example*:  
*Input*: 0; *Output*: 0   
*Input*: 1; *Output*: 1   
*Input*: 2; *Output*: 1  
*Input*: 3; *Output*: 2  
*Input*: 5; *Output*: 5  

Constraints:  
* integer has value between 0 and 100

Classname: **FibonacciNumberCalculator**

### 10. [15.november] 
Write a method that receives an array of integers (initialArray) and returns also an array of integers (resultArray) where each element has value that represents how far from original value is his first greater successor. For example, if initialArray[3] = 5, value of resultArray[3] will be distance from that index (3) to the index of next greater successor. In case there is not greater successor value will be 0.

*Example*:  
*Input*: [22,23,24,11,15,2,45,47]; *Output*: [1,1,4,1,2,1,1,0]   
*Input*: [60,70,80,90]; *Output*: [1,1,1,0]   
*Input*: [90,60,30]; *Output*: [0,0,0]  

Constraints:  
* length of arrays is between 1 and 10000
* values of initialArray are between 1 and 100

Classname: **FirstGreaterSuccessor**

### 11. [16.november] 
Write a method that receives an array of integers and returns pairs of elements that have the same difference as the minimum absolute difference of array. Minimum absolute difference of array is the lowest difference between two elements. Elements can be in more than one pair, but elements are unique inside array. Pairs are returned in IList<IList<int>> type of structure. Also pairs are in ascending order. So if *b-a=minAbsDiff(array)*, a < b and pair [a,b] is added to returning structure.  

*Example*:  
*Input*: [1,3,8,14,22]; *Output*: [[1,3]]  
*Input*: [3,8,-10,23,19,-4,-14,27]; *Output*: [[-14,-10],[19,23],[23,27]]  
*Input*: [4,2,1,3]; *Output*: [[1,2],[2,3],[3,4]]  

Constraints:  
* length of array is between 2 and 10000 elements
* values of array have values between -10<sup>6</sup> and 10<sup>6</sup>

Classname: **AllPairsWithMinimalDifference**


### 12. [17.november] 
Write a method that receives an array of integers and returns value of super element of given array, otherwise it returns -1. Super element is element that has a value equal to the number of repetitions in the array.

*Example*:  
*Input*: [2,2,3,4]; *Output*: 2  
*Input*: [1,2,2,3,3,3]; *Output*: 3  
*Input*: [2,2,2,3,3]; *Output*: -1

Constraints:  
* length of array is between 1 and 500 elements
* values of array have values between 1 and 500

Classname: **SuperElementOfArray**

### 13. [18.november] 
Write a method that receives an integer and returns true if integer is ugly number. Ugly number is positive integer whose factors are limited to 2, 3 and 5.

*Example*:  
*Input*: 6; *Output*: true (2, 3)  
*Input*: 1; *Output*: true (1 has no prime factors)  
*Input*: 14; *Output*: false (2, 7)  
*Input*: 22; *Output*: false (2, 11)  
*Input*: 24; *Output*: true (2, 2, 2, 3)  


Constraints:  
* integer has any possible value for integer number in C#

Classname: **UglyNumberCheck**

### 14. [21.november] 
Copy-Paste problem - you have opened Notepad and written one letter **P**. Two possible operations are given to you: Copy-All and Paste, and you need to use as less as possible number of operations to get required number of written letters **P**. Write a method that receives an integer (number of letters **P** that must be written in Notepad) and returns an integer that is the minimum required number of operations that are needed to do that.

*Example*:  
*Input*: 3; *Output*: 3  
*Input*: 4; *Output*: 4  
*Input*: 5; *Output*: 5  
*Input*: 1; *Output*: 0  
*Input*: 6; *Output*: 5  
*Input*: 10; *Output*: 7  


Constraints:  
* integer has value between 1 and 1000

Classname: **CopyPasteProblem**

### 15. [24.november] 
Restaurant meel waiting - customers arrive in restaurant and order food, wait for it to be prepared, and then get it. You have to write a method that receives array *customers*, and returns double value that represents value of average time customers need to wait.  
*customers[i]*, for each *i*, has [arrival<sup>i</sup>, time<sup>i</sup>]:  
* arrival<sup>i</sup> is integer that represents time of customers arrival. Elements of customers array are sorted in ascending order by arrival time
* time<sup>i</sup> is the time that is needed to prepare food for customer i.  
Kitchen can prepare food for only one customer, parallelisation is impossible.  

*Example*:  
*Input*: [[1,2],[2,5],[4,3]]; *Output*: 5.00  
*Input*: [[5,2],[5,4],[10,3],[20,1]]; *Output*: 3.25  


Constraints:  
* array customers has length between 1 and 10000
* arrival and time have values between 1 and 1000
* arrival<sup>i</sup> <= arrival<sup>i+1</sup>

Classname: **CopyPasteProblem**
