# 11. Vectors I

### 1. Scaling vector $\mathbf{a}$ to unit length
The given vector is:

$$
\mathbf{a} = [3, 4]
$$

How the given vector looks like:

The length (magnitude) of $\mathbf{a}$ is calculated as:

$$
\|\mathbf{a}\| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5
$$

To make the length of $\mathbf{a}$ equal to 1, we multiply it by:

$$
k = \frac{1}{\|\mathbf{a}\|} = \frac{1}{5}
$$

Thus, the scaled vector (unit vector) is:

$$
\mathbf{a}_{\text{unit}} = k \cdot \mathbf{a} = \frac{1}{5} \cdot [3, 4] = \left[\frac{3}{5}, \frac{4}{5}\right]
$$

---

### 2. Length and unit vector of $\mathbf{b}$
The given vector is:

$$
\mathbf{b} = [1, 1]
$$

The length (magnitude) of $\mathbf{b}$ is:

$$
\|\mathbf{b}\| = \sqrt{1^2 + 1^2} = \sqrt{2}
$$

The unit vector of $\mathbf{b}$ is:

$$
\mathbf{b}_{\text{unit}} = \frac{\mathbf{b}}{\|\mathbf{b}\|} = \frac{1}{\sqrt{2}} \cdot [1, 1] = \left[\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right]
$$

---

### 3. Plotting vectors $\mathbf{b}$ and $\mathbf{b}_{\text{unit}}$

We will plot the vector $\mathbf{b} = [1, 1]$ and its unit vector 
$\mathbf{b}_{\text{unit}} = \left[\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right]$
 on a 2D plane.

---

### 4. Length and unit vector of $\mathbf{c}$
The given vector is:

$$
\mathbf{c} = [1, 2, 3]
$$

The length (magnitude) of $\mathbf{c}$ is:

$$
\|\mathbf{c}\| = \sqrt{1^2 + 2^2 + 3^2} = \sqrt{1 + 4 + 9} = \sqrt{14}
$$

The unit vector of $\mathbf{c}$ is:

$$
\mathbf{c}_{\text{unit}} = \frac{\mathbf{c}}{\|\mathbf{c}\|} = \frac{1}{\sqrt{14}} \cdot [1, 2, 3] = \left[\frac{1}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{3}{\sqrt{14}}\right]
$$

---

### 5. Cartesian coordinates of $\mathbf{v}$ in the given basis
The given vector is:

$$
\mathbf{v} = [2, 3, 4]
$$

![alt text](<Screenshot 2024-12-06 at 7.58.09 AM.png>)

The basis vectors are:

$$
\mathbf{b}_1 = [1, 0, 1], \quad \mathbf{b}_2 = [0, 1, 0], \quad \mathbf{b}_3 = [1, 0, -1]
$$

The coordinates of $\mathbf{v}$ in the given basis are found by solving:

$$
\mathbf{v} = x_1 \mathbf{b}_1 + x_2 \mathbf{b}_2 + x_3 \mathbf{b}_3
$$

![
](<Screenshot 2024-12-06 at 8.00.43 AM.png>)


Expanding this equation:

$$
[2, 3, 4] = x_1 [1, 0, 1] + x_2 [0, 1, 0] + x_3 [1, 0, -1]
$$

Equating components:

$$
2 = x_1 + x_3, \quad 3 = x_2, \quad 4 = x_1 - x_3
$$

From the second equation:

$$
x_2 = 3
$$

From the first and third equations:

$$
x_1 + x_3 = 2, \quad x_1 - x_3 = 4
$$

Adding these equations:

$$
2x_1 = 6 \implies x_1 = 3
$$

Subtracting these equations:

$$
2x_3 = -2 \implies x_3 = -1
$$

Thus, the coordinates of $\mathbf{v}$ in the given basis are:

$$
(x_1, x_2, x_3) = (3, 3, -1)
$$

