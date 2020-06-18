#include<stdio.h>

int nthMagicNo(int n)
{
    int pow = 1, answer = 0;
    while (n)
    {
       pow = pow*5;
       if (n & 1)
         answer += pow;
       n >>= 1;
    }
    return answer;
}

void main()
{
    int n, i;
    printf("Enter the value of N: ");
    scanf("%d", &n);
    for(i = 1; i <= n; i++)
    {
        printf("%d ", nthMagicNo(i));
    }
    printf("\n");
}
