### Program 14 : Write a program to identify vowels.
```c
#include<stdio.h>
int main()
{
	char alphabet;
	printf("enter the alphabet");
	scanf("%c",&alphabet);
	switch (alphabet)
	{
		case 'a':
			printf("vowel");
			break;
			case 'e':
				printf("vowel");
				break;
				 case 'i':
				printf("vowel");
				break;
			case'o':
			printf("vowel");
			break;
			case'u':
			printf("vowel");
			break;
		
			
				default:
					printf("not a vowel");
					
	}
	return 0;
	
}
```
**Output:not a vowel**