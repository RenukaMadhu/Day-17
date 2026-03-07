# Day-17
This C program calculates the factorial of a given number using a for loop.
#include <stdio.h> → Includes the standard input/output library for using printf and scanf.
int n, i; → Declares variables n (input number) and i (loop counter).
long long factorial = 1; → Stores the factorial value. It is initialized to 1.
printf("Enter a number: "); → Asks the user to enter a number.
scanf("%d", &n); → Reads the input number from the user.
for(i = 1; i <= n; i++) → Loop runs from 1 to n.
factorial = factorial * i; → Multiplies numbers step-by-step to calculate factorial.
printf() → Displays the final factorial result.
