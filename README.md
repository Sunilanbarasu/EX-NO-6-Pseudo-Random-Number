# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Pseudo Random Numbers:\n");

    for(i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}

```
# OUTPUT:
<img width="1527" height="920" alt="image" src="https://github.com/user-attachments/assets/5d2f0952-eddc-43de-a6a4-8a0ce545ae17" />

# RESULT:
Thus, the C program to generate Pseudorandom Numbers using the standard library functions rand(), srand() and time() was successfully implemented and executed.
