Program 39: Write a program to print the multiplication table of 5 using while loop.
```c
#include<stdio.h>
int main()
{
    int i=0;
    while(i<11)
    {
        printf("%d * %d = %d\n" , 5 , i, 5*i );
        i++;
    }
    return 0;
}
```
**Output:5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
5 * 4 = 20
5 * 5 = 25
5 * 6 = 30
5 * 7 = 35
5 * 8 = 40
5 * 9 = 45
5 * 10 = 50**