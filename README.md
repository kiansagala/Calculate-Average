# Calculate-Average
#include <iostream>
using namespace std;
 
int main() {
    int i, count, sum, inputArray[500];
    float average;
 
    cout << "Enter number of data\n";
    cin >> count;
     
    cout << "Enter " << count << " data\n";
    
    for(i = 0; i < count; i++) {
        cin >> inputArray[i];
    }
     
    sum = 0;
    
    for(i = 0; i < count; i++) {
        sum += inputArray[i];
    }
 
    average = (float)sum / count;
    cout << "Average = " << average;
 
    return 0;
}
