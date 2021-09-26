#include <stdio.h>

int main() 
{
	int n1, n2;
	int a, b; //a는 행,b는 열

	scanf("%d %d", &n1, &n2);



	if (n1 >= n2)
	{
		n2 = a;
		n1 = b;
	}
	else if(n1<n2)
	{
		n1 = a;
		n2 = b;
	}

	int i, j,k;

	for (i = 0; i < a; i++)
	{
		for (j = 0; j < b; j++)
		{
			printf("*");

			for (k = a - 1; k > 0; k--)
			{
				printf(" ");
			}
		
		}
	
	
	}






	return 0;
}
