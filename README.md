# c-language
MY FIRST C LANGUAGE CODE
#include<stdio.h>
#include<math.h>
int main(){
    float a,b,add,sub,mul,div,mod;
    printf("enter first number\n");
    scanf("%f",&a);
    printf("enter second number\n");
    scanf("%f",&b);
    add=a+b;
    sub=a-b;
    mul=a*b;
    div=a/b;
    mod=a%b;
    printf("addition is %f\n ",add);
    printf("subtraction is %f\n",sub);
    printf("multipy is %f\n",mul);
    printf("division is %f\n",div);
    printf("modalus is%f \n",mod);
    return 0;
}
