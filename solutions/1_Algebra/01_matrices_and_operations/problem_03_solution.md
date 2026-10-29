# Exercise 3. When Can Matrices Be Multiplied?

## Problem Statement

The matrix sizes are

\[
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
\]

Determine whether each product below is defined. If it is defined, state the size of the result:

\[
AB,\qquad BA,\qquad BC,\qquad CB,\qquad AC,\qquad CA,\qquad AD,\qquad DA.
\]

## Theoretical Background

A product \(XY\) is defined when the number of columns of \(X\) equals the number of rows of \(Y\). If \(X\) has size \(m\times n\) and \(Y\) has size \(n\times p\), then \(XY\) has size \(m\times p\).

## Step-by-Step Solution

1. **\(AB\):** \(A\) is \(2\times3\) and \(B\) is \(3\times4\). The inner dimensions match (3), so \(AB\) is defined and has size \(2\times4\).

2. **\(BA\):** \(B\) is \(3\times4\) and \(A\) is \(2\times3\). The inner dimensions, 4 and 2, do not match, so \(BA\) is not defined.

3. **\(BC\):** \(B\) is \(3\times4\) and \(C\) is \(4\times2\). The inner dimensions match (4), so \(BC\) is defined and has size \(3\times2\).

4. **\(CB\):** \(C\) is \(4\times2\) and \(B\) is \(3\times4\). The inner dimensions, 2 and 3, do not match, so \(CB\) is not defined.

5. **\(AC\):** \(A\) is \(2\times3\) and \(C\) is \(4\times2\). The inner dimensions, 3 and 4, do not match, so \(AC\) is not defined.

6. **\(CA\):** \(C\) is \(4\times2\) and \(A\) is \(2\times3\). The inner dimensions match (2), so \(CA\) is defined and has size \(4\times3\).

7. **\(AD\):** \(A\) is \(2\times3\) and \(D\) is \(2\times2\). The inner dimensions, 3 and 2, do not match, so \(AD\) is not defined.

8. **\(DA\):** \(D\) is \(2\times2\) and \(A\) is \(2\times3\). The inner dimensions match (2), so \(DA\) is defined and has size \(2\times3\).

## Verification

For each defined product, the result's size uses the outer dimensions of the two matrices. Products with unequal inner dimensions are not defined.
