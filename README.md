CDS Experiment -01
Aim: To install VS CODE and print "HELLO WORLD" including sum, average, even odd and leap year.
Theory: In this program we have printed HELLO WORLD  and find the sum of two number (user input), average, even odd and also to check entered year is leap year of not using basic C++ language.
Code for the program as follows:
// Ashu Yadav
//23070123154
//experiment 1

#include <iostream>
using namespace std;

int main() {
    cout << "Hello world" << endl;

    int a, b;
    cout << "Enter the value of the first number: ";  
    cin >> a;

    cout << "Enter the value of the second number: ";
    cin >> b;

    int sum = a + b;
    cout << "The sum of the two numbers is: " << sum << endl;
    
    int avg = (a + b) / 2;
    cout << "The average of the two numbers is: " << avg << endl;

    int c;
    cout << "Enter a number: ";
    cin >> c;

    if (c % 2 == 0) {
        cout << "The number is even." << endl;
    } else {
        cout << "The number is odd." << endl;
    }

    int d;
    cout << "Enter the year you want to check whether it is a leap year or not: ";
    cin >> d;

    if ((d % 400 == 0) || (d % 100 != 0 && d % 4 == 0)) {
        cout << "The year entered is a leap year." << endl;
    } else {
        cout << "The year entered is not a leap year." << endl;
    }

    return 0;
}

Co

