#include <iostream>
using namespace std;

int main() {
    int age, marks;
    
    
    cout << "Enter age: ";
    cin >> age;
    
    
    cout << "Enter marks: ";
    cin >> marks;
    
    cout << "Concatenated: " << age << marks << endl;

    int product = age * marks;
    cout << "Product of age and marks: " << product << endl;
    
    return 0;
}
