CDS Experiment -01 <br>
Aim: To install VS CODE and print "HELLO WORLD" including sum, average, even odd and leap year. <br>
Theory: In this program we have printed HELLO WORLD  and find the sum of two number (user input), average, even odd and also to check if entered year is leap year of not using basic C++ language.<br>
Code for the program as follows:<br>
// Ashu Yadav <br>
//23070123154 <br>
//experiment 1 <br>

```
#include <iostream> <br>
using namespace std; <br>

int main() { <br>
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
```
} <br>
![exp1](https://github.com/ashuydv-05/CDS-Experiment-1/blob/main/Screenshot%202024-07-30%20151908.png) <br>

Conclusion:<br>
In this experiment we learnt, how to print HELLO WORLD and also to find the sum of two numbers, average , even odd and to check the entered year is leap or not.<br>

