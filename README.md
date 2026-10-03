Prime Number Checker Using Function in C
Description

This C program uses a function to determine whether a given positive integer is a prime number.

Problem Statement

Write a C program that uses a function to check whether a given positive integer is prime.

Concepts Used
Functions
Conditional statements
For loop
Modulus operator
Prime number logic
How It Works
The user enters a positive integer.
The isPrime() function checks whether the number is divisible by any integer from 2 up to its square root.
If a divisor is found, the number is not prime.
Otherwise, the number is prime.
Sample Input
7
Sample Output
7 is a prime number.
Another Example

Input:

10

Output:

10 is not a prime number.
Time Complexity

O(√n)

Language

C

How to Compile and Run
gcc prime_function.c -o prime.exe

On Windows PowerShell, run:

.\prime.exe
