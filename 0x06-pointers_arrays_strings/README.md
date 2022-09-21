(file 0-strcat.c) a function that concatenates two strings. Prototype: char *_strcat(char *dest, char *src); This function appends the src string to the dest string, overwriting  the terminating null byte (\0) at the end of the dest, and then adds a terminating null byte Returns a pointer to the resulting string dest FYI: The standard library provides a similar function: strcat. Run man strcat to learn more.

(file 1-strcat.c) a function that concatenates two strings. Prototype: char *_strncat(char *dest, char *src,  int n); The _strncat function is similar to the _strcat function, except that it will use at most n byte; and src does not need to be null-terminated if it contains n or more bytes. Return a pointer to the resulting string dest FYI: The standard library provides a similar function: strncat. Run man strncat to lear more.

file 2-strncpy.c) a function that copies a string. Prototype: int_strncpy(char *dest, char *src, int n); Your function should work exactly like

 strncpy FYI: The standard library provides a similar function: strncpy. Run man strncpy to learn more.                                         

                                                                                                                                                

(file 3-strcmp.c) a function that compares two strings. Prototype: int_strcmp(char *s1, char *s2); Your function should work exactly like strcmp

 FYI: The standard library provides a similar function: strcmp. Run man strcmp to learn more.                                                   

                                                                                                                                                

(file 4-rev_arrays.c) a function that reverses the content of an array of integers. Prototype: void reverse_array(int *a, intn); Where n is the 

number of elemnts of the array.                                                                                                                 

                                                                                                                                                

(file 5-string_toupper.c) a function that changes all lowercase letters of a string to uppercase. Prototype: char *string_toupper(char*);       

                                                                                                                                                

(file 6-cap_string.c) function that capitalises all words of a string. Prototype: char *cap_string(char *); seperators of words: space, tabulati

on, new line, ,, ;, ., !, ?, ", (,), {, and}.                                                                                                   

                                                                                                                                                

                                                                                                                                                

(file 7-leet.c) function that encodes a string into 1337. Letters a and A should be replaced by 4 letters e and E should be replaced by 3 letter

s o and O should be replaced by 0 letters t and T should be replaced by 1 prototype: char *leet(char *); You can only use two loops in your code

, you are not allowed ton use switch, you are not allowed to use any ternary operation.                                                         

                                                                                                                                                

(file 100-rot13.c) a function that encodes a string using rot13. Prototype: char *rot13(char *); you can only use if statement once in your code

. you are not allowed to use any ternary operation.                                                                                             

                                                                                                                                                

(file 101-print_number.c) a function that prints an integer. prototype: void print_number(int n); you can only use _putchar function to print, y

ou are not allowed to use long you are not allowed to hard-code special values.                                                                 

                                                                                                                                                

(file 102-magic.c) Add one line to this code, so that the program prints a[2] = 98, followed by a new line. You are not allowed to use the varia

ble a in your new line of code you are not allowed to modify variable p, you can only write one statement, you are not allowed to use , you are 

not allowed to code anything else than the line of expected line of code at the expected line. your code should be written at line 19, bnefore t

he ; Do not remove anything from the initial code (not even the comments) and dont change anything but the line of code you are adding (dont cha

nge the spaces to tabs!) You are allowed to use the standard library.                                                                           

                                                                                                                                                

(file 103-infinite_add.c) a function that adds two numbers. Prototype: char *infinite_add(char *n1, char *n2, char *r, int size_r); Where n1 and

 n2 are the two numbers r is the buffer that the function will use to store the result size_r is the buffer size. The function returns a pointer

 to the result. you can assume that you will always get positive numbers, or 0 you can assume that there will be only digits in the strings n1 a

nd n2 n1 and n2 will never be empty if the resultcan notbe atored in r the function must return 0.                                              

                                                                                                                                                

(file 104-print_buffer.c) a function that prints a buffer. prototype: void print_buffer(char *b, int size); The function must print the content of size bytes of the buffer pointed by b. The output should print 10 bytes per line each line starts with the position of the first byte of the line in hexadecimal (8 chars), starting with 0 each line shows the hexadecimal content (2 chars) of the buffer, 2 bytes at a time, seperated by a space each line shows the content of a buffer, 2 bytes at a time, seperated by a space. Each line shows the content of a buffer, if the byte is printable character, print the letter, if not, print . each line ends with a new line \n if size is 0 or less, the output should be a new line only \n you are allowed to use the standard library. The output should look like the following example, and formatted exactly the same way.
