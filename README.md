# intersection_of_two_arrays
// INTERSECTION OF TWO ARRAYS
#include <iostream>
using namespace std;

void findintersect(int arr1[], int arr2[], int size) {
    for (int i=0; i<size; i++) {
        for (int j=0; j<size; j++) {
            if (arr1[i] == arr2[j]) {
                cout << "intersection found, the intersecting element is";
                cout << arr1[i] << endl;
            }
        }
    }
}

int main() {
    int arr1[] = {2,4,6,8};
    int arr2[] = {3,4,5,6};
    findintersect(arr1, arr2, 4);
    return 0;
}
