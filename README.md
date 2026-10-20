
#include <iostream>
using namespace std;
int main() {
    int a[5], b[5], sum[5];
    cout << "Enter 5 elements of first array: ";
    for (int i = 0; i < 5; i++) {
        cin >> a[i];
    }
    cout << "Enter 5 elements of second array: ";
    for (int i = 0; i < 5; i++) {
        cin >> b[i];
    }
    for (int i = 0; i < 5; i++) {
        sum[i] = a[i] + b[i];
    }
    cout << "Sum of two arrays: ";
    for (int i = 0; i < 5; i++) {
        cout << sum[i] << " ";
    }
    return 0;
}
