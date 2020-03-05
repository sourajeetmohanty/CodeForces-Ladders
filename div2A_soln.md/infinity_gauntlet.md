```cpp
/******************************************************************************

                              Online C++ Compiler.
               Code, Compile, Run and Debug C++ program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <iostream>
#include<bits/stdc++.h>
using namespace std;

int
main ()
{
  map < string, string > mp;
  mp.insert (
	      {
	      "purple", "Power"});
  mp.insert (
	      {
	      "green", "Time"});
  mp.insert (
	      {
	      "blue", "Space"});
  mp.insert (
	      {
	      "orange", "Soul"});
  mp.insert (
	      {
	      "red", "Reality"});
  mp.insert (
	      {
	      "yellow", "Mind"});
  int n;
  cin >> n;
  map < string, string >::iterator itr;
  int m=n;
  while (n--)
    {
      map < string, string >::iterator itr;
      string s;
      cin >> s;
      //for (itr = mp.begin (); itr != mp.end (); ++itr)
//	{

	 // std::map < string, string >::iterator
	  itr = mp.find (s);
	  if (itr != mp.end ())
	    (*itr).second =" ";
	  //if (itr->second == s)
	    //itr->first = " ";
//	}
    }
  cout << 6 - m << endl;
  for (itr = mp.begin (); itr != mp.end (); ++itr)
    {
      if (itr->first != " ")
	cout << itr->second << endl;
    }
  return 0;
}
```
*solution by:
Sourajeet Mohanty
22:46pm
05-03-2020
*
