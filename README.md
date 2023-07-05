# C-Program

#include<stdio.h>
int main()
{
    int strt,end,sum=0;
    printf("Enter the start and end number: ");
    scanf("%d%d",&strt,&end);
    for(strt;strt<=end;strt++)
    {
        if(strt%2==0)
        {
            sum = sum+strt;
            printf(" %d",strt);
            if(strt<end)
                printf(" +");
        }
    }
    printf(" = %d",sum);
}
