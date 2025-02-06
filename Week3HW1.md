# Premise

Write a program that converts Fahrenheit temperatures to Celsius temperatures.  The formula is

Celsius = 5/9 x (Fahrenheit – 32)

Beware, it's easier than you think to get this one wrong!  Check with 212.

The output should look like:

     xxx.xx Fahrenheit = xxx.xx Celsius

which means you need to use formatting to the get the output to look like that


//Abigial Hurd
//CS 1143 Day TR015
// Fahrenheit to Celsius

#include <iostream>
#include <iomanip>
using namespace std;

int main() {

    // Declare Variables 
    double fahrenheit = 0.0, celsius;

    cout << "Enter the temperature in Fahrenheit: ";
    cin >> fahrenheit;
    
    celsius = 5.0 / 9.0 * (fahrenheit - 32);

    cout << fixed << setprecision(2);
    cout << fahrenheit << " Fahrenheit = " << celsius << " Celsius" << endl;

    return 0;
