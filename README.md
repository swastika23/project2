<!-- # project2 -->
#include<iostream>
using namespace std;
int main()
{
    /*           * 
               * * *
             * * * * *
           * * * * * * *
         * * * * * * * * *     */
    int n,rang1,rang2;
    cin>>n;
    rang1=n/2;
    rang2=n/2;
    for(int i=0;i<n;i++)
    {
        for(int k=0;k<=rang1+2;k++)
        {
            cout<<"  ";
        }
        for(int j=rang1;j<=rang2;j++)
        {
            cout<<"* ";
        }
        cout<<endl;
        rang1--;
        rang2++;
    }
} 
