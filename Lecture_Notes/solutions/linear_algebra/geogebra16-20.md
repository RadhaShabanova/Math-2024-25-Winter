## 16. Equations of planes in space

#### 1. The plane passes through points A(1,2,3), B(3,4,5), and C(2,1,4). Find the equation of the plane.

![alt text](<Screenshot 2024-12-19 at 7.31.51 PM.png>)

#### 2. The plane passes through point A(1,2,3) and is parallel to the plane 2x+3y+4z=5. Find the equation of the plane.

The plane we are looking for must be parallel to the given plane 2x+3y+4z=5.

A parallel plane will have the same normal vector n=(2,3,4).


The general equation of a plane with normal vector (a,b,c) is ax+by+cz=d.


The plane passes through the point A(1,2,3).

Substituting x=1,y=2,z=3 into 2x+3y+4z=d, we solve for 2(1)+3(2)+4(3)=d⟹d=2+6+12=20.


Therefore, the equation of the plane is:
2x+3y+4z=20.

![alt text](<Screenshot 2024-12-19 at 7.39.37 PM.png>)

#### 3. The plane passes through point A(1,2,3) and is perpendicular to the normal vector n = [2,3,4]. Find the equation of the plane.


The plane passes through the point $A(1, 2, 3)$ .
The normal vector to the plane is $\mathbf{n} = [2, 3, 4]$ .

The general equation of a plane with a normal vector $\mathbf{n} = [a, b, c]$ is:

   $$
   a(x - x_0) + b(y - y_0) + c(z - z_0) = 0,
   $$

where $(x_0, y_0, z_0)$ is a point on the plane.

Substitute Values:
   - Normal vector: $a = 2, b = 3, c = 4$.
   - Point $A(1, 2, 3) $ : $ x_0 = 1, y_0 = 2, z_0 = 3$ .

   Substituting into the equation:

   $$
   2(x - 1) + 3(y - 2) + 4(z - 3) = 0.
   $$

Simplify the Equation:

Expand and simplify:

   $$
   2x - 2 + 3y - 6 + 4z - 12 = 0,
   $$

   $$
   2x + 3y + 4z - 20 = 0.
   $$

   The equation of the plane is:

   $$
   2x + 3y + 4z = 20.
   $$

![alt text](<Screenshot 2024-12-19 at 7.46.36 PM.png>)

#### 4. We have two planes 2x+3y+4z=5 and 3x+4y+2z=6. Find the line of intersection of these planes.

Solving the Two Plane Equations Simultaneously

Eliminate One Variable:
   - To eliminate $z$, align the coefficients of $z$ by multiplying:
     - Multiply Plane 1 by $2$m:

       $$
       4x + 6y + 8z = 10,
       $$

     - Multiply Plane 2 by $4$:

       $$
       12x + 16y + 8z = 24.
       $$

   - Subtract Plane 1 from Plane 2:

     $$
     (12x + 16y + 8z) - (4x + 6y + 8z) = 24 - 10,
     $$

     $$
     8x + 10y = 14.
     $$

   - Simplify:

     $$
     4x + 5y = 7. \quad \text{(Equation 3)}
     $$

Solve for $x$ in Terms of $y$ :

   - From Equation 3:

     $$
     x = \frac{7 - 5y}{4}.
     $$

Express $x$ and $y$ in Terms of $z$ :
   - Substitute $x = \frac{7 - 5y}{4}$ into Plane 1:

     $$
     2\left(\frac{7 - 5y}{4}\right) + 3y + 4z = 5,
     $$

     $$
     \frac{14 - 10y}{4} + 3y + 4z = 5.
     $$

   - Simplify:

     $$
     \frac{14 - 10y + 12y}{4} + 4z = 5,
     $$

     $$
     \frac{14 + 2y}{4} + 4z = 5,
     $$

     $$
     \frac{7 + y}{2} + 4z = 5.
     $$

   - Solve for $y$ in terms of $z$ :

     $$
     \frac{7 + y}{2} = 5 - 4z,
     $$

     $$
     y = 2(5 - 4z) - 7,
     $$

     $$
     y = 10 - 8z - 7,
     $$

     $$
     y = 3 - 8z.
     $$

   - Substitute $y = 3 - 8z$ into $x = \frac{7 - 5y}{4}$ :

     $$
     x = \frac{7 - 5(3 - 8z)}{4},
     $$

     $$
     x = \frac{7 - 15 + 40z}{4},
     $$

     $$
     x = \frac{-8 + 40z}{4},
     $$

     $$
     x = -2 + 10z.
     $$

Parametric Form of the Line:
   - Let $z = t$ (the parameter). Then:

     $$
     x = -2 + 10t, \quad y = 3 - 8t, \quad z = t.
     $$

   - The parametric equation of the line is:

     $$
     \mathbf{r}(t) = (-2, 3, 0) + t(10, -8, 1).
     $$

