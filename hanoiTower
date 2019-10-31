#include <iostream>
using namespace std;

void hanoi(int,char,char,char);

int main()
{
    char x='1',y='2',z='3';
    hanoi(3,x,y,z);
}

void hanoi(int n, char x, char y, char z)
{
    if(n == 1)
        cout<<"diski "<<x<<" dan "<<z<<" ye koy.."<<endl;
    else{
        hanoi(n-1,x,z,y);
            hanoi(1,x,y,z);
                hanoi(n-1,y,x,z);
    }

}
