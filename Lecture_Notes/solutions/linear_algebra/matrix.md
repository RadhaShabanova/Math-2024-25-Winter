# Mathematics

Exercises 2024/2025

---

## 1. Basic Operations on Matrices

![alt text](<Screenshot 2024-11-22 at 10.52.17 AM.png>)

For the following matrices:

$$
\mathbf{A}=
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad
\mathbf{C}=
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
\qquad
\mathbf{D}=
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6 
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
1 & 2\\
4 & 5\\
7 & 8
\end{pmatrix}
$$

---

## Solutions

### 1. Matrix Additions and Subtractions

#### 1.1 \( A + B \)
$$
\mathbf{A} + \mathbf{B} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
+
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}=
\begin{pmatrix}
6 & 8 \\
10 & 12
\end{pmatrix}
$$

#### 1.2 \( B - A \)
$$
\mathbf{B} - \mathbf{A} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}-
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}=
\begin{pmatrix}
4 & 4 \\
4 & 4
\end{pmatrix}
$$

#### 1.3 \( A + C \)
$$
\mathbf{A} + \mathbf{C} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
+
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}=
\begin{pmatrix}
0 & 4 \\
6 & 4
\end{pmatrix}
$$

#### 1.4 \( D + E \)
$$
\mathbf{D} + \mathbf{E} =
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
+
\begin{pmatrix}
1 & 2\\
4 & 5\\
7 & 8
\end{pmatrix}=
\text{can not be done}
$$



---

### 2. Scalar Multiplications

#### 2.1 $\frac{1}{2} \mathbf{A}$

$$
\frac{1}{2} \mathbf{A} =
\frac{1}{2}
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}=
\begin{pmatrix}
0.5 & 1 \\
1.5 & 2
\end{pmatrix}
$$

#### 2.2 $2 \mathbf{B}$

$$
2 \mathbf{B} =
2 \cdot
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}=
\begin{pmatrix}
10 & 12 \\
14 & 16
\end{pmatrix}
$$

#### 2.3 \( -3C \)

$$
-3 \mathbf{C} =
-3 \cdot
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}=
\begin{pmatrix}
3 & -6 \\
-9 & 0
\end{pmatrix}
$$

#### 2.4 \( 4D \)

$$
4 \mathbf{D} =
4 \cdot
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}=
\begin{pmatrix}
-4 & 8 & 12 \\
16 & 0 & 24
\end{pmatrix}
$$

---

### 3. Matrix Products

#### 3.1 $\mathbf{A} \cdot \mathbf{B} $

$$
\mathbf{A} \cdot \mathbf{B} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\cdot
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}=
\begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

#### 3.2 $\mathbf{B} \cdot \mathbf{A}$

$$
\mathbf{B} \cdot \mathbf{A} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\cdot
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}=
\begin{pmatrix}
23 & 34 \\
31 & 46
\end{pmatrix}
$$

#### 3.3 $\mathbf{A} \cdot \mathbf{D}$

$$
\mathbf{A} \cdot \mathbf{D} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\cdot
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}=
\begin{pmatrix}
7 & 2 & 15 \\
13 & 6 & 33
\end{pmatrix}
$$

#### 3.4 $\mathbf{D} \cdot \mathbf{E}$

$$
\mathbf{D} \cdot \mathbf{E} =
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
\cdot
\begin{pmatrix}
1 & 2 \\
4 & 5 \\
7 & 8
\end{pmatrix}=
\begin{pmatrix}
26 & 40 \\
46 & 64
\end{pmatrix}
$$

## 2. Determinants 2x2 and 3x3


2x2 matrices:

$$
\mathbf{A} = 
\begin{pmatrix}
2 & 3 \\
1 & 4
\end{pmatrix}
\qquad
\mathbf{B} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad
\mathbf{C} =
\begin{pmatrix}
-1 & 2 \\
3 & 0 
\end{pmatrix}
$$

![alt text](<Screenshot 2024-11-26 at 4.10.14 PM.png>)

**Determinants:**

$$
\text{det}(A) = (2)(4) - (3)(1) = 8 - 3 = 5
$$

$$
\text{det}(B) = (5)(8) - (6)(7) = 40 - 42 = -2
$$

$$
\text{det}(C) = (-1)(0) - (2)(3) = 0 - 6 = -6
$$

3x3 matrices:

