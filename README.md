

---

# Experiment 9: Study of NumPy in Python

---

## Aim

To study the NumPy library in Python 

---

## Theory

### Introduction to NumPy

NumPy (Numerical Python) is one of the most important libraries in Python used for scientific computing and data analysis. It provides support for:

• Large multidimensional arrays
• Mathematical and statistical operations
• High-performance numerical computation
• Efficient memory usage compared to Python lists

NumPy arrays are significantly faster and more efficient than normal Python lists when performing numerical calculations because they are implemented using optimized internal structures.

NumPy is widely used in fields such as Data Science, Machine Learning, Artificial Intelligence, Scientific Computing, and Data Analysis.

---

## Importing NumPy

To use NumPy in a Python program, the library must first be imported.

import numpy as np

Here, **np** is an alias that allows easier access to NumPy functions.

---

## NumPy Commands Used in the Program

### Creating NumPy Arrays

a = np.array([1,10,20,30,40,50,500])
b = np.array([[1,2,3],[4,5,6]])

The **np.array()** function is used to convert Python lists into NumPy arrays.

• **a** is a one-dimensional array
• **b** is a two-dimensional array (matrix)

NumPy arrays store data in a structured format which allows faster mathematical operations.

---

### Printing Arrays

print(a)
print(b)

The **print()** function displays the contents of the arrays.

---

### Finding the Number of Dimensions

a.ndim
b.ndim

The **ndim** attribute returns the number of dimensions of the array.

Examples:

• 1D array → dimension = 1
• 2D array → dimension = 2

---

### Finding the Shape of an Array

a.shape
b.shape

The **shape** attribute returns the structure of the array.

It shows:

• Number of rows
• Number of columns

Examples:

(7,) → 1D array with 7 elements
(2,3) → 2 rows and 3 columns

---

### Finding Data Type of Array Elements

a.dtype
b.dtype

The **dtype** attribute shows the data type of elements stored in the array.

Common NumPy data types include:

• int
• float
• bool

If even one element is a decimal number, NumPy converts the entire array to **float type**.

---

## Special NumPy Functions

NumPy provides built-in functions to quickly generate different types of matrices.

---

### Creating a Zero Matrix

np.zeros((2,3))

The **zeros()** function creates a matrix filled with 0 values.

Example:
2 rows × 3 columns matrix of zeros.

---

### Creating a Ones Matrix

np.ones((3,3))

The **ones()** function generates a matrix filled entirely with 1 values.

Example:
3 × 3 matrix of ones.

---

### Identity Matrix

np.eye(3)

The **eye()** function creates an identity matrix.

An identity matrix is a square matrix where:

• Diagonal elements = 1
• Other elements = 0

Example:

1 0 0
0 1 0
0 0 1

---

### Creating Arrays Using a Range

np.arange(1,10,2)

The **arange()** function generates numbers within a specified range.

Syntax:

np.arange(start, stop, step)

Where:

• start → beginning value
• stop → stops before this value
• step → difference between numbers

Example result:

[1 3 5 7 9]

---

### Creating Evenly Spaced Values

np.linspace(0,1,4)

The **linspace()** function creates equally spaced numbers between two limits.

Syntax:

np.linspace(start, stop, number_of_values)

Example:

Creates **4 evenly spaced numbers between 0 and 1**.

---

## Mathematical Operations on Arrays

NumPy allows **vectorized operations**, meaning operations are applied to all elements simultaneously.

### Multiplication

b * 2

Each element of array **b** is multiplied by 2.

### Addition

a + 5

Adds 5 to every element of the array.

This is faster than looping through elements individually.

---

## Statistical Functions in NumPy

NumPy provides many built-in functions for statistical analysis.

### Mean (Average)

np.mean(a)

Calculates the average value of all elements.

Formula:

Mean = Sum of all elements / Number of elements

---

### Median

np.median(a)

The median is the middle value when numbers are arranged in ascending order.

If the number of elements is even, the median is the average of the two middle numbers.

---

### Standard Deviation

np.std(a)

The standard deviation measures how much the data values deviate from the mean.

A small standard deviation means the data points are close to the mean.

---

### Maximum Value

np.max(a)

Returns the largest value in the array.

---

### Minimum Value

np.min(a)

Returns the smallest value in the array.

---

### Sum of Elements

np.sum(a)

Calculates the total sum of all elements in the array.

---

## Applications of NumPy

NumPy is widely used in:

• Data Science
• Machine Learning
• Artificial Intelligence
• Scientific Computing
• Data Analysis
• Image Processing
• Statistical Modeling

Most Python libraries such as **Pandas, TensorFlow, SciPy, and Scikit-learn** depend heavily on NumPy.

---

## Conclusion

Thus, the NumPy library in Python was successfully studied. The experiment demonstrated how NumPy provides efficient tools for creating arrays, performing mathematical operations, and executing statistical analysis, making it an essential library for numerical and scientific computing.

---



