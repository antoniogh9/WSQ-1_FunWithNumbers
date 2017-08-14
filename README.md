# WSQ-1_FunWithNumbers
/*
FunWithNumbers.cpp
Aug 13, 2017
Dulca
*/
#include <iostream>
using namespace std;
int main()
{
	int First, Second, Sum, Diff, Product, Div, Remainder ;

	//User Input
	cout << "Enter your first number:" << endl ;
	cin >> First ;
	cout << "Enter your second number:" << endl ;
	cin >> Second ;

	//Formulas
	Sum = First + Second ;
	Diff = First - Second ;
	Product = First * Second ;
	Div = First / Second ;
	Remainder = First % Second ;

	//Verification
	cout << endl ;
	cout << "You chose the numbers " << First << " and " << Second << "." << endl ;
	cout << endl ;

	//Results
	cout << "The addition of those numbers is " << Sum << "." << endl ;
	cout << "The difference of those numbers is " << Diff << "." << endl ;
	cout << "The product of those numbers is " << Product << "." << endl ;
	cout << "The division of those numbers is " << Div << "." << endl ;
	cout << "The remainder of those numbers is " << Remainder << "." << endl ;

return 0;
}
