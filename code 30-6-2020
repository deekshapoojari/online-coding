#include<stdio.h>
int main()
{
    int year, month;
    printf("Enter the month number and year: ");
    scanf("%d %d",&month,&year);
    if(month == 1 || month == 3 || month == 5 || month == 7 || month == 8 || month == 10 || month == 12)
        printf("Number of days is 31\n");
    else if((month == 2) && ((year%400==0) || (year%4==0 && year%100!=0)))
    {
        printf("Number of days is 29\n");
    }
    else if(month == 2)
    {
        printf("Number of days is 28\n");
    }
    else
        printf("Number of days is 30\n");
    return 0;
}
