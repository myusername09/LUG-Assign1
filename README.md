# LUG-Assign1


#include<stdio.h>

int main()
{
    printf("Hello,welcome to my first assignment at LetsUpGrade : )");
    printf("\n");
    int M;
    printf("enter value of M=");
    scanf("%d",&M);
    if(M%3==0 && M%5==0)
    {
        printf("%d is a Good Number",M);
    }
    if(M%3==0 && M%5!=0)
    {
        printf("%d is a Bad Number",M);
    }
    if(M%3!=0 && M%5==0)
    {
        printf("%d is a Poor Number",M);
    }
    if(M%3!=0 && M%5!=0)
    {
        return -1;
    }
    return 0;
}
