# Correct simple syntax errors

### Please help us fix this code. Here is the program in question:
```C++
#include <stdio.h>

int main(void) {
    printf ("This is code with errors: ")
    printf "Fix them!";
    return 0;
}
```
### And here are the compiler error messages:


```C++

/user-input:4:43: error: expected ';' after expression
    printf ("This is code with errors : ")
                                          ^
                                          ;
/user-input:5:11: error: expected ';' after expression
    printf "Fix them!";
          ^
          ;
/user-input:5:5: warning: expression result unused
    printf "Fix them!";
    ^~~~~~
/user-input:5:12: warning: expression result unused
    printf "Fix them!";
          ^~~~~~~~~~~  
```

**_Warning: We cannot allow additional errors. You are therefore not allowed to write new code or remove code. You only need to correct the errors in the given code._**
___

# Solution
```C
#include <stdio.h>
int main(void) {
    printf ("This is code with errors: ");
    printf ("Fix them!");
    return 0;
}
```


