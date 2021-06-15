# c-2
developed by devil
#include<iostream>
#include<string>
using namespace std;
int main() 
{
int age;
cout<<" Enter your age:";
cin>>age;
if (age >=18) 
{
cout <<" you are eligible for voting";
}
else
{ 
cout<<" you are not eligible for voting";
cout<<"wait for "<<18-age<<" Year(s): ";
}
getch() ;
}
