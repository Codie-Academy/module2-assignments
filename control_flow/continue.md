**Quiz 1: Understanding the `continue` Statement**

1. What is the primary purpose of the `continue` statement in Swift?
   a) To exit a loop completely
   b) To skip the current iteration of a loop and move to the next
   c) To terminate a function

2. Which of the following loops is the `continue` statement typically used with?
   a) `for-in` loop
   b) `while` loop
   c) `if` statement

3. What is the effect of using `continue` in a loop?
   a) It ends the loop
   b) It immediately goes to the next iteration of the loop, skipping the remaining code in the current iteration

**Quiz 2: Practical Usage of `continue`**

1. In a `for-in` loop that iterates through an array of numbers, you encounter a number that meets a specific condition,
   and you want to skip processing that number and move to the next one. What statement do you use?

2. How does the use of `continue` differ from the use of `break` in a loop?
   a) `continue` ends the loop, while `break` skips the current iteration
   b) `continue` skips the current iteration and moves to the next, while `break` ends the loop

**Exercise 1: Removing Vowels**

Write a Swift program that takes a sentence as input and uses a `for-in` loop to remove all vowels (a, e, i, o, u) from the sentence. 
Print the modified sentence without vowels. For example, if the input is "Hello, World!", the program should print "Hll, Wrld!".

**Exercise 2: Finding Odd Numbers**

Create a Swift program that uses a `for-in` loop to iterate through numbers from 1 to 50. For each number, if it's even, skip to the 
next iteration using the `continue` statement. If it's odd, print the number. This will result in printing all the odd numbers between 1 and 50.

**Exercise 3: Skipping Specific Values**

Write a Swift program that uses a `for-in` loop to iterate through an array of integers. If the current integer is divisible by 5, use 
the `continue` statement to skip it. Print the remaining integers in the array. For example, if the array is [2, 5, 10, 7, 15, 3], the 
program should print "2 7 3."

These quizzes and exercises will help learners practice the usage of the `continue` statement in Swift, which is a valuable tool for 
controlling the flow of loops and skipping specific iterations based on conditions.
