Lab Problem Statement — Employee Performance Report System

Write a Java program to implement a class hierarchy for employees in a company using inheritance and method overriding.

Requirements

Create a base class Employee with the following data members:

name

address

salary

jobTitle

performanceRating (out of 5)

Implement the following methods in the Employee class:

calculateBonus()

generatePerformanceReport()

manageProject()

The method generatePerformanceReport() should generate the report based on the performance rating using the following criteria:

Rating	Performance
5	Outstanding
4	Very Good
3	Good
2	Needs Improvement
1	Poor

Create subclasses:

Manager

Developer

Programmer

Override the calculateBonus() method using the following bonus percentages:

Manager → 20% of salary

Developer → 10% of salary

Programmer → 8% of salary

In the main class:

Create objects for Manager, Developer, and Programmer.

Store them using Employee reference.

Display bonus, performance report, and project management details.
