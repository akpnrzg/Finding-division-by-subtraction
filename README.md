//# Finding-division-by-subtraction
//Finding division by subtraction
#include <stdio.h>
#include <conio.h>
int main(void)
{
    int num,deno,i=0;
    printf("Enter numerator and denaminator: ");
    scanf("%d%d",&num,&deno);

    for(i=1;num>deno;i++)
        num-=deno;
    printf("\nResult: %d\n",i);
    return 0;

}
