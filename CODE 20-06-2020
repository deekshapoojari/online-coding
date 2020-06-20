#include <stdio.h>
void rightRotate(int A[], int k, int n)
{
	int aux[k];
	for (int i = 0; i < k; i++)
		aux[i] = A[n-k+i];
	for (int i = n-k-1; i >= 0; i--)
		A[i+k] = A[i];
	for (int i = 0; i < k; i++)
		A[i] = aux[i];
	for (int i = 0; i < n; i++)
		printf("%d ", A[i]);
	printf("\n");
}
void main()
{
	int A[50],k,n;
	printf("Enter the size of array :\n");
	scanf("%d",&n);
	printf("Enter the array :\n");
	for(int i=0;i<n;i++)
		scanf("%d",&A[i]);
	printf("Enter number of rotation :\n");
	scanf("%d",&k);
	rightRotate(A, k, n);
}
