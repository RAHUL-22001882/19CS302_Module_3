# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:11/05/2025
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1. Start the program.
2. Create a function with no arguments that reads a decimal number from the user.
3. Inside the function, convert the number to binary using a loop and store the binary digits.
4. Return 0 from the function after displaying the binary equivalent.
5. Call the function from main() and end the program.  

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by: AKILA P
RegisterNumber:  212222060012

#include <stdio.h>

int convertToBinary() {
    int num, binary[32], i = 0;
    scanf("%d", &num);

    if(num == 0) {
        printf("Binary: 0\n");
        return 0;
    }

    while(num > 0) {
        binary[i++] = num % 2;
        num /= 2;
    }

    printf("Binary: ");
    for(int j = i - 1; j >= 0; j--) {
        printf("%d", binary[j]);
    }
    printf("\n");

    return 0;
}

int main() {
    convertToBinary();
    return 0;
}
*/
```

## Output:
![444986634-b691156d-ff67-44e5-b0fe-6acee15b9809](https://github.com/user-attachments/assets/8eac6873-db8f-409e-aa59-bb731e5a9d3c)



## Result:
Thus the program was executed and the output was verified successfully.
