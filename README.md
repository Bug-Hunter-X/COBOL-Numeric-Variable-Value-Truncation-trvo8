# COBOL Numeric Variable Value Truncation

This example demonstrates a potential error in COBOL programs when initializing numeric variables with values that exceed the declared picture size.  The code attempts to assign a five-digit number to a variable with insufficient space, leading to unexpected behavior during program execution. The solution illustrates a corrected version with sufficient PICTURE clause definition. 

## Bug
The bug.cob file demonstrates the original code with an incorrectly sized numeric variable.

## Solution
The bugSolution.cob file provides a corrected version with an appropriately defined PICTURE clause to handle the value without data loss.