# -*- coding: utf-8 -*-
# Application of Accelerators
# Exercise 01
# by Fynn Sören Sauerwein

import numpy as np

# Task 1
# Definition of function
def add(value1,value2):
    # function adds just two numbers
    return value1 + value2

# Print result
print('Result from add = ',add(2,2))

#Task 2
# Definition of function
def multiply(array1,array2):
    return array1.dot(array2)

# Create random 3x3 matrices
a = np.random.random((3,3))
b = np.random.random((3,3))

# Print results
print('\nMatrix 1\n',a)
print('\nMatrix 2\n',b)
print('\nResult from multiply = \n',multiply(a,b))