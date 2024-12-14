# basedC

This ultra-compact syntax sacrifices readability for brevity, much like lambda calculus where you focus on the essence of computation with minimal structure. In real-world C, you'd never write code this way due to readability issues, but for learning core concepts in this style, it's an interesting exercise. Remember, actual C programming demands more structure and clarity for maintenance and teamwork.

Hello, World!
c

main(){puts("Hi!");}


Variables
c

int a=5;float b=3.14;


If Statement
c

a>0?puts("pos"):puts("neg");


For Loop
c

for(i=0;i<3;++i)puts("loop");


While Loop
c

while(a--)puts("count");


Array
c

int a[]={1,2,3};puts(a[0]+'0');


Function
c

f(a,b){return a+b;}puts(f(2,3));


Pointer
c

int a=5;int*p=&a;puts(*p+'0');


Memory Allocation
c

int*p=malloc(4);*p=10;free(p);

