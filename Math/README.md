# Matrix Calculator

A menu-driven C++ program for 3×3 matrix operations.

## Features
- Add or subtract two matrices
- Multiply two matrices (triple nested loop)
- Determinant of one matrix (cofactor expansion along the first row)

## Sample run
    Matrix Calculator
    1. Add two 3x3 matrices
    ...
    Enter your choice: 4
    Determinant of matrix A: <result>

## Limitations / next steps
- Fixed at 3×3. Generalizing to N×N is planned.
- Uses `vector<vector<double>>` for storage.

## Run
    g++ Matrix.cpp -o matrix && ./matrix
