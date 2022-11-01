### Program 3 : Write a code to enter username and roll number using scanf
```c
#include<stdio.h>
int main(){
int Roll_No;
char Username[50];
printf(" What is your Username ?  ");
scanf("%s", Username);
printf(" What is your Roll No ? ");
scanf(" %d", &Roll_No);
printf("\n Your Username is ");
printf("%s", Username);
printf("\n Your Roll no is ");
printf("%d \n", Roll_No);
return 0;
}
```
**Output: What is your Username ? Aaruni**

**What is your roll no ? 2221002**

**Your Username is Aaruni**

**Your Roll no is 2221002**
