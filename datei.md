# Hier ist ein Beispiel von Markdown

**Fett**

*Italic*

1. Numberierung
2. Auch numerierung

```c#
using System;
namespace Rextester
{
  class Program
  {
    public static void Main(string[] args)
    {
      Console.WriteLine("Hey there, welcome to programming world!");
    }
  }
}
```

# Art

Art is a diverse range of human activities in creating visual, auditory or performing artifacts, expressing the author's imaginative, conceptual ideas, or technical skill, intended to be appreciated for their beauty or emotional power.


``````````````````````````````````````````````````
  +--------------+  +-----------------+
 / This is art  /---|It is appreciable|
+--------------+    +-----------------+

+-------------------------+   +------------------------+
|Let us start enjoying it.|---|because it is very funny|
+-------------------------+   +------------------------+
                                                 +
          +--------+      .-.       +------+     |\
  /\      |        |     (   )     / Trapez \    | \
 /  \     |        |      .-.     / Trapézio \   |  \
+----+    +--------+             +------------+  +---+
``````````````````````````````````````````````````

As we know music is also art, let me link here one of my favourite music.

We can also find random numbers using **C** swap numbers as shown below.

```c      Random.c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <time.h>

void swap(int* x, int* y)
{
  int temp = * x;
  * x = * y;
  * y = temp;
}
int main(void)
{
  int number, x=2, y= 3;
  srand(time(NULL));
  number = rand()%100+1;
  printf("The random number is %d\n",number);
  printf(" x = %i and y = %i\n",x,y);
  swap(&x,&y);
  printf(" x = %i and y = %i",x,y);
}
```
@Rextester.C_vc

**C**

```c        Character.c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <time.h>
void endJoke();
int main(void)
{
  printf("Welcome to my Program!\n");
  char a = 'a',m = 'M',c='c',h='h',e='e',l='l' ;
  printf("\nValue of %c is %d",m,m);
  printf("\nValue of %c is %d",a,a);
  printf("\nValue of %c is %d",c,c);
  printf("\nValue of %c is %d",h,h);
  printf("\nValue of %c is %d",e,e);
  printf("\nValue of %c is %d",l,l);

  char name[] = "Machel"; int i =0,j=0,k=0, sum=0;
  for(i=0;i<strlen(name);i++)
  {
    sum += name[i];
  }
  printf("\nSum of letters of %s is %i",name,sum);
  for(i=0;i<strlen(name);i++)
  {
    printf("\n%c",name[i]);
  }
  printf("\n");
  printf("Here is the table of 1x1:\n");
  printf("\n");
  for(j=1;j<=10;j++)
  {
    for(k=1;k<=10;k++)
    {
      printf("%4i",j*k);
    }
    printf("\n");
  }
  printf("\n");
  endJoke();
  return 0;
}
void endJoke()
{
  printf("Hello there, are you enjoying the programming?\n I find it really funny, when I understand a little bit what I am programming");
}

```
@Rextester.C_clang

