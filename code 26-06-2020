#include<stdio.h>
#include<stdlib.h>
int min(int a, int b)
{
    if(a>b)
        return b;
    else
        return a;
}

// Function to find absolute sum
int abs_sum(int arr[], int n)
{

    int sum = 0;

    sum += abs(arr[0] - arr[1]);
    sum += abs(arr[n-1] - arr[n-2]);

    for (int i=1; i<n-1; i++)
        sum += min(abs(arr[i] - arr[i-1]), abs(arr[i] - arr[i+1]));  // Total sum of absolute difference

    return sum;
}

// Function to sort the elements

void sort(int a[], int n)
{
    for(int i = 0; i < n-1; i++)
    {
        for(int j = 0; j < n-i-1; j++)
        {
            if (a[j] > a[j+1])
            {
                int temp = a[j];
                a[j] = a[j+1];
                a[j+1] = temp;
            }}}}

int main()
{
    int a[20], n, i;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    printf("Enter the elements: ");
    for(i=0; i<n; i++)
    {
        scanf("%d", &a[i]);
    }
    sort(a, n);
    printf("The minimum sum of absolute is %d",abs_sum(a, n));
    return 0;
}