$$
\mathbf{D} = 
\begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 4 & -2
\end{pmatrix}
\qquad
\mathbf{E} =
\begin{pmatrix}
3 & 1 & -1 \\
0 & 2 & 4 \\
5 & 3 & 2
\end{pmatrix}
\quad
\mathbf{F} =
\begin{pmatrix}
2 & -3 & 1 \\
1 & 4 & -2 \\
1 & 5 & 3
\end{pmatrix}
$$

![alt text](<Screenshot 2024-11-26 at 4.10.26 PM.png>)

**Determinants**

For D

$$
\text{det}(D) = 1((3)(-2) - (1)(4)) - 0((-1)(-2) - (1)(2)) + 2((-1)(4) - (3)(2))
$$

$$
\text{det}(D) = 1(-6 - 4) - 0(2 - 2) + 2(-4 - 6) = -10 + 0 - 20 = -30
$$

For E

$$
\text{det}(E) = 3((2)(2) - (4)(3)) - 1((0)(2) - (4)(5)) + (-1)((0)(3) - (2)(5))
$$

$$
\text{det}(E) = 3(4 - 12) - 1(0 - 20) - 1(0 - 10) = 3(-8) - (-20) - (-10) = -24 + 20 + 10 = 6
$$

For F

$$
\text{det}(F) = 2((4)(3) - (-2)(5)) - (-3)((1)(3) - (-2)(1)) + 1((1)(5) - (4)(1))
$$

$$
\text{det}(F) = 2(12 + 10) - (-3)(3 + 2) + 1(5 - 4) = 2(22) + 15 + 1 = 44 + 15 + 1 = 60
$$

## 3. Determinants using Laplace's Expansion

$$
\mathbf{A} =
\begin{pmatrix}
2 & 3 & 1 \\
1 & 4 & 0 \\
3 & 2 & 1
\end{pmatrix}
\qquad
\mathbf{B} =
\begin{pmatrix}
2 & 3 & 1 \\
1 & 4 & 0 \\
3 & 2 & 0 
\end{pmatrix}
\qquad
\mathbf{C} =
\begin{pmatrix}
2 & 3 & 1 & 4 \\
1 & 0 & 0 & 5 \\
3 & 2 & 1 & 5 \\
2 & 1 & 4 & 0 
\end{pmatrix}
\qquad
\mathbf{D} = 
\begin{pmatrix}
2 & 3 & 1 & 4 & 5 \\
1 & 4 & 0 & 0 & 7 \\
3 & 0 & 0 & 0 & 0 \\
2 & 1 & 4 & 3 & 2 \\
1 & 2 & 3 & 4 & 5 
\end{pmatrix}
$$

![alt text](<Screenshot 2024-11-26 at 4.12.34 PM.png>)

![alt text](<Screenshot 2024-11-26 at 4.13.16 PM.png>)

**Determinants**

For A

$$
\text{det}(A) = 2((4)(1) - (0)(2)) - 3((1)(1) - (0)(3)) + 1((1)(2) - (4)(3))
$$

$$
\text{det}(A) = 2(4 - 0) - 3(1 - 0) + 1(2 - 12)
$$

$$
\text{det}(A) = 2(4) - 3(1) + 1(-10) = 8 - 3 - 10 = -5
$$

For B

$$
\text{det}(B) = 2((4)(0) - (0)(2)) - 3((1)(0) - (0)(3)) + 1((1)(2) - (4)(3))
$$

$$
\text{det}(B) = 2(0 - 0) - 3(0 - 0) + 1(2 - 12)
$$

$$
\text{det}(B) = 0 - 0 + 1(-10) = -10
$$

For C 

$$
\text{det}(C) = 2 \begin{vmatrix} 0 & 0 & 6 \\ 2 & 1 & 5 \\ 1 & 4 & 0 \end{vmatrix} - 3 \begin{vmatrix} 1 & 0 & 6 \\ 3 & 1 & 5 \\ 2 & 4 & 0 \end{vmatrix} + 1 \begin{vmatrix} 1 & 0 & 2 \\ 3 & 2 & 5 \\ 2 & 1 & 0 \end{vmatrix} - 4 \begin{vmatrix} 1 & 0 & 2 \\ 3 & 2 & 1 \\ 2 & 1 & 4 \end{vmatrix}
$$

For D

$$
\text{det}(D) = 77
$$

## 4. Determinants from the Gauss Method and Triangular Matrices


### Matrix \( A \)


$$
\mathbf{A} =
\begin{pmatrix} 
12 & 3 \\
-18 & -4
\end{pmatrix}
$$


