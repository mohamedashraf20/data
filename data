#include <iostream>
#define size 10
using namespace std;
class stack{
private:
    int top;
    int arr[size];
public:
    stack(){
    top=-1;
    }
    void push(int x)
    {
    if(top<=size-1){
top++;
    arr[top]=x;
    }
    else{
     cout<<" over flow \n";
    }
    }
    void pop(){
        if(top==-1 )
    {
        cout<<" is empty" ;
    }
    else
    {
     top--;
    }
    }
    bool Isempty()
    {
    return(top==-1);
    }
 bool Isfull()
    {
    return(top==size-1);
    }
    void print()
    {
    for( int i=0; i<=top; i++)
    {
    cout<<arr[i]<<endl;
    }
    }

};




int main()
{
 stack e;
e.push(2);
 e.push(9);
 e.push(8);
 e.push(88);
 e.push(22);
 e.pop();
 cout<<e.Isempty();
e.print();
