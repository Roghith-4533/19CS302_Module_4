# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Start
2.Declare variables: num, leftShift, rightShift
3.Display the message: "Enter an integer"
4.Read the integer num from the user
5.Perform left shift: leftShift = num << 1
6.Perform right shift: rightShift = num >> 1
7.Display the original number num
8.Display the result of the left shift (leftShift)
9.Display the result of the right shift (rightShift)
10.End

## Program:
```
#include <stdio.h>
int main() {
    int num, leftShift, rightShift;
    printf("Enter an integer: ");
    scanf("%d", &num);
    leftShift = num << 1;
    rightShift = num >> 1;
    printf("Original number: %d\n", num);
    printf("After left shift by 1: %d\n", leftShift);
    printf("After right shift by 1: %d\n", rightShift);
    return 0;
}
```


## Output:
![WhatsApp Image 2025-05-19 at 15 30 05_754934ba](https://github.com/user-attachments/assets/ce266e04-8991-4fef-b465-0c9fd21152bd)





## Result:
Thus the program was executed and the output was verified successfully.
