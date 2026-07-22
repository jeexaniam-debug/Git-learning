Simple Calculator

A basic command-line calculator built in Python. Supports addition, subtraction, multiplication, and division with input validation and error handling.

Features
Clean menu-driven CLI
Handles invalid input (non-numeric values) gracefully
Handles division by zero without crashing
Unit tests included
Getting Started
Prerequisites
Python 3.7+
Run it
bash
python calculator.py
Run the tests
bash
python -m unittest test_calculator.py
Example
===== Simple Calculator =====
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit
==============================
Choose an operation (1-5): 1
Enter first number: 4
Enter second number: 5

Result: 4.0 add 5.0 = 9.0
Project Structure
calculator-project/
├── calculator.py       # Main program logic
├── test_calculator.py  # Unit tests
└── README.md           # Project documentation
Possible Extensions
Add support for exponents, square roots, and modulo
Add a history log of past calculations
Build a GUI version with tkinter
Turn it into a simple web app (HTML/CSS/JS)
License

Free to use and modify.
