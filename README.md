# C_190703
C_Languase_Class


#include <stdio.h>

int main()
{
	double i, s = 0.0; //float는 소수점이라서 초기값이 0 이 아닌 0.0 을 주어야 한다.
	int c = 0; //초기값

	for (i = 1.0; i < 10.0; i = i + 1.0)
	{
		c = c + 1;
		if (c % 2)
			s -= i / (i + 1.0);
		else
			s += i / (i + 1.0);
	}
	printf("%f", s);
}
