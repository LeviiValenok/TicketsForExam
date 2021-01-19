#include <stdio.h>
#include <stdarg.h>
enum type {Int, Float};
void SumOfIntegersAndFloats(int numberOfGroups, int numberOfElements, enum type type);
int main()
{
	SumOfIntegersAndFloats(2, 3, Int, 3, 5, 7, 3, Float, 2.0, .9, 1.1);
	printf("\n");
	return 0;
}

void SumOfIntegersAndFloats(int numberOfGroups, int numberOfElements, enum type type)
{
	int sumOfIntegers = 0;
	float sumOfFloats = 0;
	va_list pointer;
	va_start(pointer, type);
	while (numberOfGroups--)
	{
		if (type == Int)
		{
			while (numberOfElements--)
			{
				sumOfIntegers += va_arg(pointer, int);
			}
		}
		if (type == Float)
		{
			while (numberOfElements--)
			{
				sumOfFloats += va_arg(pointer, double);
			}
		}
		numberOfElements = va_arg(pointer, int);
		type = va_arg(pointer, enum type);
	}
	va_end(pointer);
	printf("Sum of integers is: %d. Sum of floats is: %lf", sumOfIntegers, sumOfFloats);
}
