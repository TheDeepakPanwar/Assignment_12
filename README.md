# Assignment_12
## Q1. Create a class Rectangle with data members length and breadth, having a default constructor that initializes both to 1 and a parameterized constructor that initializes them with user-given values. Write a member function to calculate and display the area. Demonstrate the use of both constructors by creating two objects, one with default and another with parameterized values.

### Test Case:
```text
Using Default Constructor:
Area = 1

Enter length and breadth: 2
3
Using Parameterized Constructor:
Area = 6
```

## Q2. Define a class Complex to represent complex numbers using constructor overloading. Include three constructors: a default constructor setting both real and imaginary parts to 0, a constructor initializing only the real part (imaginary = 0), and another initializing both real and imaginary parts. Display the complex numbers in the form a + bi and demonstrate all three constructors through different objects.

### Test Case:
```text
Default Constructor Object: 0 + 0i

Enter real part for second complex number: 1
Object with only real part: 1 + 0i

Enter real and imaginary parts for third complex number: 3
4
Object with real and imaginary parts: 3 + 4i
```
## Q3. Write a program to create a class Car with data members brand and price. Use a parameterized constructor to initialize the values. Create two car objects with different values and display their details.

### Test Case:
```text
Enter brand of first car: suv
Enter price of first car: 245

Enter brand of second car: swift
Enter price of second car: 345

Car 1 Details: Brand: suv, Price: 245
Car 2 Details: Brand: swift, Price: 345
```
## Q4. Create a class Box having data members length, breadth, and height. Use constructor overloading to initialize: (a) all values as 1, (b) one value, and (c) all three values. Display the volume for each case.

### Test Case:
```text
Using Default Constructor (1,1,1): Volume = 1

Enter one value for second box: 2
Using One Value Constructor: Volume = 8

Enter length, breadth, and height for third box: 3
4
5
Using Three Values Constructor: Volume = 60
