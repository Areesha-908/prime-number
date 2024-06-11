# prime number
#include<iostream>
using namespace std;
int main()
{
cout<<"my roll number : 03048"<<endl;
int num;
cout<<"enter a number"<<endl;
cin>>num;
for(int i=2;i<num;i++)
{
if(num%i==0)
cout<<"not prime";
break;
}
cout<<"prime number";
return 0;
}
 
