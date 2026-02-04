#include<stdio.h>

int isPrime(int n)
{
  for(int i=2;i<n;i++)
  {
    if(n%i==0)
      return 0;
  }
  return 1;
}

int main()
{
  int n;
  int i,j,k;
  printf("Enter a digit:\n");
  scanf("%d",&n);
  if(n==0 || n==1)
    printf("%d/n",n);
  else
  {
    for(i=2;i<=n;i++)
    {
      if(isPrime(i))
        printf("<%d>",i);
      
    }
  }
}
