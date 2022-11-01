### Program 3 : Write username and roll number using scanf
```c
#include <stdio.h>
struct student
{
    char name[50];
    int roll;
};
int main()
{
    struct student s;
    
 printf("Enter The Information of Students :\n\n");
    
 printf("Enter Name : ");
    scanf("%s",s.name);
    
 printf("Enter Roll No. : ");
    scanf("%d",&s.roll);
    
    
    printf("\nDisplaying Information\n");
    
 printf("Name: %s\n",s.name);
    printf("Roll: %d\n",s.roll);
    return 0;
}
```

**Output : Enter name : Aaruni
Enter Roll No. : 2221002
Displaying Information
Name : Aaruni
Roll No.: 2221002**
