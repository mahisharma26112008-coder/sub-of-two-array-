# sub-of-two-array-

#include <iostream>
using namespace std;

int main() {
    int a[5], b[5], c[5];
    int i, choice;

    cout << "Enter first array elements: ";
    for (i = 0; i < 5; i++)
        cin >> a[i];

    cout << "Enter second array elements: ";
    for (i = 0; i < 5; i++)
        cin >> b[i];

    cout << "1. Subtraction of arrays\n";
    cout << "Enter your choice: ";
    cin >> choice;

    switch (choice) {
        case 1:
            for (i = 0; i < 5; i++)
                c[i] = a[i] - b[i];

            cout << "Result: ";
            for (i = 0; i < 5; i++)
                cout << c[i] << " ";
            break;

        default:
            cout << "Invalid choice";
    }

    return 0;
}
