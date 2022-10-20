//# C-prime-plus-
//C prime plus第六章答案
//第一题
int main()
{
	char letter[26];
	int i = 0;
	char ch = 'a';
	int sz = sizeof(letter) / sizeof(letter[0]);
	for (i = 0, ch = 'a'; i < sz; i++, ch++)
	{
		letter[i] = ch;
	}
	for (i = 0; i < sz; i++)
	{
		printf("%c ", letter[i]);
		}
	return 0;
}
//第二题
int main()
{
	int row = 5;
	int i, j;
	for (i = 0; i < row; i++)
	{
		for (j = 0; j <= i; j++)
		{
			printf("$");
		}
		printf("\n");
	}
	return 0;
}
//第三题
int main()
{
	int row = 6;
	int i, j;
	char ch;
	for (i = 0, ch = 'F'; i < row; i++, ch--)
	{
		for (j = 0, ch = 'F'; j <= i; j++, ch--)
		{
			printf("%c", ch);
		}
		printf("\n");
	}
	return 0;
}
