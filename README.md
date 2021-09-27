# Exercise-3
# C++Basics
#include<iostream>
using namespace std;
int main()
{
	int purchased, sale;//declaring datatype integer
	int profit, loss;
	cout << "Enter the Purchased Price :" << endl; //the user will enter the purchased price
	cin >> purchased; //the input from user will be stored in variable 
	cout << "Enter the Sale Price : " << endl;
	cin >> sale;
	if (sale> purchased) //using else if statement
	{
		profit = sale - purchased; //formula to calculate profit
		cout << "Profit gained is : " << profit << endl;
	}
	else if (purchased > sale)
	{
		loss = purchased - sale;  //formula to calculate loss
		cout << "Loss is : " << loss << endl;
	}
	return 0;
}
