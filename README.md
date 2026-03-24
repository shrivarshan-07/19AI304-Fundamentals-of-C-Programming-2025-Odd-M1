# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.

# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 29 / 01 / 2026
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```
#include <stdio.h>

int main() {
    char c1, c2, c3;
    scanf(" %c", &c1);
    scanf(" %c", &c2);
    scanf(" %c", &c3);
    printf("%c %c %c", c3, c2, c1);
    return 0;
}
```
# Output:
<img width="407" height="258" alt="image" src="https://github.com/user-attachments/assets/5d6be046-8f35-4884-b799-f5db5cdadf54" />


# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```
#include <stdio.h>

int main() {
    int A;
    scanf("%d", &A);
    if (A > 0) {
        printf("Positive number");
    } else {
        printf("Not a positive number");
    }

    return 0;
}
```
# Output:
<img width="538" height="198" alt="image" src="https://github.com/user-attachments/assets/eb3d52f0-6440-496f-a05e-31261ffb52c3" />


# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```
#include <stdio.h>
int main() {
    float a, b, min;
    scanf("%f %f", &a, &b);
    min = (a < b) ? a : b;
    printf("Minimum = %.2f", min);
    return 0;
}
```
# Output:
<img width="532" height="226" alt="image" src="https://github.com/user-attachments/assets/3227f344-3429-4c2c-bc42-e374596357bc" />

# Result: 

Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>

int main() {
    int n;

    // Read the input value
    scanf("%d", &n);

    // Check if the value is equal to 1
    if (n == 1) {
        printf("The value is equal to 1");
    }

    return 0;
}
```
# Output:

<img width="482" height="186" alt="image" src="https://github.com/user-attachments/assets/9e97a820-b317-4db9-97ae-65e26c57bbbb" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>

int main() {
    float m1, m2, m3, total, percent;

    // Read marks of three subjects
    scanf("%f %f %f", &m1, &m2, &m3);

    // Calculate total and percentage
    total = m1 + m2 + m3;
    percent = (total / 300) * 100;

    printf("Total = %.2f\n", total);
    printf("Percentage = %.2f\n", percent);

    // Check minimum marks and division
    if (m1 >= 35 && m2 >= 35 && m3 >= 35) {
        if (percent >= 60)
            printf("First Division");
        else if (percent >= 50)
            printf("Second Division");
        else if (percent >= 35)
            printf("Pass");
        else
            printf("Fail");
    } else {
        printf("Fail");
    }

    return 0;
}
```
# Output:

<img width="445" height="276" alt="image" src="https://github.com/user-attachments/assets/d5a9d776-44d9-41d4-ad56-13ab21731b25" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


