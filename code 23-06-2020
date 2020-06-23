#include<stdio.h>
int stack[100], temps[100], temp, choice, n, top, ttop, x, i;
void push(int x)
{
    top++;
    stack[top]=x;
}
void pop()
{
    temp = stack[top];
    top--;
}
void display()
{
    if(ttop>=0)
    {
        printf("\n The sorted elements in STACK \n");
        for(i=ttop; i>=0; i--)
            printf("\n%d",temps[i]);
    }
    else
    {
        printf("\n The STACK is empty");
    }

}
int main()
{
    top=-1;
    ttop = -1;
    printf("\n Enter the size of STACK[MAX=100]:");
    scanf("%d",&n);
    printf("Enter the elements in the stack:\n");
    for(i=0; i<n; i++)
    {
        printf(" Enter a value to be pushed:");
        scanf("%d",&x);
        push(x);
    }

    while(top != -1)
    {
        pop();
        while(ttop != -1 && temps[ttop] > temp)
        {
            push(temps[ttop]);
            ttop--;
        }
        ttop++;
        temps[ttop] = temp;
    }
    display();
}
