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

### Steps:

1. **Augment the Matrix**:
   - Combine \( M \) with the identity matrix \( I \) of the same dimensions to form an augmented matrix $$[M | I]$$
   
   For example, if \( M \) is a 3 * 3 matrix:

$$
M = 
\begin{bmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{bmatrix}
\quad \longrightarrow \quad
\left[
\begin{array}{ccc|ccc}
a_{11} & a_{12} & a_{13} & 1 & 0 & 0 \\
a_{21} & a_{22} & a_{23} & 0 & 1 & 0 \\
a_{31} & a_{32} & a_{33} & 0 & 0 & 1
\end{array}
\right]
$$


2. **Transform the Left Side to the Identity Matrix**:
   - Apply **elementary row operations** to the augmented matrix. The goal is to convert the left-hand portion (original \( M \)) into the identity matrix \( I \).
   - Elementary row operations include:
     - Swapping two rows $$ R_i \leftrightarrow R_j $$
     - Multiplying a row by a non-zero scalar $$ k \cdot R_i $$
     - Adding or subtracting a multiple of one row to another $$ R_i \pm k \cdot R_j $$

3. **Interpret the Right Side as the Inverse**:
   - Once the left side becomes \( I \), the right side will be $$ M^{-1} $$

---

## Example:

Find the inverse of the matrix:

$$
M = \begin{bmatrix}
2 & 1 \\
5 & 3
\end{bmatrix}
$$

### Step 1: Augment with the Identity Matrix:
$$
\left[
\begin{array}{cc|cc}
2 & 1 & 1 & 0 \\
5 & 3 & 0 & 1
\end{array}
\right]
$$

### Step 2: Row Operations to Form \( I \) on the Left:

1. Make the top-left entry \( 1 \) by dividing the first row by 2:

$$
R_1 \rightarrow \frac{1}{2} R_1 \quad \Rightarrow \quad
\left[
\begin{array}{cc|cc}
1 & 0.5 & 0.5 & 0 \\
5 & 3 & 0 & 1
\end{array}
\right]
$$


2. Eliminate the first entry in the second row ( R_2 ):

$$
R_2 \rightarrow R_2 - 5 \cdot R_1 \quad \Rightarrow \quad
\left[
\begin{array}{cc|cc}
1 & 0.5 & 0.5 & 0 \\
0 & 0.5 & -2.5 & 1
\end{array}
\right]
$$

3. Make the pivot in the second row a \( 1 \) by dividing \( R_2 \) by 0.5:

$$
R_2 \rightarrow \frac{1}{0.5} R_2 \quad \Rightarrow \quad
\left[
\begin{array}{cc|cc}
1 & 0.5 & 0.5 & 0 \\
0 & 1 & -5 & 2
\end{array}
\right]
$$

4. Eliminate the second entry in the first row (\( R_1 \)):

$$
R_1 \rightarrow R_1 - 0.5 \cdot R_2 \quad \Rightarrow \quad
\left[
\begin{array}{cc|cc}
1 & 0 & 3 & -1 \\
0 & 1 & -5 & 2
\end{array}
\right]
$$

### Step 3: The Right Side is the Inverse:

$$
M^{-1} =
\begin{bmatrix}
3 & -1 \\
-5 & 2
\end{bmatrix}
$$

---

This method generalizes to any n * n  matrix, provided it is invertible (i.e., det(M) !=0). If \( M \) cannot be reduced to \( I \), the matrix is singular and does not have an inverse.

## 7. Linear Equations old school

Given: 

$$
3x - 2y = 5, \quad 2x + 3y = 7
$$

1. Solve for \( y \) in terms of \( x \) from the first equation:  

$$
y = \frac{3x - 5}{2}
$$

2. Substitute into the second equation:  

$$
2x + 3 \left(\frac{3x - 5}{2}\right) = 7
$$  

$$
13x = 29 \quad \implies \quad x = \frac{29}{13}
$$

3. Solve for \( y \): 

$$
y = \frac{3 \cdot \frac{29}{13} - 5}{2} = \frac{11}{13}
$$

### Solution:  

$$
x = \frac{29}{13}, \quad y = \frac{11}{13}
$$

---

Given:  

$$
2x - 3y = 10, \quad 4x + 5y = 20
$$

1. Solve for \( y \):  

$$
y = \frac{2x - 10}{3}
$$

2. Substitute into the second equation:  

$$
4x + 5 \left(\frac{2x - 10}{3}\right) = 20
$$  
$$
x = 5, \quad y = 0
$$

### Solution: 

$$
x = 5, \quad y = 0
$$

---

Given: 

$$
2x - y + z = 3, \quad x + 2y - z = 1, \quad 3x - y + 2z = 11
$$

1. Solve for \( z \): 

$$
z = 3 - 2x + y
$$

2. Substitute into the second and third equations:  

$$
3x + y = 4, \quad -x + y = 5
$$

3. Solve:  

$$
x = -\frac{1}{4}, \quad y = \frac{19}{4}, \quad z = \frac{45}{4}
$$

### Solution:  

$$
x = -\frac{1}{4}, \quad y = \frac{19}{4}, \quad z = \frac{45}{4}
$$


## 8. Linear equations by Cramer's Rule

![alt text](<Screenshot 2024-11-27 at 8.52.25 PM.png>)

$$
\begin{cases}
2x_1 - 3x_2 = 7 \\
3x_1 + 5x_2 = 2
\end{cases}
$$

Matrix form:

$$
A = \begin{bmatrix} 2 & -3 \\ 3 & 5 \end{bmatrix}, \quad \mathbf{x} = \begin{bmatrix} x_1 \\ x_2 \end{bmatrix}, \quad \mathbf{b} = \begin{bmatrix} 7 \\ 2 \end{bmatrix}
$$

Determinant of \( A \):

$$
\text{det}(A) = (2)(5) - (-3)(3) = 10 + 9 = 19
$$

For \( x_1 \), replace the first column of A with B:

$$
A_1 = \begin{bmatrix} 7 & -3 \\ 2 & 5 \end{bmatrix}, \quad \text{det}(A_1) = (7)(5) - (-3)(2) = 35 + 6 = 41
$$

For \( x_2 \), replace the second column of A with B:

$$
A_2 = \begin{bmatrix} 2 & 7 \\ 3 & 2 \end{bmatrix}, \quad \text{det}(A_2) = (2)(2) - (7)(3) = 4 - 21 = -17
$$

Now apply Cramer's Rule:

$$
x_1 = \frac{\text{det}(A_1)}{\text{det}(A)} = \frac{41}{19}, \quad x_2 = \frac{\text{det}(A_2)}{\text{det}(A)} = \frac{-17}{19}
$$

### Final Solution:

$$
x_1 = \frac{41}{19}, \quad x_2 = \frac{-17}{19}
$$

---

### 2. Solve the system:

$$
\begin{cases}
2x + y - z = 1 \\
x - y + 2z = 4 \\
3x - 2z = -1
\end{cases}
$$

Matrix form:

$$
A = \begin{bmatrix} 2 & 1 & -1 \\ 1 & -1 & 2 \\ 3 & 0 & -2 \end{bmatrix}, \quad \mathbf{x} = \begin{bmatrix} x \\ y \\ z \end{bmatrix}, \quad \mathbf{b} = \begin{bmatrix} 1 \\ 4 \\ -1 \end{bmatrix}
$$

Apply Cramer's Rule as shown in the first example. Calculate the determinants for \( x \), \( y \), and \( z \).

---

### 3. Solve the system:

$$
\begin{cases}
x + y + z - t = 2 \\
x - z + 2t = 6 \\
2x - 3y + t = 4 \\
3x + y + 3z - 4t = -2
\end{cases}
$$

Matrix form:

$$
A = \begin{bmatrix} 1 & 1 & 1 & -1 \\ 1 & 0 & -1 & 2 \\ 2 & -3 & 0 & 1 \\ 3 & 1 & 3 & -4 \end{bmatrix}, \quad \mathbf{x} = \begin{bmatrix} x \\ y \\ z \\ t \end{bmatrix}, \quad \mathbf{b} = \begin{bmatrix} 2 \\ 6 \\ 4 \\ -2 \end{bmatrix}
$$

Apply Cramer's Rule by finding the determinants for each variable.

---

### 4. Why can't the system be solved using Cramer's Rule?

Given system:

$$
\begin{cases}
x_1 + 2x_2 + 3x_3 = 3 \\
4x_1 + 5x_2 + 6x_3 = 2 \\
7x_1 + 8x_2 + 9x_3 = 1
\end{cases}
$$

The determinant of the coefficient matrix \( A \) is:

$$
\text{det}(A) = \begin{vmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{vmatrix} = 0
$$

Since the determinant is zero, the system has no unique solution and cannot be solved using Cramer's Rule.

## 9. Linear equations by Gauss Elimination

### 1. Solve the system:

$$
\begin{cases}
x + 2y - 2z = 4 \\
2x + y + z = 0 \\
3x + 2y + z = 1
\end{cases}
$$

The augmented matrix is:

$$
\left[
\begin{array}{ccc|c}
1 & 2 & -2 & 4 \\
2 & 1 & 1 & 0 \\
3 & 2 & 1 & 1
\end{array}
\right]
$$

Perform row operations to eliminate variables and solve for \( x \), \( y \), and \( z \). After Gaussian elimination:

Row 2: 

$$ R_2 \rightarrow R_2 - 2R_1 $$

Row 3: 

$$ R_3 \rightarrow R_3 - 3R_1 $$

Continue simplifying to get the values of \( x \), \( y \), and \( z \).

---

### 2. Solve the system:

$$
\begin{cases}
x + y + z - t = 2 \\
2x + y + z = 3 \\
-x + z - t = 0 \\
3x + 2y - z + 2t = -1
\end{cases}
$$

The augmented matrix is:

$$
\left[
\begin{array}{cccc|c}
1 & 1 & 1 & -1 & 2 \\
2 & 1 & 1 & 0 & 3 \\
-1 & 0 & 1 & -1 & 0 \\
3 & 2 & -1 & 2 & -1
\end{array}
\right]
$$

Apply Gaussian elimination to simplify this system and find \( x \), \( y \), \( z \), and \( t \).

---

### 3. Solve the system:

$$
\begin{cases}
x + y - z - t = 0 \\
2x + 3y - 2z + t = 4 \\
3x + 5z = 0 \\
-x + y - 3z + 2t = 3
\end{cases}
$$

The augmented matrix is:

$$
\left[
\begin{array}{cccc|c}
1 & 1 & -1 & -1 & 0 \\
2 & 3 & -2 & 1 & 4 \\
3 & 0 & 5 & 0 & 0 \\
-1 & 1 & -3 & 2 & 3
\end{array}
\right]
$$

Use row operations to simplify the system and solve for \( x \), \( y \), \( z \), and \( t \).

## 10. Linear equations by Matrix Inversion

![alt text](<Screenshot 2024-11-27 at 9.11.27 PM.png>)

### 1. Solve the system:

$$
\begin{cases}
x + 2y + 3z = 5 \\
2y + 3z = 4 \\
3z = 3
\end{cases}
$$

Write the system in matrix form:

$$
\begin{bmatrix}
1 & 2 & 3 \\
0 & 2 & 3 \\
0 & 0 & 3
\end{bmatrix}
\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}
=
\begin{bmatrix}
5 \\
4 \\
3
\end{bmatrix}
$$

Find the inverse of the coefficient matrix:

$$
A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 2 & 3 \\
0 & 0 & 3
\end{bmatrix}, \quad A^{-1} = \begin{bmatrix}
1 & -1 & 0 \\
0 & 1 & -1 \\
0 & 0 & \frac{1}{3}
\end{bmatrix}
$$

Multiply $$ A^{-1} $$ by the constant matrix to solve for $$ \begin{bmatrix} x \\ y \\ z \end{bmatrix} $$ =


$$
\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}
= A^{-1} \begin{bmatrix} 5 \\ 4 \\ 3 \end{bmatrix}
= \begin{bmatrix}
1 & -1 & 0 \\
0 & 1 & -1 \\
0 & 0 & \frac{1}{3}
\end{bmatrix}
\begin{bmatrix}
5 \\
4 \\
3
\end{bmatrix}
= \begin{bmatrix}
2 \\
1 \\
1
\end{bmatrix}
$$

### Final Solution:

$$
x = 2, \quad y = 1, \quad z = 1
$$

---

### 2. Solve the system:

$$
\begin{cases}
x_1 + 2x_2 + 3x_3 = 41 \\
4x_1 + 5x_2 + 6x_3 = 93 \\
7x_1 + 8x_2 + 9x_3 = 145
\end{cases}
$$

Write the system in matrix form:

$$
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}
\begin{bmatrix}
x_1 \\
x_2 \\
x_3
\end{bmatrix}
=
\begin{bmatrix}
41 \\
93 \\
145
\end{bmatrix}
$$

Find the inverse of the coefficient matrix \( A \). However, this matrix is **singular** (its determinant is 0), so it **does not have an inverse**. Hence, the system has no unique solution.

### Conclusion:
Since the determinant of \( A \) is 0, the system cannot be solved using matrix inversion.
