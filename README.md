#include<iostream.h>
#include<conio.h>
#include<math.h>
void main()
{
    clrscr();
    int n; float s;
    cout<<"Enter the angle whose sine value you want to calculate:";
    cin>>n;
    s=sin(n);
    cout<<"The sine value of "<<n<<" is:"<<s;
    getch();
}
