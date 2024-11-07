# Mathematical Functions Library

This library provides a set of mathematical functions for calculating distances, hypotenuses, permutations, combinations, and series sums. Each function is designed to solve specific problems in geometry or sequence operations.

## Functions Overview

### 1. `distance(x1, y1, x2, y2)`
Calculates the distance between two points \((x_1, y_1)\) and \((x_2, y_2)\) using the distance formula.  
- **Example**: Calculate the distance between points (3, 4) and (7, 1).

### 2. `hypotenuse(a, b)`
Finds the length of the hypotenuse of a right triangle given its two perpendicular sides \(a\) and \(b\).  
- **Example**: Calculate the hypotenuse for sides of lengths 6 and 8.

### 3. `permutation(n, r)`
Calculates the number of permutations for \(n\) objects taken \(r\) at a time using the formula:
\[
P(n, r) = \frac{n!}{(n - r)!}
\]
- **Example**: Calculate \(P(5, 3)\).

### 4. `arithmetic_sum(a, d, n)`
Computes the sum of the first \(n\) terms of an arithmetic series with the first term \(a\) and common difference \(d\).  
- **Formula**:
  \[
  S_n = \frac{n}{2} \times (2a + (n - 1) \times d)
  \]
- **Example**: Find the sum of the first 10 terms with \(a = 5\) and \(d = 3\).

### 5. `combination(n, r)`
Calculates the number of combinations for \(n\) objects taken \(r\) at a time using the formula:
\[
C(n, r) = \frac{n!}{r! \times (n - r)!}
\]
- **Example**: Calculate \(C(7, 3)\).

### 6. `geometric_sum(a, r, n)`
Calculates the sum of the first \(n\) terms of a geometric series where \(a\) is the first term and \(r\) is the common ratio.  
- **Formula**:
  - If \( r = 1 \): \( S_n = a \times n \)
  - If \( r \neq 1 \): \( S_n = a \times \frac{1 - r^n}{1 - r} \)
- **Example**: Find the sum of the first 8 terms with \(a = 3\) and \(r = 2\).

## Usage
Each function is standalone and can be used individually to perform specific calculations related to distance, triangles, permutations, combinations, and series sums.

This library is ideal for anyone needing quick calculations for geometry or sequence problems in a mathematical or programming context.