# Vectors II

### 1. Vector addition and plotting
Perform the addition of vectors:

$$
\mathbf{v_1} = [2, 1], \quad \mathbf{v_2} = [-1, 1]
$$

The sum of the vectors is:

$$
\mathbf{v_1} + \mathbf{v_2} = [2 - 1, 1 + 1] = [1, 2]
$$

### Plot:
We will plot $\mathbf{v_1}$, $\mathbf{v_2}$, and their sum $\mathbf{v_1} + \mathbf{v_2}$ on a 2D graph.

![
](<Screenshot 2024-12-06 at 8.03.33 AM.png>)


---

### 2. Area of the triangle spanned by $\mathbf{v_1}$ and $\mathbf{v_2}$
The formula for the area of the triangle spanned by two vectors in 2D is:

$$
\text{Area} = \frac{1}{2} \left| \mathbf{v_1} \times \mathbf{v_2} \right|
$$

The cross product in 2D is given by:

$$
\mathbf{v_1} \times \mathbf{v_2} = \det\begin{bmatrix}
2 & 1 \\
-1 & 1
\end{bmatrix} = (2)(1) - (1)(-1) = 2 + 1 = 3
$$

Thus, the area is:

$$
\text{Area} = \frac{1}{2} \left| 3 \right| = \frac{3}{2}
$$

---

### 3. Volume of the parallelepiped spanned by $\mathbf{v_1}, \mathbf{v_2}, \mathbf{v_3}$
The given vectors are:

$$
\mathbf{v_1} = [2, 1], \quad \mathbf{v_2} = [-1, 1], \quad \mathbf{v_3} = [1, 2]
$$

Since these vectors are 2D and cannot span a 3D space, the volume is:

$$
\text{Volume} = 0
$$

---

### 4. Perpendicularity of $\mathbf{v_1}$ and $\mathbf{v_2}$
Two vectors are perpendicular if their dot product is zero:

$$
\mathbf{v_1} \cdot \mathbf{v_2} = (2)(-1) + (1)(1) = -2 + 1 = -1
$$

Since $\mathbf{v_1} \cdot \mathbf{v_2} \neq 0$, the vectors are **not perpendicular**.

---

### 5. Angle between vectors $\mathbf{v_4} = [4, 2, 1]$ and $\mathbf{v_5} = [1, 3, 2]$
The formula for the angle between two vectors is:

$$
\cos\theta = \frac{\mathbf{v_4} \cdot \mathbf{v_5}}{\|\mathbf{v_4}\| \|\mathbf{v_5}\|}
$$

The dot product is:

$$
\mathbf{v_4} \cdot \mathbf{v_5} = (4)(1) + (2)(3) + (1)(2) = 4 + 6 + 2 = 12
$$

The magnitudes are:

$$
\|\mathbf{v_4}\| = \sqrt{4^2 + 2^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}
$$

$$
\|\mathbf{v_5}\| = \sqrt{1^2 + 3^2 + 2^2} = \sqrt{1 + 9 + 4} = \sqrt{14}
$$

Thus:

$$
\cos\theta = \frac{12}{\sqrt{21} \cdot \sqrt{14}} = \frac{12}{\sqrt{294}}
$$

The angle is:

$$
\theta = \cos^{-1}\left(\frac{12}{\sqrt{294}}\right)
$$

Converting to degrees, we compute:

$$
\theta = \text{degrees}\left(\cos^{-1}\left(\frac{12}{\sqrt{294}}\right)\right)
$$

---

### 6. Proof of vector identity
Given three-dimensional vectors:

$$
\mathbf{a} = [a_x, a_y, a_z], \quad \mathbf{b} = [b_x, b_y, b_z], \quad \mathbf{c} = [c_x, c_y, c_z]
$$

We aim to prove:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}
$$

### Step 1: Expand $\mathbf{b} \times \mathbf{c}$
The cross product is:

