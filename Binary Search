#include <bits/stdc++.h>
using namespace std;
int main()
{
    int array_size;
    cout<<"Enter the size of array:"<<endl;
    cin>>array_size;
    int arr[array_size];
    int low=0, high=array_size-1, middle, key;
    cout<<"Enter elements in sorted order in the array:"<<endl;
    for(int i=0;i<array_size;i++)
    {
        cin>>arr[i];
    }
    cout<<"Enter the element you want to search:"<<endl;
    cin>>key;
    while(low<=high)
    {
        middle=(low+high)/2;
        if(key==arr[middle]) {cout<<"Found "; return 0;}
        if(key>arr[middle]) low=middle+1;
        else high=middle-1;
    }
    cout<<"Not found";

    return 0;
}
