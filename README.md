#include<stdio.h>

int main()
{
  int x=17;
  int *ptr=NULL;
  ptr = &x;
  printf("%d",*ptr);
}
