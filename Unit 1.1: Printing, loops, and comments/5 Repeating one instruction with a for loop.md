# Repeating one instruction with a for loop

### Activity: use a for-loop to print a line multiple times
You would like to display the same line of text several times, but you do not wish to have to type it multiple times in your program.

##### Please print the following text to the screen:

```C
C is fun!
C is fun!
C is fun!
```
To make this a bit more challenging, you are only allowed to use one single "printf" statement, and you are not allowed to repeat text inside your printf statement.


**_Warning_: Your output needs to look exactly like the above output.**

___

# Solution
```C
#include <stdio.h>

int main(void) {

    int i;

    for(i = 0; i < 3; i++) {
        printf("C is fun!\n");
    }

    return(0);
}

```
