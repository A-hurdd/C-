// Abigail Hurd
// CS 1143 Day TR015
// Miles per Gallon

#include<iostream>
using namespace std;

int main()
{
	// Declare variables
	double miles = 0.0;
	double gallons = 0.0;
	double milesPerGallon = 0.0;

	cout << "Enter miles driven: ";
	cin >> miles;

	cout << "Enter gallons of gas used: ";
	cin >> gallons;

	milesPerGallon = miles / gallons;

	cout << "Miles per Gallon: " << milesPerGallon << endl;

	return 0;
}
