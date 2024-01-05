# practical
#include<stdio.h>

int main(){
    int a, b,c;
    char ch;

    printf("enter your operator(+,-,*,/,%)=");
    scanf("%c",&ch);

printf("enter values of a and b\n");
scanf("%d%d", &a,&b);

switch (ch)
{
case '+': c=a+b;
printf("addition of two numbers is %d", c);
    break;

case '-': c=a-b;
printf("subtraction of two numbers is %d", c);
break;

case '*': c=a*b;
printf("Multoplication of two numbers is %d", c);
    break;

case '/': c=a/b;
printf("Division of two numbers is %d", c);
break;

case '%': c=a%b;
printf("quotient of two numbers is %d", c);
break;

default:
    break;
}
return 0;
}


