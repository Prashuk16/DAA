#include<bits/stdc++.h>
#include <iostream>
using namespace std;
int main()
{
    int i,j,n,t,k,m;
    cout<<"Enter no of test cases: ";
    cin>>t;
    for(k=0;k<t;k++)
    {
        cout<<"Enter total no. of elements in array1: ";
        cin>>m;
        int a1[m];
        cout<<"Enter elements in 1st array:"<<endl;
        for(i=0;i<m;i++)
        {
            cin>>a1[i];
        }
        cout<<"Enter total no. of elements in array2: ";
        cin>>n;
        int a2[n];
        cout<<"Enter elements in 2st array:"<<endl;
        for(i=0;i<n;i++)
        {
            cin>>a2[i];
        }
        sort(a1,a1+m);
        sort(a2,a2+n);
        vector<int>f;
        j=0;
        i=0;
        int count=0;
        while(i<m&&j<n)
        {
            if(a1[i]<a2[j])
            i++;
            else if(a1[i]>a2[j])
            j++;
            else
            {
               f.push_back(a1[i]);
               i++;
               j++;
            }
        }
        int l=f.size();
        for(i=0;i<l;i++)
        cout<<f[i]<<" ";
        cout<<endl;
    }
    return 0;
}
