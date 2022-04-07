# Codeforcescpp-279A
#include <bits/stdc++.h>
using namespace std;
 
int main() {
	int x,y;
  cin >> x >> y;
  if(y>0 && x+y>=0 && x-y<=-1)
    cout << 4*y-2;
  else if(x<0 && x+y<=0 && x-y<=0)
    cout << 4*(-x)-1;
  else if(y<0 && x+y<=1 && x-y>=1)
    cout << 4*(-y);
  else if(x>0 && x+y>=2 && x-y>=0)
    cout << 4*x-3;
  else
    cout << 0;
  
	return 0;
}
