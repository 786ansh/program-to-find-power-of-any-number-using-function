# program-to-find-power-of-any-number-using-function
#include <stdio.h>
int p_ow(int,int);

int main()
{
    int a;
    printf("enter a number");
    scanf("%d",&a);
    int r;
    printf("enter range");
    scanf("%d",&r);
    p_ow(a,r);
}
int p_ow(int a, int r)
{
    int p=1;
    for(int i=1;i<=r;i++)
    p=p*a;
    printf("%d",p);
}




