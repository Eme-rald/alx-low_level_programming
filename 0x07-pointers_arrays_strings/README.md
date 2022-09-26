(file 0-memset.c) a function that fills memory with a constantbyte. Prototype: char*_memset(char *s, char b, unsigned int n); The _memset() function fills the first n bytes of the memory area pointed to by s with the constant byte b returns a pointer to the memory area s FYI: The standard library provides a similar function: memset. Run man memset to learn more.

(file 1-memcpy.c) a function that copies memory area. Prototype: char *_memcpy(char *dest, char *src, unsigned int n); The _memcpy() function copies n bytes from memory area src to memory area dest. Returns a pointer to dest FYI: The standard libray provides a similar function: memcpy. Run man memcpy to learn more.

(file 2-strchr.c) a function that locates a character in a string. Prototype: char *_strch(char *s, char c); Returns a pointer to the first occurrence of the character c in the string s, or NULL if the character is not found FYI: The standard library provides a similar function: strchr. Run man strchr to learn more.

(file 3-strspn.c) a function that gets the length of a prefix substring. Prototyppe: unsigned int _strspn(char *s, char *accept); Returns the number of bytes from accept FYI: The standard library provides a similar function: strspn. Run man strspn to learn more.


(file 4-strpbrk.c) a function that searches a string for any of a set of bytes. Prototype: char *_strpbrk(char *s, char *accept); The _strpbrk() function locates the first occurence in the strings of any of the bytes in the string accept Returns a pointer to the byte in s that matches one of the bytes in accept, or NULL if no such byte is found FYI: The standard library provides a similar function: strpbrk. Run man strpbrk to learn more.

(file 5-strstr.c) a function that locates a substring. Prototype: char *_strstr(char *haystack, char *needle); The _strstr() function finds the first occurence of the substring needle in the string haystack. The terminating null bytes (\0) are not compared Returns a pointer to the beginning of the located substring, or NULL if the substring is no found. FYI: The standard library provides a similar function: strstr. Run man strstr to learn more.

(file 7-print_chessboard.c) a function that prints the chessboard. Prototype: void print_chessboard(char(*a[8]);

(file 8-print_diagsums.c) a function that prints the sum of the two diagonals of a square matrix of integers. Prototyppe: void print_diagsums(int a, int size); format: see example you are allowed to use the standard library Note that in the following example we are casting an int[] into an int. This is not something you should do. The goal here is to make sure you understand how an array of array is stored in memory.

(file 100-set_string.c) a function that sets the value of a pointer to a char. Prototype: void set_string(char **s, char *to);

(file 101-crackme_password) a file that contains the password for the crackme2 executable. Your file should contain the exact password, no new line, no extra space ltrace, ldd, gdb and objdump can help you may need to install the openssl library to run the crackme2 program: sudo apt install libssl-dev Edit the source list sudo nano/etc/apt/sources.list to add the following line: deb http://security.ubuntu.com/ubuntu xenial-security main. Then sudo apt update and sudo apt install libssl1.0.0
