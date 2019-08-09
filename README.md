#include<stdio.h>
int main()
{
  int x,p,amount;
  scanf("%d %d",&x,&p);
  amount=x*(100-p)/100;
  printf("please output the amount necessary to order for free.\n");
  if(amount==1)
    printf("%d",amount);
  return 0;
  }
 
