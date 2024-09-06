# Boolean Functions and Logic Gates

## Overview
This repository contains information and examples related to Boolean functions and logic gates, specifically focusing on OR and NOT gates.

## Table of Contents
- Introduction
- Boolean Functions
- Logic Gates
  - OR Gate
  - NOT Gate
- Examples
- Contributing
- License

## Introduction
Boolean functions are fundamental in digital logic design and computer science. They are used to perform logical operations on binary variables. This repository provides a detailed explanation of Boolean functions and the implementation of OR and NOT gates.

## Boolean Functions
Boolean functions are expressions formed using binary variables, the constants 0 and 1, and the logical operations AND, OR, and NOT. These functions are used to represent and manipulate logical statements.

## Logic Gates
Logic gates are the building blocks of digital circuits. They perform basic logical functions that are essential for digital computing.

### OR Gate
The OR gate is a digital logic gate that implements logical disjunction. It outputs true or 1 when at least one of its inputs is true or 1.

**Truth Table:**
| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

### NOT Gate
The NOT gate is a digital logic gate that implements logical negation. It outputs the opposite value of its input.

**Truth Table:**
| A | Output |
|---|--------|
| 0 |   1    |
| 1 |   0    |

## Examples
Here are some examples of how OR and NOT gates can be used in digital circuits:

1. **OR Gate Example:**
   ```python
   def or_gate(a, b):
       return a or b

   # Test the OR gate function
   print(or_gate(0, 0))  # Output: 0
   print(or_gate(0, 1))  # Output: 1
   print(or_gate(1, 0))  # Output: 1
   print(or_gate(1, 1))  # Output: 1

 NOT Gate Example:
Python

def not_gate(a):
    return not a

# Test the NOT gate function
print(not_gate(0))  # Output: 1
print(not_gate(1))  # Output: 0
