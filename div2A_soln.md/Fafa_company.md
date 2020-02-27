```cpp


#include <stdio.h>
#include<bits/stdc++.h>
using namespace std;

int main()
{
    int n,c=0;

    cin>>n;
       for (int i=1; i<=sqrt(n); i++)
    {
        if (n%i == 0)
        {

            c++;
        }
    }
cout<<c*2-1;
    return 0;
}
```
**
Solution by:
Sourajeet Mohanty
14:29 pm
27-02-2020
**
