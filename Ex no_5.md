# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1.Start

2.Declare an array to store marks of 7 subjects.

3.Declare variables for total, average, and percentage.

4.Use a loop to input marks for 7 subjects.

5.Add each mark to the total.

6.After the loop, calculate:

Average = total / 7

Percentage = (total / (7 × maximum_marks_per_subject)) × 100

7.Display the total, average, and percentage.

8.End. 

## Program:
#include <stdio.h>

int main() {
    int marks[7];
    int total = 0;
    float average, percentage;
    int i;
    int max_marks = 100; // Assuming each subject is out of 100

  
  printf("Enter marks for 7 subjects:\n");
   
  for(i = 0; i < 7; i++) {
        printf("Subject %d: ", i + 1);
        scanf("%d", &marks[i]);
        total += marks[i];
    }

  
  average = total / 7.0;
    percentage = (total / (7.0 * max_marks)) * 100;

  printf("\nTotal Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

   return 0;
}

/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
Developed by: 
RegisterNumber:  
*/


## Output:

Enter marks for 7 subjects:

Subject 1: 85

Subject 2: 90

Subject 3: 78

Subject 4: 88

Subject 5: 92

Subject 6: 81

Subject 7: 89

Total Marks = 603

Average Marks = 86.14

Percentage = 86.14%


## Result:
Thus the program was executed and the output was verified successfully.
