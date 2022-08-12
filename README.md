_printf(
The printf project is a collaboration between Biniyam Asfaw and Alexander Sibhatu ,students of Software Engineering at ALX.
This function named "_printf()" imitates the actual "printf()" command located in the stdio.h library of C programming Language. It contains some of the basic features and functions found in the manual 3 of "printf".
  int _printf(const char *format, ...) 
Where format contains the string that is printed.
_printf() is a variadic function, it can receives n arguments that replace by n tags written inside the string.
The format tags prototype is the following:
%[flags][length]specifier
If the program runs successfully, the return value is the amount of chars printed.
_printf.c
Own Printf Function That Performs Formatted Output Conversion And Print Data.
holberton.h
Header File Where All Prototypes Are Saved.
get_print_func.c
Pointer To A Function That Selects The Correct Function To Perform The Operation
print_buf.c
Function That Prints The Buffer
handl_buf.c
Function That Concatenates The Buffer Characters.
