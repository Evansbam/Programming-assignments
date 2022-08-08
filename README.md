# Programming-assignments

#include <iostream>

using namespace std;
int main()
{
int s=0, c=0, i;
float av;
for(i=2; i<=10000; i++){
if(i%2==0) {s=s+i; c++}
}
av = s/c;
cout << av;
return 0;
}
