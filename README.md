# M5-D2
AIM:
Write a C program to swap the values m = 25, n=100 using function pointers (using temporary variable) 
PROGRAM:
```
#include <stdio.h>
int main()
{
    int m,n,*a,*b,c;
    scanf("%d %d",&m,&n);
    
    a=&m;
    b=&n;
    printf("m is %d, n is %d",*a,*b);
    c=*a;
    *a=*b;
    *b=c;
    
    printf("\nm is %d, n is %d",*a,*b);
}
```
OUTPUT:

<img width="675" height="431" alt="image" src="https://github.com/user-attachments/assets/d5b7b73a-9720-465f-a41c-32f56ebc09d1" />
RESULT:
Thus the code run successfully!
