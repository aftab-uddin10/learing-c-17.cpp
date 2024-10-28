#include <iostream>
using namespace std;

int main() {
  // An array storing different ages
  int ages[8] = {20, 22, 18, 35, 48, 26, 87, 70};

  float avg, sum = 0;
  int i;

  // Get the length of the array
  int length = sizeof(ages) / sizeof(ages[0]);

  // Loop through the elements of the array
  for (int age : ages) {
    sum += age;
  }
  
  // Calculate the average by dividing the sum by the length
  avg = sum / length;

  // Print the average
  cout << "The average age is: " << avg << "\n";

  return 0;
}
