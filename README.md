# c-program-if-else-
#include<stdio.h>
void main ()
{ printf("the size of int is %d \n",sizeof(int));
  printf("the size of short int is %hd \n",sizeof(short int));
  printf("the size of unsigned short int is %hu \n",sizeof(unsigned short int));
  printf("the size of unsigned int is %u \n",sizeof(unsigned int );
  printf("the size of long int is %ld \n",sizeof(long int));
  printf("the size of unsigned long int is %lu \n ",sizeof(unsigned long int));
  printf("the size of long long int is %lld \n",sizeof(long long int));
  printf("the size of unsigned long long int %llu \n",size of(unsigned long long int));
  printf("the size of signed char %c \n",sizeof(signed char));
  printf("the size of unsigned char % \n",sizeof(unsigned char));
  printf("the size of float %f \n",sizeof(float));
  printf("the size of double %lf \n",sizeof(double));
  printf("the size of long double %l_f \n",sizeof(long double));

}

#include<stdio.h>
void main()
{ /* get number input from the user and print if it is odd print weird */
 int(i);
 printf("give any no.");
 scanf("%d",&i);
 if(i/2==0)
 {
     printf("the no is even %d ",i);
 }
 else
 {
     printf("weird");
 }
 
}

#include<stdio.h>
void main()
{ /* get number input from the user and print
 1.if n is odd  print weird
 2.if n is even and range b/w 2 to 5 print not weird
 3.if n is even and range b/w 6 to 20 print weird
 4.if n is greater than 20 print not weird */
 int(i);
 printf("give any no.");
 scanf("%d",&i);
 if((i/2==0) && (i<=5 && i>=2))
 {
     printf("not weird");
 }
 if else((i/2==0) && (i<=20 && i>==6))
 {
     printf("weird");
 }
 if else(i>20)
 {
     printf("not weird");
 }
 else
 {
     printf("weird");
 }
 
}


/* find the max no b/w two no */
#include<stdio.h>
void main ()
{
int(a);
int(b);
printf("enter a no. ");
scanf("%d",&a);
printf("enter 2 no. ");
scanf("%d",&b);
if(a>b)
{ printf("the no is greater %d ", a);
}
else
{ printf("the no is greater %d ", b);
}
}

/* to fint the max b/w three no. */
#include<stdio.h>
void main ()
{
int(a);
int(b);
int(c);
printf("enter a no. ");
scanf("%d",&a);
printf("enter 2 no. ");
scanf("%d",&b);
printf("enter 3 no. ");
scanf("%d",&c);
if(a>b && b>c)
{ printf("the no is greater %d ", a);
}
else if(b>a && a>c)
{ printf(" the no is greater %d ",b);
else
{ printf("the no is greater %d ", c);
}
}

/* to check whether a no is - , + or 0 */
#include<stdio.h>
void main ()
{
int(a);
printf("give a no. ");
scanf("%d",&a);
if(a==0)
{printf(" the no is = to 0");
}
else if(a>0)
{printf("the no is +");
}
else
{printf("the no is -");
}
}

/* to check whether a no is / by 5 and 11 */
#include<stdio.h>
void main ()
{
int(a);
printf("enter a no ");
scanf("%d",&a);
if(a%5==0 && a%11==0)
{
printf("the no is / by 5 and 11");
}
else
{printf("the no is no / by 5 and 11 ");
}
}

/* to check whether a no is odd or even */
#include<stdio.h>
void main ()
{
int(a);
printf("enter a no.");
scanf("%d",&a);
if(a%2==0)
{
printf("the no is even ");
}
else
{
printf("the no is odd");
}
}
 
/*the check a year is leap year or not */
#include<stdio.h>
void main ()
{
int(a);
printf("enter a year ");
scanf("%d",&a);
if(a%4==0)
{printf("the year is leap year");
}
else
{printf("the year is not leap year");
}
}

/* TO CHECK WHEATHER CHAR IS ALPABET OR NO*/
#include <stdio.h>

void main()
{
char x;
printf(" Please Enter any character \n");
scanf("%c", &x);
if( (x>='a' && x<='z') || (x>='A' && x<='Z'))
{
printf("\n %c is an Alphabet", x);
}  
else
{
printf("\n %c is not an Alphabet", x);
}  
}

/* TO CHECK A CHAR IS IN UPPER CASE OR IN LOWER CASE */
#include <stdio.h>

void main()
{
char x;
printf(" Please Enter any character \n");
scanf("%c", &x);
if(x >='a' && x<='z')
{
printf("the char is in lower case");
}  
else if(x>='A' && x<='Z')
{
printf("the char is in upper case ");
}
else
{printf("the it is not a char");
}
}

/* TO CHECK A CHAR IS vowal or consonant */
#include <stdio.h>

void main()
{
char a;
printf(" Please Enter any character \n");
scanf("%c", &a);
switch(a)
{case 'a' :
{printf("the char is vowel");
}
break;
case 'e' :
{printf("the char is vowel");
}
break;
case 'i' :
{printf("the char is vowel");
}
break;
case 'o':
{printf("the char is vowel");
}
break;
case 'u':
{printf("the char is vowel");
}
break;
default :
{printf("the char is consonant");
}
}
}

/* to check wheather a char is alphabet or a digit or a special char*/
#include <stdio.h>

void main()
{
char a;
printf("Enter any character: ");
scanf("%c", &a);
if((a>='a' && a<='z') || (a>='A' && a<='Z'))
{
printf("alphabet.");
}
else if(a>='0' && a<='9')
{
printf(" digit.");
}
else
{
printf(" special character.");
}
}

/*c program to check input week number and print week day*/
#include <stdio.h>
void main()
{
int a;
printf(" Please Enter any character \n");
scanf("%d", &a);
switch(a)
{case 1 :
{printf("monday");
}
break;
case 2 :
{printf("tuesday");
}
break;
case 3 :
{printf("wednesday");
}
break;
case 4:
{printf("thursday");
}
break;
case 5:
{printf("friday");
}
break;
case 6:
{printf("saturday");
}
case 7:
{printf("sunday");
}
default :
{printf("wrong input");
}
}
}

/*c program to check input month number and print month day*/
#include <stdio.h>
void main()
{
int a;
printf(" Please Enter any character \n");
scanf("%d", &a);
switch(a)
{case 1 :
{printf("january");
}
break;
case 2 :
{printf("february");
}
break;
case 3 :
{printf("march");
}
break;
case 4:
{printf("april");
}
break;
case 5:
{printf("may");
}
break;
case 6:
{printf("june");
}
case 7:
{printf("july");
}
case 8:
{printf("august");
}
case 9:
{printf("september");
}
case 10:
{printf("october");
}
case 11:
{printf("november");
}
case 12:
{printf("december");
}
default :
{printf("wrong input");
}
}
}

/*c program to count total number of notes in given amount*/
#include <stdio.h>

void main()
{
int a;
int b, c, d, e, f, g, h, i;
b = c = d = e = f = g = h = i = 0;
printf("Enter amount: ");
scanf("%d", &a);
printf("Total number of notes = \n");
if(a >= 500)
{
b = a/500;
a -= b * 500;
printf("500 = %d\n", b);
}
if(a >= 100)
{
c = a/100;
a -= c * 100;
printf("100 = %d\n", c);
}
if(a >= 50)
{
d = a/50;
a -= d * 50;
printf("50 = %d\n", d);
}
if(a >= 20)
{
e = a/20;
a -= e * 20;
printf("20 = %d\n", e);
}
if(a >= 10)
{
f = a/10;
a -= f * 10;
printf("10 = %d\n", f);
}
if(a >= 5)
{
g = a/5;
a -= g * 5;
printf("5 = %d\n", g);
}
if(a >= 2)
{
h = a /2;
a -= h * 2;
printf("2 = %d\n", h);
}
if(a >= 1)
{
i = a;
printf("1 = %d\n", i);
}
}

/*c program to check input month number and print no of day*/
#include <stdio.h>
void main()
{
int a;
printf(" Please Enter any character \n");
scanf("%d", &a);
switch(a)
{case 1 :
{printf("31");
}
break;
case 2 :
{printf("28,29");
}
break;
case 3 :
{printf("31");
}
break;
case 4:
{printf("30");
}
break;
case 5:
{printf("31");
}
break;
case 6:
{printf("30");
}
case 7:
{printf("31");
}
case 8:
{printf("31");
}
case 9:
{printf("30");
}
case 10:
{printf("31");
}
case 11:
{printf("30");
}
case 12:
{printf("31");
}
default :
{printf("wrong input");
}
}
}

/* to check a angle is correct or wrong*/
#include<stdio.h>
void main()
{int (a);
int(b);
int(c);
printf("\nEnter 3 angles of the triangle :");
scanf("%d %d %d",&a,&b,&c);
if ((a+b+c)==180 )
{ printf("\nTriangle is valid"); }
else
{ printf("\nTriangle is not valid");}
}

/*to check the side of triangles is correct or not*/
#include<stdio.h>
void main()
{ int a,b,c;
printf("\nEnter 3 side of the triangle :");
scanf("%d %d %d",&a,&b,&c);
if ( (a+b>c) && (a+c>b) && (c+b>a) )
{ printf("\nTriangle is valid"); }
else
{ printf("\nTriangle is not valid"); }
}

/*to check the type of triangle*/
#include<stdio.h>
void main()
{ int a,b,c,a1,b1,c1;
printf("\nEnter 3 side of the triangle :");
scanf("%d %d %d",&a,&b,&c);
if ( (a+b>c) && (a+c>b) && (c+b>a) )
{ if(a==b && b==c && a==c)
{ printf("\nTringle formed is an Equilateral triangle"); }
else if(a==b && b!=c)
{ printf("\nTrinangle in Isoceles triangle"); }
else if(a!=b && b!=c && a!=c)
{ printf("\n Triangle is Scalene triangle."); }
else
{ printf("\nTriangle is not valid"); }
}

/*to get find all root of quar. Equ.*/
#include<stdio.h>
void main()
{ int a,b,c;
printf("\nEnter coefficient of X^2 :");
scanf("%d",&a);
printf("\nEnter coefficient of X :");
scanf("%d",&b);
printf("\nEnter the constant :");
scanf("%d",&c);
printf("\n1st root is :%f",(-b+sqrt((b*b)-(4*a*c)))/2*a);
printf("\n2nd root is :%f",(-b-sqrt((b*b)-(4*a*c)))/2*a);
}


/*to calculate profit or loss*/
#include<stdio.h>
void main()
{
float i,f,p,l;
printf("Enter the initial capital:");
scanf("%f",&i);
printf("\n Enter the final capital:");
scanf("%f",&f);
if(i<f)
{printf("\n Profit:");
p=(f-i);
printf("%f",p);
}
else if(i==f)
{printf("\n No Profit,No Loss.");
}
else
{printf("\n Loss:");
l=(i-f);
printf("%f",l);
}
}


/*to input marks of 5 subject */
#include<stdio.h>
void main()
{
float p,c,m,b,comp,per;
char grade;
printf("Enter marks of different subjects(out of 100):\n Physics:");
scanf("%f",&p);
printf("\n Chemistry:");
scanf("%f",&c);
printf("\n Maths:");
scanf("%f",&m);
printf("\n Biology:");
scanf("%f",&b);
printf("\n Computer:");
fflush(stdin);
scanf("%f",&comp);
per=(p+c+m+b+comp)/5;
if(per>=90)
{
grade='A';
printf("\n Grade: %c",grade);
}
else if(per>=80 && per<90)
{
grade='B';
printf("\n Grade: %c",grade);
}
else if(per>=70 && per<80)
{
grade='C';
printf("\n Grade: %c",grade);
}
else if(per>=60 && per<70)
{
grade='D';
printf("\n Grade: %c",grade);
}
else if(per>=40 && per<60)
{
grade='E';
printf("\n Grade: %c",grade);
}
else
{
grade='F';
printf("\n Grade: %c",grade);
}
}

/*taking input and calculate thegross salary according to data given*/
#include<stdio.h>
void main()
{
int bs,hra,da,gs;
printf("\n Enter the basic salary of the Employee:");
scanf(("%u",&bs));
if(bs<=10000)
{
hra=(0.2*bs);
da=(0.8*bs);
}
else if(bs>=10000 && bs<=20000)
{
hra=(0.25*bs);
da=(0.9*bs);
}
else
{
hra=(0.3*bs);
da=(0.95*bs);
}
gs=(bs+hra+da);
printf("\n The grioss Salary of the employee is: %u",gs);
}

/* to input electricity unit changeand calculate total bill acc. to given info */
#include<stdio.h>
void main()
{
int a,amt;
printf("\n Enter no. of Electricity Units consumed:");
scanf("%d",&a);
if(a<=50)
amt=(a*0.5);
else if(a>50 && a<=150)
amt=(a*0.75);
else if(a>50 && a<=250)
amt=(a*1.2);
else
amt=(a*1.5);
amt=(amt*0.2);
printf("\n The total Electricity Bill is: %d",amt);
}