![alt text](<Screenshot 2024-12-19 at 8.04.06 PM.png>)

#### 5. Write the equation of the plane passing through point A(1,2,3) and parallel to vectors v1=[1,0,1] and v2=[0,1,-1].

1. The plane passes through the point $A(1, 2, 3)$ and is parallel to the vectors:

   $$
   \mathbf{v}_1 = [1, 0, 1], \quad \mathbf{v}_2 = [0, 1, -1].
   $$

2. The normal vector $\mathbf{n}$ of the plane is perpendicular to both $\mathbf{v}_1$ and $\mathbf{v}_2$, which we find using the cross product:

   $$
   \mathbf{n} = \mathbf{v}_1 \times \mathbf{v}_2.
   $$

   Compute the determinant:

   $$
   \mathbf{n} = \begin{vmatrix}
   \mathbf{i} & \mathbf{j} & \mathbf{k} \\
   1 & 0 & 1 \\
   0 & 1 & -1
   \end{vmatrix}
   = \mathbf{i}(0 \cdot -1 - 1 \cdot 1) - \mathbf{j}(1 \cdot -1 - 0 \cdot 0) + \mathbf{k}(1 \cdot 1 - 0 \cdot 0).
   $$

   Simplify:

   $$
   \mathbf{n} = \mathbf{i}(-1) - \mathbf{j}(-1) + \mathbf{k}(1),
   $$

   $$
   \mathbf{n} = [-1, 1, 1].
   $$

   The normal vector is:

   $$
   \mathbf{n} = [-1, 1, 1].
   $$

---

Writing the Equation of the Plane.

The general equation of a plane is:

$$
n_1(x - x_1) + n_2(y - y_1) + n_3(z - z_1) = 0,
$$

where:
- $(x_1, y_1, z_1)$ is a point on the plane,
- $\mathbf{n} = [n_1, n_2, n_3]$ is the normal vector.

Substitute:
- Point $A(1, 2, 3)$,
- Normal vector $\mathbf{n} = [-1, 1, 1]$,

$$
-1(x - 1) + 1(y - 2) + 1(z - 3) = 0.
$$

Simplify:

$$
-x + 1 + y - 2 + z - 3 = 0,
$$

$$
-x + y + z - 4 = 0.
$$

Rewriting:

$$
x - y - z + 4 = 0.
$$

Thus, the equation of the plane is:

$$
x - y - z + 4 = 0.
$$

![alt text](<Screenshot 2024-12-19 at 8.12.36 PM.png>)

#### 6. We have the plane 2x+3y+4z=5. Find an example of a plane parallel and perpendicular to it.

Plane Parallel to $2x + 3y + 4z = 5$
- Planes parallel to $2x + 3y + 4z = 5$ will have the same normal vector $\mathbf{n} = [2, 3, 4]$.
- The equation of a parallel plane is:

$$
2x + 3y + 4z = D
$$

  where $D$ is any constant. For example:

$$
2x + 3y + 4z = 10
$$

  This plane is parallel to the original plane.

Plane Perpendicular to $2x + 3y + 4z = 5$
- A perpendicular plane will have a normal vector that is orthogonal to the normal vector $\mathbf{n} = [2, 3, 4]$ of the original plane.
- To find a plane perpendicular to the original, we can choose any vector $\mathbf{n'}$ that satisfies $\mathbf{n} \cdot \mathbf{n'} = 0$.
- For example, choose $\mathbf{n'} = [1, -2, 1]$. The dot product $\mathbf{n} \cdot \mathbf{n'} = 2(1) + 3(-2) + 4(1) = 0 $ , so they are perpendicular.
- The equation of the perpendicular plane is:

  $$
  x - 2y + z = D
  $$

  Example of a perpendicular plane:

  $$
  x - 2y + z = 4
  $$

![alt text](<Screenshot 2024-12-19 at 8.19.05 PM.png>)

#### 7. We have the plane 2x+3y+4z=5 and point A(1,2,3) .Find the distance from point A to this plane.

Distance Formula:
The distance from a point $(x_1, y_1, z_1)$ to a plane $Ax + By + Cz + D = 0$ is given by:

$$
D = \frac{|Ax_1 + By_1 + Cz_1 + D|}{\sqrt{A^2 + B^2 + C^2}}
$$

### Applying the Formula:

For the plane $2x + 3y + 4z = 5$, rewrite as $2x + 3y + 4z - 5 = 0$, so $A = 2$, $B = 3$, $C = 4$, and $D = -5$.

For point $A(1, 2, 3)$, $x_1 = 1$, $y_1 = 2$, $z_1 = 3$ .

Substitute into the formula:

$$
D = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}} = \frac{|15|}{\sqrt{29}} = \frac{15}{\sqrt{29}}
$$

The distance is $\frac{15}{\sqrt{29}}$ .

![alt text](<Screenshot 2024-12-19 at 8.26.10 PM.png>)

