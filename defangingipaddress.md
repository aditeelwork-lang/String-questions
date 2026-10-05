#include <iostream>
using namespace std;

int main() 
{
    char arr[]={'1','.','1','.','1','.','1'};
    int n=sizeof(arr)/sizeof(arr[0]);
    int start=0;
    string ans;
    while(start<n){
        if(arr[start]=='.')
        ans=ans+"[.]";
        else
        ans=ans+arr[start];
        start++;
    }
    cout<<ans;
}
#output-1[.]1[.]1[.]1
