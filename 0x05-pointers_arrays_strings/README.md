(File 0-reset_to_98.c) a functionthat takes a pointer to an int as parameter and updates the value it points to to 98. Prototype: void reset_to_98(int *n);

(file 1-swap.c) a function that swaps the values to two integers. Prototype: void swap_int(int *a, int*b);

(file 2-strlen.c) function that returns the length of a string. Prototype: int_strlen(char *s);

(file 3-puts.c) a function that prints a string in reverse, followed by a new line, to stdout. Prototype: void_puts(char *str);

(file 4-print_rev.c) a function that prints a string, in reverse, followed by a new line. Prototype: void print_rev(char *s);

(file 5-rev_string.c) a function that reverses a string. Prototype: void rev_string(char *s);

(file 6-puts2.c) a function that prints every other character of a string starting with the first character, followed by a new line. Prototype: void puts2(char *str);

(file 7-puts_half.c) function that prints half of a string, followed by a new line. Prototype: void puts_half(char *str); The function should print the second half of the string if the number of characters is odd, the function should print the last n characters of the string, where n = (length_of_the_string - 1) /2

(file 8-print_array.c) a function that prints n elements of an array of integers, followed by a new line. Prototype void print_array(int *a, int n); wher n is the number of elements of the array to be printed, numbers must be seperated by comma, followed by a space. The numbers should be displayed in the sameorder as they are stored in the array. You are allowed to use printf

(file 9-strcpy.c) a function that copies the string to by src, including the terminating null byte (\0), to the buffer pointed to by dest.  Prototype: char *_strcpy(char *dest, char *src); Return value: the pointer to dest FYI: The standard library provides a similar function: strcpy. Run man strcpy to learn more.

(file 100-atoi.c) a function that converts a string to an integer. Prototype: int_atoi(char *s); The number in the string can be preceded by an infinite number in the string can be preceded by an infinite number of characters, you need to take into account all the - and + signs before the number. if there are no numbersin the string, the function must return 0. You not allowed to use long, you are not allowed to declare new variables of "type" array you are not allowed to hard-code special values. We will use the -fsanitize=signed-integer-overflow gcc flag to compile your code. For your information: The standrd library provides a similar function: atoi. Run man atoi to learn more.

(file 101-keygen.c) a program that generates a random valid passwords for the program that generates random valid passwords for the program 101-crackme. You are allowed to use the standard library, You do not have to pass the betty-style tests (you still need to pass the betty-doc tests) man srand, rand, time gdb and objdump can hel.
