# ft_printf Project

## Program Name

**ft_printf**

## Description

The `ft_printf` project is a custom implementation of the `printf` function, similar to the standard C library version. This project requires you to implement your own version of the `printf` function to output formatted data to the console.

### Functionality

The `ft_printf` function should support the following features:

- Output string
- Output integer (both positive and negative)
- Output character
- Output pointer address
- Output unsigned integer
- Output hexadecimal (lowercase and uppercase)
- Output percentage symbol (`%`)

### Supported Format Specifiers

The following format specifiers should be supported by your implementation:

- `%c` - Character
- `%s` - String of characters
- `%p` - Pointer address
- `%d` or `%i` - Signed decimal integer
- `%u` - Unsigned decimal integer
- `%x` - Unsigned hexadecimal integer (lowercase)
- `%X` - Unsigned hexadecimal integer (uppercase)
- `%%` - Percentage symbol

### Example Usage

```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s! Your score is %d.\n", "World", 100);
    return 0;
}
output :
Hello, world! Your score is 100
