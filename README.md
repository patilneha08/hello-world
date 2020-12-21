# hello-world
This is my trial code
#include<stdio.h>
void main()
{
  char user[20];
  printf("Hello");
  user=name();
  printf("Hello %s",user);
}
char name()
{
  char name[20];
  printf("\nEnter your name");
  gets(name);
  return name;
}
