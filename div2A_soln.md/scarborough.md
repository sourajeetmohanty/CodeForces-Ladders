```cpp

#include <iostream>
using namespace std;

int main()
{
    int m,n;
    cin>>n>>m;

    string s;
    cin>>s;
    while(m--)
    {
        int l,r;
        char c1,c2;
        cin>>l>>r>>c1>>c2;
        for(int i=l-1;i<=r-1;i++)
        {
            if(s[i]==c1)
            {
                s[i]=c2;
            }
        }

    }
    cout<<s;

    return 0;
}
```
*
solution by:
Sourajeet mohanty
12:12 pm
28-02-2020
*
