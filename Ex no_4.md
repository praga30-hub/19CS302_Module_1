# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start

2.Declare a variable age

3.Prompt the user to enter their age

4.Read the value of age

5.If age >= 21, then
  Display "Eligible for marriage"
Else
  Display "Not eligible for marriage"

6.End
   

## Program:
#include <stdio.h>

int main() {
    int age;

    //Step 1: Read age from the user
    
  printf("Enter your age: ");
   
  scanf("%d", &age);

    // Step 2: Check eligibility
  if (age >= 21) {
       
  printf("You are eligible for marriage.\n");
    }
    else 
    {
        printf("You are not eligible for marriage.\n");
    }

    return 0;
}

/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by: 
RegisterNumber:  
*/


## Output:

Enter your age: 21  

You are eligible for marriage.



## Result:
Thus the program was executed and the output was verified successfully.
