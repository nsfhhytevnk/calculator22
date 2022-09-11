# calculator22
#include <iostream>


using namespace std;

int main()
{
    int num1, num2;
    char m;
    std::cout << "Enter the first number: ";
    cin>>num1;
    cout << "Enter the secound number: ";
    cin >> num2;
    cout<< "Enter the sign of operation";
    cin>> m;
    if (m=='+')
{
    cout<< "th resu1t is";
    cout<<num1 + num2;
}
if(m =='-')
{
    cout<< "th resu1t is";
    cout<<num1 - num2;
}
if(m =='*')
{
    cout<< "th resu1t is";
    cout<<num1 * num2;
}
if(m =='/')
{
    cout<< "th resu1t is";
    cout<<num1 / num2;

}


}
