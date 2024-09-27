# Project: Matrix Calculations with NumPy

This project demonstrates how to perform various statistical calculations on a list of numbers after converting it into a 3x3 matrix using NumPy.

## Objectives:

1. **Input Validation**:
   - Ensure that the input list contains exactly 9 numbers.
   - Raise a `ValueError` if the input does not meet the required conditions.

2. **Matrix Reshaping**:
   - Convert the input list into a 3x3 matrix using NumPy.

3. **Statistical Calculations**:
   - Calculate the following statistics for the matrix:
     - **Mean**: The average of the values across the columns, rows, and the entire matrix.
     - **Variance**: The measure of how spread out the numbers are, calculated along the columns, rows, and the whole matrix.
     - **Standard Deviation**: The square root of variance, computed for both axes and the whole matrix.
     - **Maximum and Minimum Values**: The largest and smallest values in each axis and the entire matrix.
     - **Sum**: The total sum of the values along both axes and the whole matrix.

4. **Result Structure**:
   - Return the calculated statistics in a dictionary where each key corresponds to a specific calculation (e.g., mean, variance), and each value is a list containing:
     - Column-wise result
     - Row-wise result
     - Overall matrix result


