# 4
int main()
{
	int i = 0;
	while (i <= 10)
	{
		if (i < 5)
			printf("%d\n", i);
		i++;
	}
	return 0;
}
 打印 1 2 3 4 

int main()
{
	int i = 0;
	while (i <= 10)
	{
		i++;
		if (i == 5)	
		continue;				
	printf("%d\n", i);
	}
	return 0;

}
打印：1 2 3 4 6 7 8 9 10 11

int main()
{
	int i = 0;
	while (i <= 10)
	{
		i++;
		if (i == 5)
			break;
		printf("%d\n", i);
	}
	return 0;

}
打印：1 2 3 4