$$
\mathbf{b} \times \mathbf{c} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
b_x & b_y & b_z \\
c_x & c_y & c_z
\end{vmatrix}
$$

### Step 2: Compute $\mathbf{a} \times (\mathbf{b} \times \mathbf{c})$
Substitute the result of $\mathbf{b} \times \mathbf{c}$ into:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c})
$$

Simplify to show:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}
$$

This completes the proof.

# Vectors III

### 1. Divide the line segment connecting points $A(-1, 2)$ and $B(3, -2)$ in the ratio 1:3
The formula for dividing a line segment in the ratio $m:n$ is:

$$
P = \left( \frac{m x_2 + n x_1}{m + n}, \frac{m y_2 + n y_1}{m + n} \right)
$$

where $A(x_1, y_1)$ and $B(x_2, y_2)$ are the endpoints, and $m$ and $n$ are the given ratios.

Here, $A(-1, 2)$, $B(3, -2)$, and the ratio is $1:3$, so $m = 1$ and $n = 3$.

Substitute into the formula:

$$
P = \left( \frac{1 \cdot 3 + 3 \cdot (-1)}{1 + 3}, \frac{1 \cdot (-2) + 3 \cdot 2}{1 + 3} \right)
$$

$$
P = \left( \frac{3 - 3}{4}, \frac{-2 + 6}{4} \right)
$$

$$
P = \left( \frac{0}{4}, \frac{4}{4} \right)
$$

$$
P = (0, 1)
$$

Thus, the point that divides the segment in the ratio 1:3 is $P(0, 1)$.

### Plot:
We will plot points $A(-1, 2)$, $B(3, -2)$, and the point $P(0, 1)$ on the graph.

---

### 2. Project vector $\mathbf{a} = (3, 4)$ onto the $OX$ and $OY$ axes
The projection of a vector $$\mathbf{a} = (a_x, a_y)$$ onto the $OX$ -axis is given by:

$$
\text{proj}_{OX}(\mathbf{a}) = (a_x, 0)
$$

And the projection onto the $OY$-axis is:

$$
\text{proj}_{OY}(\mathbf{a}) = (0, a_y)
$$

For $\mathbf{a} = (3, 4)$:

$$
\text{proj}_{OX}(\mathbf{a}) = (3, 0)
$$

$$
\text{proj}_{OY}(\mathbf{a}) = (0, 4)
$$

### Plot:
We will plot the vector $\mathbf{a} = (3, 4)$, its projection onto the $OX$ -axis $(3, 0)$, and its projection onto the $OY$ -axis $(0, 4)$.

---

### 3. Project vector $\mathbf{a} = (2, 3)$ onto vector $\mathbf{b} = (1, 1)$

The formula for the projection of vector $\mathbf{a}$ onto vector $\mathbf{b}$ is:

$$
\text{proj}_{\mathbf{b}}(\mathbf{a}) = \frac{\mathbf{a} \cdot \mathbf{b}}{\|\mathbf{b}\|^2} \mathbf{b}
$$

First, compute the dot product $\mathbf{a} \cdot \mathbf{b}$:

$$
\mathbf{a} \cdot \mathbf{b} = (2)(1) + (3)(1) = 2 + 3 = 5
$$

Next, compute the magnitude squared of $\mathbf{b}$:

$$
\|\mathbf{b}\|^2 = (1)^2 + (1)^2 = 1 + 1 = 2
$$

Thus, the projection is:

$$
\text{proj}_{\mathbf{b}}(\mathbf{a}) = \frac{5}{2} \cdot (1, 1) = \left( \frac{5}{2}, \frac{5}{2} \right)
$$

### Plot:
We will plot the vectors $\mathbf{a} = (2, 3)$, $\mathbf{b} = (1, 1)$, and the projection of $\mathbf{a}$ onto $\mathbf{b}$.

---

