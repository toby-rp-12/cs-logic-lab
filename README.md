# cs-logic-lab
A simple python code file that can make certain calculations.

## Features

This project is a small Python utility module that provides helpful mathematical and numeric functions, including calculating a hypotenuse, counting digits, and computing tip amounts, that I made for my computer science class.
The project includes three simple functions:

### hypotenuse(a, b)
Calculates the length of the hypotenuse of a right triangle using the Pythagorean theorem.

### num_digits(n)
Returns the number of digits in an integer (works for negative numbers too).

### tip_amount(total, percent)
Calculates the tip amount based on a total bill and tip percentage, rounded to the nearest whole number.

## How to Run

First, make sure you have:
1. Python 3.x
1. The built-in math module

Then, save the file as something like:
```
math_lab.py
```

Once you do that, run the program on python.

## Examples
**Input:** hypotenuse(3, 4)

**Output:** 5.0


**Input:** num_digits(-12345)

**Output:** 5


**Input:** tip_amount(50, 18)

**Output:** 9

## Other Notes

Some other notes on the project:

- tip_amount rounds to the nearest whole number using Python’s round().
