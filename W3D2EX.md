# Example code

Input : Month 1, Month 2, Month 3. Rain 1, Rain 2, Rain 3.

Process : Average = (Rain 1 + Rain 2 + Rain 3)/3

Output : The average rainfall for _, _, and _ is _ Inches.

## Code I came up with

//Abigial Hurd 
//CS 1143 Day TR015 
//Rainfall

#include <iostream>
#include <iomanip>
#include <string>
using namespace std;

int main()
{
    // Declare variables
    string month1, month2, month3;
    double rain1, rain2, rain3;

    // Input
    cout << "Enter the first month: ";
    cin >> month1;
    cout << "Enter the rainfall for " << month1 << ": ";
    cin >> rain1;

    cout << "Enter the second month: ";
    cin >> month2;

    cout << "Enter the rainfall for " << month2 << ": ";
    cin >> rain2;

    cout << "Enter the third month: ";
    cin >> month3;
    cout << "Enter the rainfall for " << month3 << ": ";
    cin >> rain3;

	// Processing

    double average = (rain1 + rain2 + rain3) / 3;

	// Output

    cout << fixed << setprecision(2);
    cout << "The average rainfall for " << month1 << ", " << month2;
    cout <<", and " << month3 << " is " << setw(6) <<average << " inches." << endl;

    return 0;
}
