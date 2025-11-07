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

## Q2. Define two structures:

   Marks with members math, science, and english (floats).

   Student with members rollNo (int), name(string), and marks (of type Marks).

   Declare an array of 5 Student structures. Accept input for all students and their marks, compute their average marks, and then display:

  (a) The student with the highest average marks, and

  (b) The student with the lowest average marks.

### Test Case:
```text
Roll No: 1
Name: Riya
Math: 90
Science: 85
English: 88

Roll No: 2
Name: Karan
Math: 70
Science: 65
English: 72

Roll No: 3
Name: Neha
Math: 95
Science: 92
English: 96

Roll No: 4
Name: Arjun
Math: 55
Science: 60
English: 58

Roll No: 5
Name: Meena
Math: 80
Science: 78
English: 82

Output:

Student with Highest Average Marks:
Roll No: 3
Name: Neha
Average Marks: 94.33

Student with Lowest Average Marks:
Roll No: 4
Name: Arjun
Average Marks: 57.67
```
## Q3. Define a structure Employee with members id(int), name (string), and salary (float). Declare an array of 5 employees and read their details from user input. Write a menu-driven program that allows the user to:

(a) Display all employee details.

(b) Search for an employee by id.

(c) Increase the salary of all employees earning less than ₹30,000 by 10%.

(d) Exit.

### Test Case:
```text
Employee 1:
ID: 101
Name: Riya
Salary: 28000

Employee 2:
ID: 102
Name: Karan
Salary: 32000

Employee 3:
ID: 103
Name: Neha
Salary: 25000

Employee 4:
ID: 104
Name: Arjun
Salary: 30000

Employee 5:
ID: 105
Name: Meena
Salary: 27000

Output:
==============================
 Employee Menu 
==============================
1. Display all employee details
2. Search employee by ID
3. Increase salary (< ₹30,000) by 10%
4. Exit
Enter your choice: 2

Enter Employee ID to search: 104

Employee Found:
ID: 104
Name: Arjun
Salary: 30000.00
```
## Q4. Define a structure SalesRecord with members month (string), amount (float). Allow the user to input the sales data for all 12 months, and then:

  (a) Write all data to a text file named "sales_data.txt".

  (b) Read the data back from the file.

  (c) Display the month(s) where sales were above the yearly average.

### Test Case:
```text
January: 20000
February: 25000
March: 27000
April: 30000
May: 15000
June: 22000
July: 18000
August: 26000
September: 31000
October: 24000
November: 19000
December: 28000

Output:

Data successfully written to 'sales_data.txt'.

Yearly Average Sales: 23750.00

Months with sales above yearly average:
February   : 25000.00
March      : 27000.00
April      : 30000.00
August     : 26000.00
September  : 31000.00
December   : 28000.00
