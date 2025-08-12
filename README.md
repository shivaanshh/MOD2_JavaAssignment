Java Module 2 Assignment
This repository contains solutions for Java Module 2 assignment, covering packages, interfaces, functional interfaces, lambda expressions, exception handling, and custom exceptions.
Each section demonstrates Java concepts through small, self-contained programs.

📂 Section 1: Defining, Implementing, and Importing Packages
MathUtils Package

Package: utilities

Class: MathUtils

Method: add(int a, int b) → returns the sum of two integers.

Demonstrated by importing and using this package in another class.

Shapes Package

Package: shapes

Interface: Shape

Methods: double area(), double perimeter()

Implementations:

Circle

Rectangle

Demonstrates interface implementation in packages.

Using Java Utility Package

Imports java.util.ArrayList

Stores and displays a list of integers.

📂 Section 2: Interfaces & Functional Programming
Functional Interface with Lambda Expression

Interface: Calculator

Method: int compute(int a, int b)

Lambda expressions for addition, subtraction, and multiplication.

Lambda for Sorting

Sorts a list of strings in descending order using a lambda expression.

Method Reference

Uses a static method to find the square of a number via method reference.

📂 Section 3: Errors and Exceptions
Try-Catch vs Try-Catch-Finally

Demonstrates difference by dividing two numbers.

Handles ArithmeticException.

Custom Exception - InvalidAgeException

Thrown if user’s age is less than 18.

Demonstrates custom exception handling.

Custom Exception with Logging

Same as above but logs the error using java.util.logging.

Throw & Throws Keywords

Calculates factorial of a number.

Throws exception if input is negative.
