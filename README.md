# ARRAY-LINEAR-SEARCH



#include<iostream>
#include<conio.h>
using namespace std;
class A
{
    public:
    void func()
    {
        int pos,i,ele;
        
        int arr[7]={5,4,3,2,1};
        int size=sizeof(arr)/sizeof(arr[0]);
        cout<<"the elements of the array are "<<endl;
        for(i=0;i<5;i++)
        cout<<arr[i]<<endl;
        cout<<"enter the element to search"<<endl;
        cin>>ele;
        for(i=0;i<size;i++)
        if(arr[i]==ele)
        {
            cout<<"element found at position"<<i+1<<endl;
        }
    }
};
int main()
{
    A obj;
    obj.func();
    return 0;
}
