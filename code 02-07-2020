#include<stdio.h>
int iterativeBsearch(int A[], int size, int element);
int main() {
   int A[] = {0,12,6,12,12,18,34,45,55,99};
   int n=55;
   printf("%d is found at Index %d \n",n,iterativeBsearch(A,10,n));
   return 0;
}
int iterativeBsearch(int A[], int size, int element) {
   int start = 0;
   int end = size-1;
   while(start<=end) {
      int mid = (start+end)/2;
      if( A[mid] == element) {
         return mid;
      } else if( element < A[mid] ) {
         end = mid-1;
      } else {
         start = mid+1;
      }
   }
   return -1;
}
