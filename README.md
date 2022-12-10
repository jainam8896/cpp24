# cpp24#include<iostream.h>

#include<conio.h>

class x

{

	public:

		int p1;

		x(int a)

		{

			p1=a;

		}

		void f()

		{

			cout<<p1;

		}

};

void main()

{

	clrscr();

	x ob1(10),*ob2;

	ob2=&ob1;

	ob2->f();

	getch();

}
