![](Codigo23.png)
#include <iostream>

using namespace std;

int main()
{
    int total=0;
    int i=0;
    int num[10];
    for (i=1;i<=10;i++)
{
    cout <<"Introduce el numero";
    cin >> num[i];
    if(num [i]%2==0)
    {total=total+ num[i];}
}
cout<< total;

    return 0;
}