### Row Operations:
1. Use the first row to make the entry below the pivot (12) in the second column 0:

$$
R_2 \rightarrow R_2 - \frac{-18}{12} R_1 = R_2 + \frac{3}{2} R_1
$$

### Resulting Upper Triangular Matrix:

$$
A' = 
\begin{bmatrix}
12 & 3 \\
0 & \frac{1}{2}
\end{bmatrix}
$$

### Determinant:

The determinant is the product of the diagonal elements:

$$
\text{Determinant of } A = 12 \cdot \frac{1}{2} = 6
$$


### Matrix \(B\)

$$
\mathbf{B} =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{pmatrix}
$$

### Row Operations:

1. Use the first row to make all entries below the pivot (1) in the first column 0:

$$
R_2 \rightarrow R_2 - 4R_1, \quad R_3 \rightarrow R_3 - 7R_1
$$
   
After this step:

   $$
   B' = 
   \begin{bmatrix}
   1 & 2 & 3 \\
   0 & -3 & -6 \\
   0 & -6 & -12
   \end{bmatrix}
   $$

2. Use the second row to make the entry below the pivot (-3) in the second column 0:

$$
R_3 \rightarrow R_3 - 2R_2
$$

After this step:

   $$
   B'' = 
   \begin{bmatrix}
   1 & 2 & 3 \\
   0 & -3 & -6 \\
   0 & 0 & 0
   \end{bmatrix}
   $$

### Determinant:

The determinant is the product of the diagonal elements:

$$
\text{Determinant of } B = 1 \cdot (-3) \cdot 0 = 0
$$

### Final Results:

- **Matrix \( A \):**

Upper Triangular Form:

$$
\begin{bmatrix}
12 & 3 \\
0 & \frac{1}{2}
\end{bmatrix}
$$

Determinant: \( 6 \)
  
- **Matrix \( B \):**

Upper Triangular Form:

$$
\begin{bmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & 0
\end{bmatrix}
$$

Determinant: \( 0 \)


## 5. Inverse of a Matrix from the formula
 
1. Find the inverse matrix for matrix
 
$$\mathbf{A}=\begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}$$
 
and verify if the result is correct.
 
2. Determine the rank of the matrix:
 
$$\mathbf{B} =
\begin{pmatrix}
4 & -3 & 7 \\
-1 & 6 & 3 \\
2 & 9 & 1
\end{pmatrix}$$
 
### Solutions
 
## Solution
 
### 1. Inverse of Matrix A
 
Given matrix:
 
$$
\mathbf{A} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$
 
#### Step 1: Find the determinant of matrix A
 
The determinant of a $3 \times 3$ matrix is given by the formula:
 
$$
\text{det}(\mathbf{A}) = a(ei - fh) - b(di - fg) + c(dh - eg)
$$
 
For matrix $\mathbf{A}$:
 
$$
\mathbf{A} = \begin{pmatrix}
a & b & c \\
d & e & f \\
g & h & i
\end{pmatrix} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$
 
Substituting the values:
 
$$
\text{det}(\mathbf{A}) = 2 \left( (1)(0) - (0)(2) \right) - 0 \left( (0)(0) - (0)(1) \right) + 1 \left( (0)(2) - (1)(1) \right)
$$
 
$$
\text{det}(\mathbf{A}) = 2(0 - 0) - 0(0 - 0) + 1(0 - 1) = 0 + 0 - 1 = -1
$$
 
#### Step 2: Find the inverse of matrix A
 
The inverse of a $3 \times 3$ matrix is given by:
 
$$
\mathbf{A}^{-1} = \frac{1}{\text{det}(\mathbf{A})} \cdot \text{adj}(\mathbf{A})
$$
 
Since the determinant is $-1$, we need to find the adjugate matrix of $\mathbf{A}$.
 
The adjugate matrix is the transpose of the cofactor matrix. The cofactor matrix is calculated by taking the determinant of $2 \times 2$ submatrices for each element.
 
Cofactors for $\mathbf{A}$ are calculated as follows:
 
$$C_{11} = \text{det}\begin{pmatrix} 1 & 0 \\ 2 & 0 \end{pmatrix} = (1)(0) - (0)(2) = 0$$

$$C_{12} = -\text{det}\begin{pmatrix} 0 & 0 \\ 1 & 0 \end{pmatrix} = -(0 - 0) = 0$$

