#include<stdio.h>
#define size 5
main()
{
	int a[5]={30,18,58,39,92};
	int i,j,temp;
	for(i=0;i<size-1;i++)
	{
		for(j=i;j<size;j++)
		{
		if(a[i]>a[j])
		{
			temp=a[i];
			a[i]=a[j];
			a[j]=temp;
		}
		}
	}
		printf("The sorted array is\n");
		for(i=0;i<size;i++)
			printf("%d\n",a[i]);
	
}

