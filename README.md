# Program-4E
C module 4
EX NO-4)E)a C program to read an amount (integer value) and break the amount into smallest possible number of bank notes
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to read an amount (integer value) and break the amount into smallest possible number of bank notes
ALGORITHM:
1)Take a amount as input from user.2)using modulus and division operator find the multiples of each note .3)print the no of notes using printf() function.
PROGRAM:
```
#include <stdio.h>
int main()
{
    int n,s,p,r,q,t,k,a,b,c;
    scanf("%d",&n);
    printf("There are:\n");
    s=n/100;
    p=n%100;
    printf("%d Note(s) of 100.00\n",s);
    r=p/50;
    q=p%50;
    printf("%d Note(s) of 50.00\n",r);
    t=q/5;
    k=q%5;
    printf("%d Note(s) of 5.00\n",t);
    a=k/2;
    b=k%2;
    printf("%d Note(s) of 2.00\n",a);
    c=b/1;
    printf("%d Note(s) of 1.00\n",c);
}
```
OUTPUT:
<img width="807" height="630" alt="Screenshot 2025-10-19 234303" src="https://github.com/user-attachments/assets/cb7d3494-071a-4474-bb2d-c4c17823928d" />
RESULT:
Thus, a C program to read an amount (integer value) and break the amount into smallest possible number of bank notes has been executed successfully.
