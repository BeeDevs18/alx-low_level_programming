Tasks file description;
main.h: Header file containing prototypes for all functions written in the project.

0-strcat.c: C function that concatenates two strings.

Adds a terminating null byte at end.
1-strncat.c: C function that concatenates two strings using at most an inputted number of bytes.

Adds a terminating null byte at end, unless source string is longer than maximum byte number.
2-strncpy.c: C function that copies a string, including the terminating null byte, using at most an inputted number of bytes.

If the length of the source string is less than the maximum byte number, the remainder of the destination string is filled with null bytes.
Works identically to the standard library function strncpy.
3-strcmp.c: C function that compares two strings.

Returns the difference in bytes at point of difference.
Works identically to the standard library function strcmp.
4-rev_array.c: C function that reverses the content of an array of integers.

5-string_toupper.c: C function that changes all lowercase letters of a string to uppercase.

6-cap_string.c: C function that capitalizes all words of a string.

7-leet.c: C function that encodes a string into 1337, without switch or ternary operations and using only one if and two loops.

Letters a and A are replaced by 4.
Leters e and E are replaced by 3.
Letters o and O are replaced by 0.
Letters t and T are replaced by 7.
Letters l and L are replaced by 1.
100-rot13.c: C function that encodes a string to rot13, without switch or ternary operations and using only one if and two loops.

101-print_number.c: C function that prints an integer without using long, arrays, pointers, or hard-coded special values.

102-magic.c: C program that prints a[2] = 98 using pointer magic.

Completion of this source code.
103-infinite_add.c: C function that adds two numbers stored in strings to a buffer.

Assumes that strings are never empty and that numbers will always be positive, or 0.
Assumes there are only digits stored in the number strings.
If result can be stored in the buffer, returns a pointer to the result.
If result cannot be stored in the buffer, returns 0.
104-print_buffer.c: C function that prints the content of an inputted number of bytes from a buffer.

Prints 10 bytes per line.
Starts with the position of the first byte in hexadecimal (8 chars), starting with 0.
Each line shows the hexadecimal content (2 chars) of the buffer, 2 bytes at a time, separated by a space.
Each line shows the content of the buffer. Prints the byte if it is printable; if not, prints ..
Each line ends with a new line \n.
If the inputted byte size is 0 or less, the function only prints a new line.
