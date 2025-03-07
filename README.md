#include<stdio.h>
int main()
{
	int n,a,sum=0;
	printf("enter the value of n");
	scanf("%d",&n);
	int i=1;
	while(i<=n)
	{
		scanf("%d",&a);
		sum=sum+a;
		i++;
		if(a%2==0)
		{
		printf("even number are :%d\n",a);
	    }
		else
		{
		printf("odd number are :%d\n",a);
	}
	}
	printf("sum of natural numbers is :%d\n",sum);
    return 0;
}
