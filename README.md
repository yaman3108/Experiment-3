# EXPERIMENT 3.



## Aim:
To demonstrate the use of arithmetic operators, assignment operators, and comparison operators in C++.

## Apparatus:
VS Code,Github


## Theory:
This program demonstrates the use of different types of operators in C++:

### Arithmetic Operators:
These include +(addition), -(subtraction), *(multiplication), /(division), and % (modulus). They are used to perform basic mathematical operations in C++.

### Assignment Operators:
These operators are used to assign values to variables. The basic assignment operator = assigns a value to a variable, while operators like +=, -=, *=, and /= combine  the particular arithmetic operation with assignment.

### Comparison Operators:
These include ==(equal to), !=(not equal to), >(greater than), <(less than), >=(greater than or equal to), and <=(less than or equal to). They are used to compare values and give the result as a boolean value either true or false.


## Explanation:

### Arithematic,assignment,comparision operators:
In this program we use the various different types of operators such as Arithematic operators, Assignment operators and comparision operators in order to learn and understand thier syntax and working in C++. We then print thier outputs using the "cout<<" command.

## Code:

### Use of arithematic,assignment and comparision operators:
```
#include<iostream> 
using namespace std; 

//Name: Yaman Hasan Ansari 
//PRN:23070123155 

int main() { 
    // Arithmetic Operators 
    int a = 10; 
    int b = 5; 
    
    cout<< "Arithmetic Operators:" <<endl; 
    cout<< "a + b = " << a + b <<endl; 
    cout<< "a - b = " << a - b <<endl; 
    cout<< "a * b = " << a * b <<endl; 
    cout<< "a / b = " << a / b <<endl; 
    cout<< "a % b = " << a % b <<endl; 

    // Assignment Operators 
    int c = a; 
    c += b; 
    cout<< "Assignment Operators:" <<endl; 
    cout<< "c after c += b: " << c <<endl; 
    c -= b; 
    cout<< "c after c -= b: " << c <<endl; 
    c *= b; 
    cout<< "c after c *= b: " << c <<endl; 
    c /= b; 
    cout<< "c after c /= b: " << c <<endl; 
    c %= b; 
    cout<< "c after c %= b: " << c <<endl; 

    // Comparison Operators 
    cout<< "Comparison Operators:" <<endl; 
    cout<< "a == b: " << (a == b) <<endl; 
    cout<< "a != b: " << (a != b) <<endl; 
    cout<< "a > b: " << (a > b) <<endl; 
    cout<< "a < b: " << (a < b) <<endl; 
    cout<< "a >= b: " << (a >= b) <<endl; 
    cout<< "a <= b: " << (a <= b) <<endl; 

    return 0; 
} 
```

### Output:
![Screenshot 2024-07-30 104208](https://github.com/user-attachments/assets/723cba7e-1d94-412d-ac97-d71e6822ae03)


## Conclusion:
This program provides a overview of how different types of operators are used in C++. Understanding these operators is important for performing various operations and implementing logic in C++ programs. This program serves as a practical guide for beginners to get familiar with operators and their applications in C++.
