# Assignment 11

For this assignment you will take a number as input and output whether or not it is a palindrome.

A palindrome is a number or word (we are only concerned with numbers here) that is the same forward as backward. (Ex: 121, 1234321, 74933947, 3223, 2)

To receive full credit you must have the following program specifications:

1. Class called `Number` with the following parts:
  * An instance variable that holds the number.
  * A constructor that initializes the instance variable that will hold the number.
  * A method named `getNthDigit` that returns a specified digit in the number (think back to the car wash and NumberManipulator--A7).
  * A method named `isPalindrome` that returns true if the number is a palindrome and false if it isn't.
2. Runner class called `PalindromeRunner` that has the following parts:
  * Prompts user to enter a number.
  * Takes user input (tell user to enter 5 digits or less).
  * Use a conditional to check that user didn't enter more than 5 digits.
  * Creates a `Number` object using the number input by the users.
  * Outputs whether the number input is a palindrome.

### Sample Outputs
```
Enter a 5 digit number: 21312
21312 is a palindrome.
```
```
Enter a 5 digit number: 22312
22312 is not a palindrome.
```
```
Enter a 5 digit number: 22312123
You entered a number with more than 5 digits.
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

