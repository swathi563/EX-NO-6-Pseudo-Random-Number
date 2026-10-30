
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

    printf("Pseudorandom numbers are:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```

# OUTPUT:

Enter the number of random numbers: 6

Pseudorandom numbers are:

557242885

1550853698

1943947565

817026389

1471073671

1717365907


<img width="687" height="272" alt="image" src="https://github.com/user-attachments/assets/ecac78df-d326-49ac-87b4-e6d1e63df44c" />

# RESULT:
Thus, pseudorandom number generation was successfully implemented using the C standard library functions rand(), srand(), and time().
