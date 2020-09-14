# A---Buying-Torches
#include <bits/stdc++.h>
using namespace std;
#define ll long long
#define ld long double
int main() {

   int t;
   cin>>t;
   while(t--){
        ll x,y,k;
        cin>>x>>y>>k;
        ld n=(ld)(k*(y+1)-1)/(x-1);
        ll m=(k*(y+1)-1)/(x-1);
        if(m<n){
           m++;
        }
        cout<<m+k<<endl;
   }

}


