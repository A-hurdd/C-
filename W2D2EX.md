# Plan

## Input 
Sales

## Process
Devision sales = sales * .58 constant

## output 
Devision sales

// Abigail Hurd
// CS 1143 Day TR015
// Example in class 

#include using namespace std;
#include<iostream>
using namespace std;

int main()
{
	// Declare variables
	double sales;
	const double PERCENT_SALES =.58;
	double divisionsales; // Declare the variable divisionsales

	// Prompt user for input
	cout << "Enter Company sales amount: ";
	cin >> sales;

	divisionsales = sales * PERCENT_SALES; // Add missing semicolon

	cout << "Division Sales: $" << divisionsales << endl;
	
	return 0;
}
