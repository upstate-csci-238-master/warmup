# program-warmup
Name your program file warmup.cpp

Submit your working C++ code to your CodePost.io account. 

In this challenge, you will determine if a given integer num is a Curzon number. If 1 plus 2 elevated to num is exactly divisible by 1 plus 2 multiplied by num, then num is a Curzon number.

You are to write 2 functions - main and isCurzon as described below. 

Write a function named isCurzon that tells if a number is Curzon or not. Pass in a number and return true or false. 

FOR A GRADE OF C: Write a C++ main function that reads in an integer. Then output (on a line by itself) # is Curzon or # is not Curzon, where # is the number you read in. 

FOR A GRADE OF B: Write a C++ main function that reads in an integer. Then output (on a line by itself) the sum of the Curzon numbers that exist between 0 and the number. In this case between is inclusive, meaning include the number. So if you read in 5 look at all the values from 0 to 5 and the ones that are Curzon, add them up. Print the sum. 

FOR A GRADE OF A: Read in several numbers until you read in 0. If the number is not positive then output an error message "input not valid" on a line by itself. Continue reading in integers and outputting the answer. Terminate when you read in 0. 

Examples of Curzon numbers
```
isCurzon(5) ➞ True
2 ** 5 + 1 = 33
2 * 5 + 1 = 11
33 is a multiple of 11
```
```
isCurzon(10) ➞ False
2 ** 10 + 1 = 1025
2 * 10 + 1 = 21
1025 is not a multiple of 21
```

```
isCurzon(14) ➞ True
2 ** 14 + 1 = 16385
2 * 14 + 1 = 29
16385 is a multiple of 29
```

Add the following comments to EVERY C++ program for this course

```
# Your Name
# CSCI 238
# Current Date
# Program - name of program (this one is called Warmup)
# approximate number of hours you invested
# Grade Version (some programs will have A, B, C versions, this one does not)
# description of any major problems you ran into
# status of the program - does it compile, does it run perfectly, does it have bugs, any limitations, etc
```

Sample Input for C version
```
14
```
Corresponding Output
```
14 is Curzon 
```

Sample Input for B version
```
17
```
Corresponding Output
```
37 
```

Sample Input for A version
```
-5
9999
238
17
20
0
```
Corresponding Output
```
input not valid
5320879
4831
37
55
```
