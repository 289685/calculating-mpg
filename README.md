#include <iostream>

using namespace std;

int main ()
{
    double md, gu;
// this will take in information for how many miles driven
    cout << "enter miles driven ";
    cin >> md;
// this will take in information for how many gallons used
    cout << "enter gallons used ";
    cin >> gu;
// this will calculate the mpg
    double mpg = md / gu;
    cout << "your car gets " << mpg << "miles per gallon";

    return 0;
}
