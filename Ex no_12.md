# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## DATE:11/05/2025
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
1. Start the program.
2. Take input of an integer number n from the user.
3. Create a function that takes n as an argument and checks whether it is prime.
4. Inside the function, use a loop to check if n is divisible by any number from 2 to √n.
5. Print whether the number is prime or not and end the program.

## Program:
```
/*
C program to check whether the given number is prime or not using function without return type and with arguments.
Developed by: AKILA P
RegisterNumber:  212222060012

#include <stdio.h>

void checkPrime(int n) {
    int i, isPrime = 1;

    if (n <= 1) {
        printf("Not a prime number\n");
        return;
    }

    for (i = 2; i * i <= n; i++) {
        if (n % i == 0) {
            isPrime = 0;
            break;
        }
    }

    if (isPrime)
        printf("Prime number\n");
    else
        printf("Not a prime number\n");
}

int main() {
    int num;
    scanf("%d", &num);
    checkPrime(num);
    return 0;
}
*/
```

## Output:
![444987182-2cd21e42-d2e0-49d0-923b-1f7141eabe33](https://github.com/user-attachments/assets/cb9f4b93-c2a5-4778-a4cc-2b5168f67890)



## Result:
Thus the program was executed and the output was verified successfully.
