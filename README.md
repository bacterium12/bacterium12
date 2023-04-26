#include<iostream>
#include<string>
#include<cstring>
using namespace std;

struct student	
{
	int num;
	string name;
	double math,Chinese,English; 
};
int main()
{
	struct student a[100];
	int n;
	cin>>n;
	for(int i=0;i<n;i++)
	{
		cin>>a[i].num>>a[i].name>>a[i].math>>a[i].Chinese>>a[i].English;
	}
	for(int i=0;i<n;i++)
	{
		cout<<a[i].num<<" "<<a[i].name<<" "<<a[i].math<<" "<<a[i].Chinese<<" "<<a[i].English;
    }
	return 0;
}
			
			
			
			