### 4. Project vector $\mathbf{b} = (1, 1)$ onto vector $\mathbf{a} = (2, 3)$

Using the same projection formula:

$$
\text{proj}_{\mathbf{a}}(\mathbf{b}) = \frac{\mathbf{b} \cdot \mathbf{a}}{\|\mathbf{a}\|^2} \mathbf{a}
$$

First, compute the dot product $\mathbf{b} \cdot \mathbf{a}$:

$$
\mathbf{b} \cdot \mathbf{a} = (1)(2) + (1)(3) = 2 + 3 = 5
$$

Next, compute the magnitude squared of $\mathbf{a}$:

$$
\|\mathbf{a}\|^2 = (2)^2 + (3)^2 = 4 + 9 = 13
$$

Thus, the projection is:

$$
\text{proj}_{\mathbf{a}}(\mathbf{b}) = \frac{5}{13} \cdot (2, 3) = \left( \frac{10}{13}, \frac{15}{13} \right)
$$

### Plot:
We will plot the vectors $\mathbf{a} = (2, 3)$, $\mathbf{b} = (1, 1)$, and the projection of $\mathbf{b}$ onto $\mathbf{a}$.

# 14. Equations of lines on a plane

### 1. Equation of the line passing through points $A(1, 2)$ and $B(3, 4)$
To find the equation of the line passing through two points $A(x_1, y_1)$ and $B(x_2, y_2)$, we first calculate the slope $m$ using the formula:

$$
m = \frac{y_2 - y_1}{x_2 - x_1}
$$

Substituting the coordinates of $A(1, 2)$ and $B(3, 4)$:

$$
m = \frac{4 - 2}{3 - 1} = \frac{2}{2} = 1
$$

Now that we have the slope, the equation of the line in point-slope form is:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = 1$ and $A(1, 2)$:

$$
y - 2 = 1(x - 1)
$$

Simplifying:

$$
y = x + 1
$$

Thus, the equation of the line is:

$$
y = x + 1
$$

---

### 2 Equation of the line passing through point $A(1, 2)$ and parallel to the line $y = 2x + 3$
The slope of the given line $y = 2x + 3$ is $m = 2$. Since the new line is parallel to this line, it will have the same slope.

Using the point-slope form of the equation:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = 2$ and $A(1, 2)$:

$$
y - 2 = 2(x - 1)
$$

Simplifying:

$$
y - 2 = 2x - 2
$$

$$
y = 2x
$$

Thus, the equation of the line is:

$$
y = 2x
$$

---

### 3. Equation of the line passing through point $A(1, 2)$ and perpendicular to the line $y = 2x + 3$
The slope of the given line $y = 2x + 3$ is $m = 2$. The slope of a line perpendicular to this will be the negative reciprocal:

$$
m_{\text{perpendicular}} = -\frac{1}{2}
$$

Using the point-slope form of the equation:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = -\frac{1}{2}$ and $A(1, 2)$:

$$
y - 2 = -\frac{1}{2}(x - 1)
$$

Simplifying:

$$
y - 2 = -\frac{1}{2}x + \frac{1}{2}
$$

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$

Thus, the equation of the line is:

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$

---

### 4. Intersection point and angle between the lines $y = 2x + 3$ and $y = 3x + 2$
To find the intersection point, set the equations equal to each other:

$$
2x + 3 = 3x + 2
$$

Solving for $x$:

$$
3 - 2 = 3x - 2x
$$

$$
x = 1
$$

