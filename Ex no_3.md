# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:17/03/2026
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
Start.
Declare the variables.
Prompt the user to enter a value.
Read the value using scanf.
Calculate the number of years using the formula:
End .  

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
#include <stdio.h> 
#include <math.h>
int main()
{
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r);
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n));
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);
return 0;
}
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
*/
```

## Output:

<img width="828" height="320" alt="image" src="https://github.com/user-attachments/assets/238a3ef9-0d75-4be3-a76f-7b1279c79208" />


## Result:
Thus the program was executed and the output was verified successfully.