$$C_{13} = \text{det}\begin{pmatrix} 0 & 1 \\ 1 & 2 \end{pmatrix} = (0)(2) - (1)(1) = -1$$

$$C_{21} = -\text{det}\begin{pmatrix} 0 & 1 \\ 2 & 0 \end{pmatrix} = -(0 - 2) = 2$$

$$C_{22} = \text{det}\begin{pmatrix} 2 & 1 \\ 1 & 0 \end{pmatrix} = (2)(0) - (1)(1) = -1$$

$$C_{23} = -\text{det}\begin{pmatrix} 2 & 0 \\ 1 & 2 \end{pmatrix} = -(4 - 0) = -4$$

$$C_{31} = \text{det}\begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix} = (0)(0) - (1)(1) = -1$$

$$C_{32} = -\text{det}\begin{pmatrix} 2 & 1 \\ 0 & 0 \end{pmatrix} = -(0 - 0) = 0$$

$$C_{33} = \text{det}\begin{pmatrix} 2 & 0 \\ 0 & 1 \end{pmatrix} = (2)(1) - (0)(0) = 2$$
 
Thus, the cofactor matrix is:
 
$$
\text{Cofactor}(\mathbf{A}) = \begin{pmatrix}
0 & 0 & -1 \\
2 & -1 & -4 \\
-1 & 0 & 2
\end{pmatrix}
$$
 
The adjugate matrix is the transpose of the cofactor matrix:
 
$$
\text{adj}(\mathbf{A}) = \begin{pmatrix}
0 & 2 & -1 \\
0 & -1 & 0 \\
-1 & -4 & 2
\end{pmatrix}
$$
 
Now, compute the inverse:
 
$$
\mathbf{A}^{-1} = \frac{1}{-1} \cdot \begin{pmatrix}
0 & 2 & -1 \\
0 & -1 & 0 \\
-1 & -4 & 2
\end{pmatrix} = \begin{pmatrix}
0 & -2 & 1 \\
0 & 1 & 0 \\
1 & 4 & -2
\end{pmatrix}
$$
 
#### Step 3: Verify the result
 
To verify, we multiply $\mathbf{A}$ and $\mathbf{A}^{-1}$:
 
$$
\mathbf{A} \cdot \mathbf{A}^{-1} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix} \cdot \begin{pmatrix}
0 & -2 & 1 \\
0 & 1 & 0 \\
1 & 4 & -2
\end{pmatrix}
$$
 
Performing the matrix multiplication:
 
$$
= \begin{pmatrix}
(2)(0) + (0)(0) + (1)(1) & (2)(-2) + (0)(1) + (1)(4) & (2)(1) + (0)(0) + (1)(-2) \\
(0)(0) + (1)(0) + (0)(1) & (0)(-2) + (1)(1) + (0)(4) & (0)(1) + (1)(0) + (0)(-2) \\
(1)(0) + (2)(0) + (0)(1) & (1)(-2) + (2)(1) + (0)(4) & (1)(1) + (2)(0) + (0)(-2)
\end{pmatrix}
$$
 
$$
= \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
$$
 
Thus, $\mathbf{A} \cdot \mathbf{A}^{-1} = \mathbf{I}$, confirming the inverse is correct.
 
### 2. Rank of Matrix B
 
Given matrix:
 
$$
\mathbf{B} = \begin{pmatrix}
4 & -3 & 7 \\
-1 & 6 & 3 \\
2 & 9 & 1
\end{pmatrix}
$$
 
#### Step 1: Perform row reduction
 
We can apply Gaussian elimination to find the rank.
 
1. First, swap rows 1 and 2 to simplify calculations:
 
$$
\mathbf{B} = \begin{pmatrix}
-1 & 6 & 3 \\
4 & -3 & 7 \\
2 & 9 & 1
\end{pmatrix}
$$
 
2. Add $4$ times the first row to the second row:
 
$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 21 & 31 \\
2 & 9 & 1
\end{pmatrix}
$$
 
3. Subtract $2$ times the first row from the third row:
 
$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 21 & 31 \\
0 & -3 & -5
\end{pmatrix}
$$
 
4. Multiply the second row by $\frac{1}{21}$:
 
$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 1 & \frac{31}{21} \\
0 & -3 & -5
\end{pmatrix}
$$
 
5. Add $3$ times the second row to the third row:
 
$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 1 & \frac{31}{21} \\
0 & 0 & \frac{2}{7}
\end{pmatrix}
$$
 