Substitute $x = 1$ into one of the original equations (e.g., $y = 2x + 3$:

$$
y = 2(1) + 3 = 5
$$

Thus, the intersection point is $(1, 5)$.

To find the angle between the two lines, use the formula:

$$
\tan \theta = \left| \frac{m_1 - m_2}{1 + m_1 m_2} \right|
$$

For the lines $y = 2x + 3$ and $y = 3x + 2$, the slopes are $m_1 = 2$ and $m_2 = 3$. Substituting:

$$
\tan \theta = \left| \frac{2 - 3}{1 + 2 \cdot 3} \right| = \left| \frac{-1}{7} \right| = \frac{1}{7}
$$

Thus:

$$
\theta = \tan^{-1}\left( \frac{1}{7} \right)
$$

The angle is approximately:

$$
\theta \approx 8.13^\circ
$$

---

### 5 Equation of the line passing through point $A(1, 2)$ and parallel to vector $\mathbf{v} = [2, 3]$
The slope of the line parallel to the vector $\mathbf{v} = [2, 3]$ is:

$$
m = \frac{3}{2}
$$

Using the point-slope form of the equation:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = \frac{3}{2}$ and $A(1, 2)$:

$$
y - 2 = \frac{3}{2}(x - 1)
$$

Simplifying:

$$
y - 2 = \frac{3}{2}x - \frac{3}{2}
$$

$$
y = \frac{3}{2}x + \frac{1}{2}
$$

Thus, the equation of the line is:

$$
y = \frac{3}{2}x + \frac{1}{2}
$$

---

### 6. Example of a line perpendicular and parallel to the line $y = 2x + 3$
- **Parallel line:** The slope of the line $y = 2x + 3$ is $m = 2$. A parallel line will have the same slope. For example, the line passing through point $(1, 1)$ with slope 2:

$$
y - 1 = 2(x - 1)
$$

$$
y = 2x - 1
$$

- **Perpendicular line:** The slope of a line perpendicular to $y = 2x + 3$ is $m = -\frac{1}{2}$. For example, the line passing through point $(1, 1)$ with slope $-\frac{1}{2}$:

$$
y - 1 = -\frac{1}{2}(x - 1)
$$

$$
y = -\frac{1}{2}x + \frac{3}{2}
$$

---

### 7. Distance from point $A(1, 2)$ to the line $y = 2x + 3$
The formula for the distance from a point $(x_1, y_1)$ to a line $Ax + By + C = 0$ is:

$$
d = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}
$$

Rewriting the equation $y = 2x + 3$ in standard form:

$$
2x - y + 3 = 0
$$

Substitute $A = 2$, $B = -1$, $C = 3$, and $(x_1, y_1) = (1, 2)$:

$$
d = \frac{|2(1) - (2) + 3|}{\sqrt{2^2 + (-1)^2}} = \frac{|2 - 2 + 3|}{\sqrt{4 + 1}} = \frac{|3|}{\sqrt{5}} = \frac{3}{\sqrt{5}}
$$

Thus, the distance is:

$$
d = \frac{3}{\sqrt{5}} \approx 1.34
$$

---

### 8. Equation of the line passing through points $A(2, 0)$ and $B(0, 3)$
The slope of the line passing through $A(2, 0)$ and $B(0, 3)$ is:

$$
m = \frac{3 - 0}{0 - 2} = \frac{3}{-2} = -\frac{3}{2}
$$

Using the point-slope form with point $A(2, 0)$:

$$
y - 0 = -\frac{3}{2}(x - 2)
$$

Simplifying:

$$
y = -\frac{3}{2}x + 3
$$

Thus, the equation of the line is:

$$
y = -\frac{3}{2}x + 3
$$

---

### 9. Angle between the line $y = x + 3$ and the $OX$ -axis
The slope of the line $y = x + 3$ is $m = 1$. The angle $\theta$ between the line and the $OX$ -axis is:

$$
\tan \theta = m = 1
$$

Thus:

$$
\theta = \tan^{-1}(1) = 45^\circ
$$

---

### 10. Vector perpendicular to the line $x + y + 1 = 0$
The equation of the line is $x + y + 1 = 0$, which can be written in the form $Ax + By + C = 0$ with $A = 1$ and $B = 1$. A vector perpendicular to this line is $\mathbf{n} = [A, B] = [1, 1]$.
