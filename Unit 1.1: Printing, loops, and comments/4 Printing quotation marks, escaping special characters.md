# Printing quotation marks, escaping special characters

### Activity: print special characters
You now know all about special characters now - in particular, how to print them to your screen. In this task, you'll get some more practice with these types of characters.

Your goal is to print Dennis Ritchie's famous quote to the screen just as shown below. To make this task a bit harder, you are only allowed to use one printf statement in your entire program. Be sure not to omit anything and not to print anything extra.

#### Output:
```C
Dennis Ritchie said:                                                            
"The only way to learn a new programming language is by writing programs in it."

```

**_Warning_: You need to print everything exactly as shown above, including the attribution.**

___

# Solution
```C
#include <stdio.h>

int main(void) {

    printf("Dennis Ritchie said:\n\"The only way to learn a new programming language is by writing programs in it.\"");

    return(0);
}
```
