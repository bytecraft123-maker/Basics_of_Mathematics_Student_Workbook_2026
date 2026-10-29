# Exercise 2. Addition and Scalar Multiplication

## Problem Statement

Given

\[
A=\begin{pmatrix}1&2\\-1&3\end{pmatrix},
\qquad
B=\begin{pmatrix}4&-2\\0&5\end{pmatrix},
\]

compute

\[
A+B,\qquad A-B,\qquad 3A-2B.
\]

## Theoretical Background

Matrices of the same size can be added or subtracted by adding or subtracting their corresponding entries. To multiply a matrix by a scalar, multiply every entry by that scalar.

## Step-by-Step Solution

### 1. Compute \(A+B\)

Add corresponding entries:

\[
A+B
=
\begin{pmatrix}
1+4 & 2+(-2)\\
-1+0 & 3+5
\end{pmatrix}
=
\begin{pmatrix}
5&0\\
-1&8
\end{pmatrix}.
\]

### 2. Compute \(A-B\)

Subtract corresponding entries:

\[
A-B
=
\begin{pmatrix}
1-4 & 2-(-2)\\
-1-0 & 3-5
\end{pmatrix}
=
\begin{pmatrix}
-3&4\\
-1&-2
\end{pmatrix}.
\]

### 3. Compute \(3A-2B\)

First multiply each matrix by its scalar:

\[
3A=
\begin{pmatrix}
3&6\\
-3&9
\end{pmatrix},
\qquad
2B=
\begin{pmatrix}
8&-4\\
0&10
\end{pmatrix}.
\]

Then subtract corresponding entries:

\[
3A-2B
=
\begin{pmatrix}
3-8 & 6-(-4)\\
-3-0 & 9-10
\end{pmatrix}
=
\begin{pmatrix}
-5&10\\
-3&-1
\end{pmatrix}.
\]

## Verification

All three results are \(2\times2\) matrices, matching the sizes of \(A\) and \(B\). The calculations apply the operations entry by entry.
