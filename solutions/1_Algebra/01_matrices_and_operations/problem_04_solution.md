# Exercise 4. Matrix Multiplication and Noncommutativity

## Problem Statement

Given

\[
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\3&1\end{pmatrix},
\]

compute \(AB\) and \(BA\). Determine whether \(AB=BA\), and explain what noncommutativity of matrix multiplication means.

## Theoretical Background

To multiply matrices, take the dot product of each row of the first matrix with each column of the second. Matrix multiplication is generally **not commutative**: reversing the order of the matrices may change the result.

## Step-by-Step Solution

### 1. Compute \(AB\)

\[
AB
=
\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}2&0\\3&1\end{pmatrix}
=
\begin{pmatrix}
1\cdot2+2\cdot3 & 1\cdot0+2\cdot1\\
0\cdot2+1\cdot3 & 0\cdot0+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}8&2\\3&1\end{pmatrix}.
\]

### 2. Compute \(BA\)

\[
BA
=
\begin{pmatrix}2&0\\3&1\end{pmatrix}
\begin{pmatrix}1&2\\0&1\end{pmatrix}
=
\begin{pmatrix}
2\cdot1+0\cdot0 & 2\cdot2+0\cdot1\\
3\cdot1+1\cdot0 & 3\cdot2+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}2&4\\3&7\end{pmatrix}.
\]

### 3. Compare the results

\[
AB=\begin{pmatrix}8&2\\3&1\end{pmatrix}
\qquad\text{and}\qquad
BA=\begin{pmatrix}2&4\\3&7\end{pmatrix}.
\]

Therefore, \(AB\ne BA\).

## Verification and Interpretation

Both products are defined because \(A\) and \(B\) are \(2\times2\) matrices. Their different results show that matrix multiplication is not commutative in general: changing the order can change the product.
