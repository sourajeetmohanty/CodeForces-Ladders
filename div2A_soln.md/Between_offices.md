```cpp


#include <stdio.h>
#include<bits/stdc++.h>
using namespace std;

int main()
{   
    int n,s1=0,f1=0;
    cin>>n;
    string s;
    cin>>s;
    for(int i=1;i<s.length();i++)
    {
        if(s[i]=='S' && s[i-1]!='S')
        s1++;
        if(s[i]=='F' && s[i-1]!='F')
        f1++;
    }
    if(f1>s1)
    cout<<"YES";
    else
    cout<<"NO";
    return 0;
}
```

**Solution by:
Sourajeet mohanty
08:37 AM
27-02-2020**
