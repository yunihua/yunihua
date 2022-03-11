- 👋 Hi, I’m @yunihua
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>

#include <stdlib.h>
#include <time.h>

int main()
{
	int a,i,sum;
	sum = 6;
	srand((unsigned)time(NULL));
	a = rand()%100;
	
	while (1)
	{
		sum--;
		scanf("%d", &i);
		if (a < i)
			printf("你的很大，我要忍一下%d\n", sum);
		if (a > i)
			printf("谷树皮，三寸丁，夜夜空对，妄自结愁肠%d\n", sum);
		if (a == i)
		{
			printf("吾王剑之所指，吾等心之所向");
				break;
		}
		if (sum == 0) 
		{
			printf("今夜受益良多，下次见%d",a);
			break;
		}
	}
	return 0;
}
<!---
yunihua/yunihua is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
