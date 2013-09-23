x-y--
=====
#include <iostream>
using namespace std;
int mihanshu(int x,int y)
{
int a,b;
int r=1;
a=x;b=y;
    if(b==0)
       r=1;
	else{
	   r=a*mihanshu(x,y-1);
	
	   }
	return r;
}
int main(){
	int x, y;
	cout<<"输入x,y"<<endl;
	cin>>x>>y;
	cout<<"result is"<<mihanshu(x,y);

}
