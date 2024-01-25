#include <iostream>
using namespace std;

int main() {

  int first_number, second_number, sum, sub;
    
  cout << "Enter two integers: ";
  cin >> first_number >> second_number;

  // sum of two numbers in stored in variable sumOfTwoNumbers
  sum = first_number + second_number;
// subtrtaction  of two numbers in stored in variable sumOfTwoNumbers
  sub = first_number - second_number;

  // prints sum 
  cout << first_number << " + " <<  second_number << " = " << sum;  
// prints subtraction 
  cout << first_number << " - " <<  second_number << " = " << sub;     

  return 0;
}
