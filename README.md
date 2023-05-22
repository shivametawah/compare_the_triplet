#include <bits/stdc++.h>

using namespace std;

string ltrim(const string &);
string rtrim(const string &);
vector<string> split(const string &);
int main()
{
  int a[3],b[3],alice=0,bob=0,i;
  scanf("%d%d%d%d%d%d",&a[0],&a[1],&a[2],&b[0],&b[1],&b[2]);
for(i=0;i<3;i++)
{
    if(a[i]>b[i])
    alice++;
    if(a[i]<b[i])
    bob++;
}
printf("%d %d",alice,bob);
return 0;
}

