# Inline Function Cube Calculation

A C++ program demonstrating the use of an inline function to calculate and display the cube of an integer.

## Description

This program uses an inline function `cube()` to compute the cube of an integer and print the result. Inline functions are used to reduce the overhead of function calls by suggesting to the compiler to insert the function's code directly into the calling location.

### Key Features
- Inline function implementation
- Cube calculation
- Efficient function call handling
- Simple arithmetic operation

## Code Structure

```cpp
#include <iostream>
using namespace std;

inline void cube(int n) {
    cout << n * n * n << endl;
}

int main() {
    cube(2);
    cube(4);
    cube(6);
    return 0;
}
