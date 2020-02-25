

```cpp
#include <iostream>

using namespace std;

int main()
{
    int n1;
    string s;
    cin>>n1;
    cin>>s;
    
    int o,n,e,z,r;
    
    for(int i=0;i<n1;i++)
    {
        if(s[i]=='o')
        o++;
        else if(s[i]=='n')
        n++;
        else if(s[i]=='e')
        e++;
        else if(s[i]=='z')
        z++;
        else if(s[i]=='r')
        r++;
        
    }
    
    if(n>=1)
    {
        while(n>0 && o>=0 && e>=0 )
        {
        n--;
        o--;
        e--;
        
        if(n>=0 && o>=0 && e>=0 )
        cout<<"1"<<" ";
    }
    }
    
    if(z>=1)
    {
        while(z>0 && e>=0 && r>=0 && o>=0 )
        {
        z--;
        e--;
        r--;
        o--;
        
    if(z>=0 && e>=0 && r>=0 && o>=0 )
    cout<<"0"<<" ";
        }        
    }

    return 0;
}
```

**solution by:
Sourajeet Moahanty
15:30 pm
25-02-2020
**

