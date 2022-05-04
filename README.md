#include<stdio.h>

#include<conio.h>

void div();

void add();

void mul();

void sub();

void main()

{

int z;

int i;

clrscr();

printf("For addition enter '1'\nfor subtraction enter '2'\nfor multiplication enter '3'\nfor division enter '4'\n");

scanf("%d",&z);

switch (z)

{

 case 1:

add();

break;

case 2:

sub();

break;

case 3:

mul();

break;

case 4:

div();

break;

default:

printf("invalid");

}

printf("\n\nfor exil enter '1'\n if not then enter '0'\n");

scanf("%d",&i);

while(i==1)

{

printf("\n\nFor addition enter '1'\nfor subtraction enter '2'\nfor multiplication enter '3'\nfor division enter '4'\n");

scanf("%d",&z);

switch (z)

{

 case 1:

add();

break;

case 2:

sub();

break;

case 3:

mul();

break;

case 4:

div();

break;

default:

printf("invalid");

}

printf("\n\nfor exil enter '1'\n if not then enter '0'\n");

scanf("%d",&i);

}

    

    getch();

}

void div()

{

    int a,b;

    float c;

    printf("enter bigger number: ");

    scanf("%d",&a);

    printf("enter smaller number: ");

    scanf("%d", &b);

        c=a/b;

    printf("%f",c);

}

void add()

{

int e, f, g;

printf("enter first number: ");

scanf("%d", &e);

printf("enter second number: ");

scanf("%d", &f);

g=e+f;

printf("%d", g);

}

void sub()

{

int e, f, g;

printf("enter bigger number: ");

scanf("%d", &e);

printf("enter smaller number: ");

scanf("%d", &f);

g=e-f;

printf("%d", g);

}

void mul()

{

int e, f, g;

printf("enter first number: ");

scanf("%d", &e);

printf("enter second number: ");

scanf("%d", &f);

g=e*f;

printf("%d", g);

}
