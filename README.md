#include <iostream>

int main() {
    // Objective 1: Include the correct namespace.
    using namespace std;

    // Objective 2: Declare the required variables.
    //double value, sum = 0;
    double value; 
    double sum = 0;
  
    // Objective 3: Use cin and cout to get data from the user.
    cout << "Enter 5 values, one at a time:" << endl;

    for (int i = 0; i < 6; i=i+2) {
      //i=i+1
        cout << "Value " <<(i+2)/2 << ": ";
        cin >> value;

        // Objective 4: Perform correct processing and math operations.
        sum += value; // sum = sum + value;
    }

    // Objective 5: Print out the result in the form of "The sum of your values is: X"
    cout << "The sum of your values is: " << sum << endl;

    return 0;
}
