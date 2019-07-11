# Printing multiple lines with one printf statement

### Activity: create ASCII art by printing multiple lines

Do you know how to print characters to the screen? Do you know how to start a new line? Then you are ready to print artwork with characters!

Your goal is to display the piece of abstract art shown below, using just a single printf command.
```C
*****
**|**
*|.|*
|...|
.....
```
>Warning! The artist who created this work insists on any reproduction of the work to be 100% faithful, so you are not allowed to make any changes.

**_Be careful with spacing especially - if you print out too few or too many spaces your program will be graded as incorrect._**

___

# Solution
```C
#include <stdio.h>

int main(void) {

    printf("*****\n**|**\n*|.|*\n|...|\n.....");

    return(0);
}
```