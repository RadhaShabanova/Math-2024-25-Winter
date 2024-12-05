# 11. Vectors I

## 1. Scaling vector $ \mathbf{a} $ to unit length
The given vector is:

$$
\mathbf{a} = [3, 4]
$$

The length (magnitude) of $ \mathbf{a} $ is calculated as:

$$
\|\mathbf{a}\| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5
$$

To make the length of $ \mathbf{a} $ equal to 1, we multiply it by:

$$
k = \frac{1}{\|\mathbf{a}\|} = \frac{1}{5}
$$

Thus, the scaled vector (unit vector) is:

$$
\mathbf{a}_{\text{unit}} = k \cdot \mathbf{a} = \frac{1}{5} \cdot [3, 4] = \left[\frac{3}{5}, \frac{4}{5}\right]
$$

---

## 2. Length and unit vector of $ \mathbf{b} $$
The given vector is:

$$
\mathbf{b} = [1, 1]
$$

The length (magnitude) of $ \mathbf{b} $ is:

$$
\|\mathbf{b}\| = \sqrt{1^2 + 1^2} = \sqrt{2}
$$

The unit vector of $ \mathbf{b} $ is:

$$
\mathbf{b}_{\text{unit}} = \frac{\mathbf{b}}{\|\mathbf{b}\|} = \frac{1}{\sqrt{2}} \cdot [1, 1] = \left[\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right]
$$

---

## 3. Plotting vectors $ \mathbf{b} $ and $ \mathbf{b}_{\text{unit}}$
We will plot the vector $ \mathbf{b} = [1, 1] $ and its unit vector $ \mathbf{b}_{\text{unit}} = \left[\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right] $ on a 2D plane.

---

## 4. Length and unit vector of $ \mathbf{c} $
The given vector is:

$$
\mathbf{c} = [1, 2, 3]
$$

The length (magnitude) of $ \mathbf{c} $ is:

$$
\|\mathbf{c}\| = \sqrt{1^2 + 2^2 + 3^2} = \sqrt{1 + 4 + 9} = \sqrt{14}
$$

The unit vector of $ \mathbf{c} $ is:

$$
\mathbf{c}_{\text{unit}} = \frac{\mathbf{c}}{\|\mathbf{c}\|} = \frac{1}{\sqrt{14}} \cdot [1, 2, 3] = \left[\frac{1}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{3}{\sqrt{14}}\right]
$$

---

## 5. Cartesian coordinates of $ \mathbf{v} $ in the given basis
The given vector is:

$$
\mathbf{v} = [2, 3, 4]
$$

The basis vectors are:

$$
\mathbf{b}_1 = [1, 0, 1], \quad \mathbf{b}_2 = [0, 1, 0], \quad \mathbf{b}_3 = [1, 0, -1]
$$

The coordinates of $ \mathbf{v} $ in the given basis are found by solving:

$$
\mathbf{v} = x_1 \mathbf{b}_1 + x_2 \mathbf{b}_2 + x_3 \mathbf{b}_3
$$

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

Thus, the coordinates of $ \mathbf{v} $ in the given basis are:

$$
(x_1, x_2, x_3) = (3, 3, -1)
$$

# Vectors II

## 1. Vector addition and plotting
Perform the addition of vectors:

$$
\mathbf{v_1} = [2, 1], \quad \mathbf{v_2} = [-1, 1]
$$

The sum of the vectors is:

$$
\mathbf{v_1} + \mathbf{v_2} = [2 - 1, 1 + 1] = [1, 2]
$$

### Plot:
We will plot $ \mathbf{v_1} $, $ \mathbf{v_2} $, and their sum $ \mathbf{v_1} + \mathbf{v_2} $ on a 2D graph.

---

## 2. Area of the triangle spanned by $ \mathbf{v_1} $ and $ \mathbf{v_2} $
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

## 3. Volume of the parallelepiped spanned by $ \mathbf{v_1}, \mathbf{v_2}, \mathbf{v_3} $
The given vectors are:

$$
\mathbf{v_1} = [2, 1], \quad \mathbf{v_2} = [-1, 1], \quad \mathbf{v_3} = [1, 2]
$$

Since these vectors are 2D and cannot span a 3D space, the volume is:

$$
\text{Volume} = 0
$$

---

## 4. Perpendicularity of $ \mathbf{v_1} $ and $ \mathbf{v_2} $
Two vectors are perpendicular if their dot product is zero:

$$
\mathbf{v_1} \cdot \mathbf{v_2} = (2)(-1) + (1)(1) = -2 + 1 = -1
$$

Since $ \mathbf{v_1} \cdot \mathbf{v_2} \neq 0 $, the vectors are **not perpendicular**.

---

## 5. Angle between vectors $ \mathbf{v_4} = [4, 2, 1] $ and $ \mathbf{v_5} = [1, 3, 2] $
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

## 6. Proof of vector identity
Given three-dimensional vectors:

$$
\mathbf{a} = [a_x, a_y, a_z], \quad \mathbf{b} = [b_x, b_y, b_z], \quad \mathbf{c} = [c_x, c_y, c_z]
$$

We aim to prove:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}
$$

### Step 1: Expand $ \mathbf{b} \times \mathbf{c} $
The cross product is:

$$
\mathbf{b} \times \mathbf{c} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
b_x & b_y & b_z \\
c_x & c_y & c_z
\end{vmatrix}
$$

### Step 2: Compute $ \mathbf{a} \times (\mathbf{b} \times \mathbf{c}) $
Substitute the result of $ \mathbf{b} \times \mathbf{c} $ into:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c})
$$

Simplify to show:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}
$$
This completes the proof.

