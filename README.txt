Program name: c program 
Arafat and Lisa wrote the program. 
This program is an agile/iterative approach allowing the user to choose different operations from a menu. It includes a debugging statement when compiled with the “debug” command line switch. 
For the command line switch, we collected data to enable/ disable debugging and use that variable in conditional testing to output debugging information or not.

Function 1: add_numbers
-Input Type(s): Two integers (int)
- Output Type: Integer (int)
- Algorithm Description: Adds two integers and returns the result.

 Function 2: multiply_numbers
- Input Type(s): Two floating-point numbers (float)
- Output Type: Floating-point number (float)
- Algorithm Description: Multiplies two floating-point numbers and returns the result.

 Function 3: reverse_string
- Input Type(s): Character array (string)
- Output Type: void (Does not return anything)
- Algorithm Description: Reverses the input string in place and prints the reversed string.

 Files Required:
1. main. c - Main program file containing the menu and switch logic. (C code)
2. functions.c - File containing the function definitions. (C code)
3. functions.h - Header file containing function prototypes. (Header file)

Program Description:
The program is a menu-driven application that allows users to perform various operations based on their selection. It starts with a command-line switch that enables or disables debugging mode. The program prompts the user with a menu and continuously loops until the user decides to exit. It offers options to add two integers, multiply two floats, reverse a string, or enter two words. Based on the user's input, the program calls the corresponding function and prompts the user for additional information.

Menu Definition and Usage:
The menu presents the following options:
1) Add 2 numbers (integers)
2) Multiply 2 numbers (floats)
3) Read in a string and reverse the string as output
4) Enter 2 words
