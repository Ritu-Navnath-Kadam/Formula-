# Formula-
#include<stdio.h>
#include<math.h>

float formula(float ,float ,float );

float formula(float p,float r,float n)
{
float A,a;
a=pow((1+(r/100)),n);
A=p*a;
printf("Final answer = %f",A);

}
void main()
{
float p,r,n;
printf("Enter 'p'  value\t");
scanf("%f",&p);

printf("Enter 'r'  value\v");
scanf("%f",&r);

printf("Enter 'n'  value\t");
scanf("%f",&n);
formula(p,r,n);

}
