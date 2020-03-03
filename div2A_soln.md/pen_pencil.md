```cpp

#include <stdio.h>
#include<bits/stdc++.h>
using namespace std;

int main()
{
    int t;
    cin>>t;

    while(t--)
    {
        float a,b,c,d,k;

        cin>>a>>b>>c>>d>>k;
        int r1=ceil(float(a/c));
        int r2=ceil(float(b/d));
        if(r1+r2<=k)
        cout<<r1<<" "<<r2<<endl;
        else
        cout<<"-1";
    }

    return 0;
}

```

*
solution by:
Sourajeet mohanty
07:18 AM
03-03-2020
*
