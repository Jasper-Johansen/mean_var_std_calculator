# Mean Variance Standard Deviation Calculator

## Project Overview

This project involves creating a Python function, `calculate()`, that performs statistical analysis on a 3x3 matrix. The function calculates the mean, variance, standard deviation, max, min, and sum along both axes (rows and columns) as well as for the entire flattened matrix.

## Objective

The goal is to create a function that:
- Takes a list of 9 numbers as input.
- Converts the list into a 3x3 Numpy array.
- Returns a dictionary containing:
  - Mean, variance, standard deviation, max, min, and sum for the rows, columns, and the entire flattened matrix.

## Input
- list (List): A list containing exactly 9 numerical values (integers or floats). If the list contains fewer than 9 elements, a ValueError is raised.

## Output 
Output:
- Returns a dictionary with the following keys and values:

python
```
{
  'mean': [axis1, axis2, flattened],
  'variance': [axis1, axis2, flattened],
  'standard deviation': [axis1, axis2, flattened],
  'max': [axis1, axis2, flattened],
  'min': [axis1, axis2, flattened],
  'sum': [axis1, axis2, flattened]
}
```
Where:

-- axis1: Values calculated for each column.

-- axis2: Values calculated for each row.

-- flattened: Values calculated for the entire flattened matrix.

## Development
The code is written in Python and makes use of the <code>numpy</code> library for array manipulation and statistical calculations.

To run your code for testing or further development, simply execute the script in your development environment.