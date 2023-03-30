# c
#include <stdio.h>

int main(void)
{
    char c;
    int i;
    float f;

    c = 10000;
    i = 1.23456 + 10;
    f = 10 + 20;
    printf("c = %d, i = %d, f = %f\n" , c, i, f);

    return 0;
   
}

   int number;

    printf("정수를 입력하시오:");
    scanf("%d" , &number);

    if(number > 0)
    {
        printf("양수입니다.");
    }
    printf("입력된 값은 %d입니다." , number);

    return 0;
    
    
    int number;
    
    printf("정수를 입력하시오:");
    scanf("%d" , &number);

    if(number % 2 == 0)
    
        printf("입력된 정수는 홀수입니다.\n");
    else  
        printf("입력된 정수는 홀수입니다.\n");
    
    
