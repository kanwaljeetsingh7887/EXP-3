# EXP 3
## Aim:
To study and implement Operators in C++

## Software:
Microsoft VSCode

## Theory:
 Opeartors in C++ are the symbols that are used two perform some mathematocalor logical operations on the variables.
They are classified into 6 types:
**1. Arithmetic Operators:**
+ Addition `(+)`: Adds two operands.
+ Subtraction `(-)`: Subtracts the second operand from the first.
+ Multiplication `(*)`: Multiplies two operands.
+ Division `(/)`: Divides the first operand by the second.
+ Modulus `(%)`: Returns the remainder of division.

**2. Relational Operators:**
+ Equal to `(==)`: Checks if two values are equal.
+ Not equal to `(!=)`: Checks if two values are not equal.
+ Greater than `(>)`: Checks if the first value is greater than the second.
+ Less than `(<)`: Checks if the first value is less than the second.
+ Greater than or equal to `(>=)`: Checks if the first value is greater than or equal to the second.
+ Less than or equal to `(<=)`: Checks if the first value is less than or equal to the second.

**3. Logical Operators:**
+ Logical AND `(&&)`: Returns true if both operands are true.
+ Logical OR `(||)`: Returns true if at least one operand is true.
+ Logical NOT `(!)`: Reverses the logical state of its operand.

**4. Assignment Operators:**
+ Simple assignment `(=)`: Assigns the value on the right to the variable on the left.
+ Add and assign `(+=)`: Adds the right operand to the left operand and assigns the result to the left operand.
+ Subtract and assign `(-=)`: Subtracts the right operand from the left operand and assigns the result to the left operand.
+ Multiply and assign `(*=)`: Multiplies the left operand by the right operand and assigns the result to the left operand.
+ Divide and assign `(/=)`: Divides the left operand by the right operand and assigns the result to the left operand.
+ Modulus and assign `(%=)`: Takes the modulus using the left and right operands and assigns the result to the left operand.

**6. Bitwise Operators:**
+ AND `(&)`: Performs a bitwise AND.
+ OR `(|)`: Performs a bitwise OR.
+ XOR `(^)`: Performs a bitwise XOR.
+ NOT `(~)`: Performs a bitwise NOT.
+ Left Shift `(<<)`: Shifts bits to the left.
+ Right Shift `(>>)`: Shifts bits to the right.










Basic Datatype
Derived Datatype
User-Defined Datatype
Storage class in C++ determines the characteristics of a variable. C++ has 5 types of storage classes which are as follows:

Auto
Extern
Mutable
Register
Static
Code: 2A
//KANWALJEET SINGH
//ENTC B2
//EXP 2A
//23070123124
#include <iostream>
using namespace std;
int main() {
    cout << "size of char: " << sizeof(char) << " byte" << endl;
    cout << "size of int: " << sizeof(int) << " byte" << endl;
    cout << "size of float: " << sizeof(float) << " byte" << endl;
    cout << "size of double: " << sizeof(double) << " byte" << endl;
    cout << "size of short int: " << sizeof(short int) << "byte" << endl;
    cout << "size of long int: " << sizeof(long int) << "byte" << endl;
    cout << "size of unsigned char: " << sizeof(unsigned char) << "byte" << endl;
    cout << "size of signed char: " << sizeof(signed char) << "byte" << endl;
    cout << "size of unsigned int: " << sizeof(unsigned int) << "byte" << endl;
    cout << "size of signed int: " << sizeof(signed int) << "byte" << endl;
    cout << "size of unsigned long int: " << sizeof(unsigned long int) << "byte" << endl;
    cout << "size of signed long int: " << sizeof(signed long int) << "byte" << endl;
    cout << "size of unsigned short int: " << sizeof(unsigned short int) << "byte" << endl;
    cout << "size of signed short int: " << sizeof(signed short int) << "byte" << endl;
    cout << "size of unsigned long long int: " << sizeof(unsigned long long int) << "byte" << endl;
    cout << "size of bool: " << sizeof(bool) << "byte" << endl;
    return 0;
}
Output:
image

Code: 2B
//KANWALJEET SINGH
//ENTC B2
//EXP 2B
//23070123124
#include<iostream>
using namespace std;
int main() {
    int a;
    char b;
    signed char c;
    unsigned char d;
    float e;
    double f;
    long double g;
    bool h;
    cout<<"Enter an integer: ";                     
    cin>>a;
    cout<<"Size of int is:"<<sizeof(a)<<"\n";        

    cout<<"Enter a character: ";                   
    cin>>b;
    cout<<"Size of char is:"<<sizeof(b)<<"\n";        

    cout<<"Enter a character: ";                    
    cin>>c;
    cout<<"Size of signed char is:"<<sizeof(c)<<"\n";     

    cout<<"Enter a character: ";                        
    cin>>d;
    cout<<"Size of unsigned char is:"<<sizeof(d)<<"\n";  

    cout<<"Enter a number: ";                             
    cin>>e;
    cout<<"Size of float is:"<<sizeof(e)<<"\n";           
    

    cout<<"Enter a number: ";                            
    cin>>f;
    cout<<"Size of double is:"<<sizeof(f)<<"\n";         

    cout<<"Enter a number: ";                           
    cin>>g;
    cout<<"Size of long double is:"<<sizeof(g)<<"\n";   

    cout<<"Enter a bool value: ";                      
    cin>>h;
    cout<<"Size of bool is:"<<sizeof(h)<<"\n";            
return 0;
}
Output:
image

Code: 2C
//KANWALJEET SINGH
//ENTC B2
//EXP 2C
//23070123124
#include<iostream>
using namespace std;

int main() {
    int a;
    cout<<"Enter a number: ";                       
    cin>>a;
    cout<<"\nInteger= "<<a<<" and size is "<<sizeof(a)<<" bytes.";  

    register int b;
    cout<<"\nEnter a number: ";                                     
    cin>>b;
    cout<<"\nRegister= "<<b<<" and size is "<<sizeof(b)<<" bytes.";   

    static int d;
    cout<<"\nEnter any number: ";                                      
    cin>>d;
    cout<<"\nStatic= "<<d<<" and size is "<<sizeof(d)<<" bytes.";      

    return 0;
}
Output:
image

Conclusion:
By studying and implementing various data types in C++, you build a strong foundation in how the language handles data and memory. This knowledge is essential for writing efficient and effective C++ programs. Practicing with real-world examples and exploring advanced concepts like dynamic memory allocation will deepen your understanding and prepare you for more complex programming challenges.# EXP-3
