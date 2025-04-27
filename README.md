#include <iostream>
using namespace std;
int msin()
{
	int r,c;
	cout<< "row";
	cin>> r;
	cout<<" column ";
	cin>> c;
	int a [r] [c],i,j;
	for (i=0;i<r;i++)
	{ for (j=0;j<c ; j++)
	{
		cout<<"a["<<i<<"]["<<j<<"]=";
		cin>>a[i][j];
	}
cout <<"\n";
}
for (i=0;i<r;i++)
	for (j=0;j<c ; j++)
	{
		cout<<a[i][j];
		cin>>a[i][j];
	}
cout <<"\n";
