# generate-a-table
#include<stdio.h>
main()
{
int i,n,p=0;
printf("which table?");
scanf("%d",&n);
for(i=1;i<11;i++)
{
    p=p+n;

printf("%d * %d = %d\n",n,i,p);
}
    
}
