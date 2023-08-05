# Prinft 

printf function from the C library. This library allows you to format and print output to the standard output stream, similar to printf.

## Features
- Supports various format specifiers, including c, s, p, d, i, u, x, X, and %
- Handles basic conversions and formatting options
- Allows printing of characters, strings, pointers, decimal and integer numbers, and hexadecimal numbers
- Can handle both lowercase and uppercase hexadecimal formatting
- Provides a convenient way to output formatted text

##  Usage
To use the ft_printf function in your C program, follow these steps:

1. Include the "libftprintf.h" header file in your source code.
2. Compile your program with the libftprintf.a library using the provided Makefile.
3. Call ft_printf function with a format string and any additional arguments.

Here's an example of how to use ft_printf:

```c
#include "libftprintf.h"

int main(void)
{
	ft_printf("Hello, %s!\n", "world");
	ft_printf("The answer is %d.\n", 42);

	return (0);
}
```

In the above example, ft_printf is used to print a string and an integer value. The format specifier `%s` is used for the string, and `%d` is used for the integer.

## Compilation
To compile your program with the libftprintf.a library, use the provided Makefile. The Makefile includes the following commands:

- `make all`: Compiles your program and creates the libftprintf.a library.
- `make clean`: Removes object files generated during compilation.
- `make fclean`: Removes the libftprintf.a library and object files.
- `make re`: Performs a clean build by running `make fclean` followed by `make all`.
