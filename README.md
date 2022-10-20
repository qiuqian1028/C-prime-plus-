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