At this point, we have three non-zero rows, so the rank of matrix $\mathbf{B}$ is 3.
 
Thus, the rank of $\mathbf{B}$ is 3.
 

## 6. Inverse of a Matrix using the Gauss Method


The **Gauss Method** involves the following steps to find the inverse of a matrix:
1. Augment the given matrix \( M \) with the identity matrix of the same dimension.
2. Use row operations to transform the augmented matrix into reduced row-echelon form (RREF), such that the left side becomes the identity matrix.
3. The right side of the augmented matrix becomes the inverse matrix \( M^{-1} \).

---

### 1. Matrix \( A \)

Matrix \( A \):

$$
A =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
$$

#### Steps:

1. Augment \( A \) with the identity matrix:

$$
\left[
\begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
3 & 4 & 0 & 1
\end{array}
\right]
$$

2. Apply row operations:

   - \( R_2 \to R_2 - 3R_1 \):

$$
\left[
\begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
0 & -2 & -3 & 1
\end{array}
\right]
$$

   - \( R_2 \to \frac{R_2}{-2} \):

$$
\left[
\begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
0 & 1 & \frac{3}{2} & -\frac{1}{2}
\end{array}
\right]
$$

   - \( R_1 \to R_1 - 2R_2 \):

$$
\left[
\begin{array}{cc|cc}
1 & 0 & -2 & 1 \\
0 & 1 & \frac{3}{2} & -\frac{1}{2}
\end{array}
\right]
$$

The right side is the inverse of \( A \):

$$
A^{-1} =
\begin{pmatrix}
-2 & 1 \\
\frac{3}{2} & -\frac{1}{2}
\end{pmatrix}
$$

---

### 2. Matrix \( B \)

Matrix \( B \):

$$
B =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 1 \\
2 & 3 & 2
\end{pmatrix}
$$

#### Steps:

1. Augment \( B \) with the identity matrix:

$$
\left[
\begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
4 & 5 & 1 & 0 & 1 & 0 \\
2 & 3 & 2 & 0 & 0 & 1
\end{array}
\right]
$$

2. Use row operations to transform the left side into the identity matrix. After performing the steps (detailed calculations omitted for brevity):

$$
\left[
\begin{array}{ccc|ccc}
1 & 0 & 0 & -1 & \frac{4}{3} & -\frac{1}{3} \\
0 & 1 & 0 & \frac{2}{3} & -\frac{5}{3} & \frac{2}{3} \\
0 & 0 & 1 & \frac{2}{3} & -\frac{1}{3} & \frac{1}{3}
\end{array}
\right]
$$

The right side is the inverse of \( B \):

$$
B^{-1} =
\begin{pmatrix}
-1 & \frac{4}{3} & -\frac{1}{3} \\
\frac{2}{3} & -\frac{5}{3} & \frac{2}{3} \\
\frac{2}{3} & -\frac{1}{3} & \frac{1}{3}
\end{pmatrix}
$$

---

### 3. Matrix \( C \)

Matrix \( C \):

$$
C =
\begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}
$$

#### Steps:

1. Augment \( C \) with the identity matrix:

$$
\left[
\begin{array}{ccc|ccc}
0 & 0 & 1 & 1 & 0 & 0 \\
0 & 1 & 0 & 0 & 1 & 0 \\
1 & 0 & 0 & 0 & 0 & 1
\end{array}
\right]
$$

2. Use row operations to transform the left side into the identity matrix:

   - Swap \( R_1 \) and \( R_3 \):

$$
\left[
\begin{array}{ccc|ccc}
1 & 0 & 0 & 0 & 0 & 1 \\
0 & 1 & 0 & 0 & 1 & 0 \\
0 & 0 & 1 & 1 & 0 & 0
\end{array}
\right]
$$

The right side is the inverse of \( C \):

$$
C^{-1} =
\begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}
$$

---

### Final Results

1. \( A^{-1} \):

$$
\begin{pmatrix}
-2 & 1 \\
\frac{3}{2} & -\frac{1}{2}
\end{pmatrix}
$$

2. \( B^{-1} \):

$$
\begin{pmatrix}
-1 & \frac{4}{3} & -\frac{1}{3} \\
\frac{2}{3} & -\frac{5}{3} & \frac{2}{3} \\
\frac{2}{3} & -\frac{1}{3} & \frac{1}{3}
\end{pmatrix}
$$

3. \( C^{-1} \):

$$
\begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}
$$
