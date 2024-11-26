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

### Inverse of Matrix \( A \)

$$
\mathbf{A} = 
\begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$

The inverse of a \(3 \times 3\) matrix \( A \) is calculated using the formula:

$$
A^{-1} = \frac{1}{\det(A)} \cdot \text{Adj}(A)
$$

### Rank of Matrix \( B \)

$$
\mathbf{B} =
\begin{pmatrix}
4 & -3 & 7 \\
-1 & 6 & 3 \\
2 & 9 & 1
\end{pmatrix}
$$

1.Check the determinant of \( B \):

$$
\det(A) = 2 \cdot 
\begin{vmatrix}
1 & 0 \\
2 & 0
\end{vmatrix}
- 0 \cdot 
\begin{vmatrix}
0 & 1 \\
1 & 0
\end{vmatrix}
+ 1 \cdot 
\begin{vmatrix}
0 & 1 \\
1 & 2
\end{vmatrix}
$$

Compute the determinant. If \( \det(B) \neq 0 \), the rank of \( B \) is 3.

2.If \( \det(B) = 0 \):

Check \( 2 \times 2 \) submatrices of \( B \) to find the largest non-zero determinant. If all \( 2 \times 2 \) determinants are zero, rank is 1. Otherwise, rank is 2.

#### Result:

Compute and find:
- Rank of \( B \) = 3 if \( \det(B) \neq 0 \).






