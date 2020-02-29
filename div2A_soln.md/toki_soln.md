```
#include <iostream>

using namespace std;

int main()
{
    int n,a;
    cin>>n;
    int k=n%4;
    if(k==1)
    {
     a=1;
     cout<<a<<" "<<"A";
    }
   else if(k==3)
    {
        a=2;
        cout<<a<<" "<<"A";
    }
    else if(k==2)
    {
        a=1;
        cout<<a<<" "<<"B";
    }
    else if(k==0)
    {
        a=1;
        cout<<a<<" "<<"A";
    }

    return 0;
}
```
*
solution by:
Sourajeet mohanty
10:09 pm
29-02-2020
*
