//programm which finds next largest mulplier divisible by another ineger between two integers.
#include<stdio.h>
main()
{
int i,j,k; //where i>j
printf("enter any two integers:\n");
scanf("%d%d",&i,&j);
k=i+j-i%j;
printf("the next largest multiplier is:\n%d",k);
return 1;
}
