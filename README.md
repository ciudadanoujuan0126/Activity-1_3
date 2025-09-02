# Activity-1_3
#include <iostream>
using namespace std;

int main() {
    int product = 1;
    int n = 1;

    while (n <= 5) {
        product *= n;
        n++;
    }

    cout << "Product of numbers from 1 to 5 is: " << product << endl;

    return 0;
}
