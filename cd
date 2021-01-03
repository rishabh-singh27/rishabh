# RISHABH
#include <string.h>
#include<stdio.h>
#include<conio.h>
//RISHABH SINGH G1 160
int main()
{
    char string[1000];
    int i,alp=0,digits=0,op=0;

    printf("Enter  the string : ");
    gets(string);
    for(i=0;string[i];i++)
    {
        if((string[i]>=65 && string[i]<=90)|| (string[i]>=97 && string[i]<=122) )
          alp++;
        else if(string[i]>=48 && string[i]<=57)
         digits++;
        else
         op++;

 	}
 	printf("Total tokens= %d\n",alp+digits+op);
    printf("Alphabets = %d\n",alp);
    printf("Digits = %d\n",digits);
    printf("operators = %d", op);
    return 0;
}
