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
   - Multiply Plane 1 by $2$ :

$$
4x + 6y + 8z = 10
$$

- Multiply Plane 2 by $4$:

$$
12x + 16y + 8z = 24
$$

   - Subtract Plane 1 from Plane 2:

$$
(12x + 16y + 8z) - (4x + 6y + 8z) = 24 - 10
$$

$$
8x + 10y = 14
$$

   - Simplify:

$$
4x + 5y = 7 \quad \text{(Equation 3)}
$$

Solve for $x$ in Terms of $y$ :

   - From Equation 3:

$$
x = \frac{7 - 5y}{4}
$$

Express $x$ and $y$ in Terms of $z$ :
   - Substitute $x = \frac{7 - 5y}{4}$ into Plane 1:

$$
2\left(\frac{7 - 5y}{4}\right) + 3y + 4z = 5
$$

$$
\frac{14 - 10y}{4} + 3y + 4z = 5
$$

   - Simplify:

$$
\frac{14 - 10y + 12y}{4} + 4z = 5
$$

$$
\frac{14 + 2y}{4} + 4z = 5
$$

$$
\frac{7 + y}{2} + 4z = 5
$$

   - Solve for $y$ in terms of $z$ :

$$
\frac{7 + y}{2} = 5 - 4z
$$

$$
y = 2(5 - 4z) - 7
$$

$$
y = 10 - 8z - 7
$$

$$
y = 3 - 8z
$$

   - Substitute $y = 3 - 8z$ into $x = \frac{7 - 5y}{4}$ :

$$
x = \frac{7 - 5(3 - 8z)}{4}
$$

$$
x = \frac{7 - 15 + 40z}{4}
$$

$$
x = \frac{-8 + 40z}{4}
$$

$$
x = -2 + 10z
$$

Parametric Form of the Line:
   - Let $z = t$ (the parameter). Then:

$$
x = -2 + 10t, \quad y = 3 - 8t, \quad z = t
$$

   - The parametric equation of the line is:

$$
\mathbf{r}(t) = (-2, 3, 0) + t(10, -8, 1)
$$

![alt text](<Screenshot 2024-12-19 at 8.04.06 PM.png>)

#### 5. Write the equation of the plane passing through point A(1,2,3) and parallel to vectors v1=[1,0,1] and v2=[0,1,-1].

1. The plane passes through the point $A(1, 2, 3)$ and is parallel to the vectors:

$$
\mathbf{v}_1 = [1, 0, 1], \quad \mathbf{v}_2 = [0, 1, -1]
$$

2. The normal vector $\mathbf{n}$ of the plane is perpendicular to both $\mathbf{v}_1$ and $\mathbf{v}_2$, which we find using the cross product:

$$
\mathbf{n} = \mathbf{v}_1 \times \mathbf{v}_2
$$

   Compute the determinant:

$$
   \mathbf{n} = \begin{vmatrix}
   \mathbf{i} & \mathbf{j} & \mathbf{k} \\
   1 & 0 & 1 \\
   0 & 1 & -1
   \end{vmatrix}
   = \mathbf{i}(0 \cdot -1 - 1 \cdot 1) - \mathbf{j}(1 \cdot -1 - 0 \cdot 0) + \mathbf{k}(1 \cdot 1 - 0 \cdot 0)
$$

   Simplify:

$$
   \mathbf{n} = \mathbf{i}(-1) - \mathbf{j}(-1) + \mathbf{k}(1)
$$

$$
   \mathbf{n} = [-1, 1, 1]
$$

   The normal vector is:

$$
   \mathbf{n} = [-1, 1, 1]
$$

---

Writing the Equation of the Plane.

The general equation of a plane is:

$$
n_1(x - x_1) + n_2(y - y_1) + n_3(z - z_1) = 0
$$

where:
- $(x_1, y_1, z_1)$ is a point on the plane,
- $\mathbf{n} = [n_1, n_2, n_3]$ is the normal vector.

Substitute:
- Point $A(1, 2, 3)$,
- Normal vector $\mathbf{n} = [-1, 1, 1]$,

$$
-1(x - 1) + 1(y - 2) + 1(z - 3) = 0
$$

Simplify:

$$
-x + 1 + y - 2 + z - 3 = 0
$$

$$
-x + y + z - 4 = 0
$$

Rewriting:

$$
x - y - z + 4 = 0
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

Applying the Formula:

For the plane $2x + 3y + 4z = 5$, rewrite as $2x + 3y + 4z - 5 = 0$, so $A = 2$, $B = 3$, $C = 4$, and $D = -5$.

For point $A(1, 2, 3)$, $x_1 = 1$, $y_1 = 2$, $z_1 = 3$ .

Substitute into the formula:

$$
D = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}} = \frac{|15|}{\sqrt{29}} = \frac{15}{\sqrt{29}}
$$

The distance is $\frac{15}{\sqrt{29}}$ .

![alt text](<Screenshot 2024-12-19 at 8.26.10 PM.png>)

#### 8. The plane intersects the coordinate axes at points A(2,0,0), B(0,3,0) and C(0,0,4). Find the equation of the plane.

Equation of the Plane:
The equation of a plane passing through points $A$, $B$, and $C$ can be written as:

$$
\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1
$$

where $a$, $b$, and $c$) are the intercepts on the $x$-, $y$-, and $z$-axes, respectively.

From the given points:
- $a = 2$
- $b = 3$
- $c = 4$

Thus, the equation of the plane is:

$$
\frac{x}{2} + \frac{y}{3} + \frac{z}{4} = 1
$$

Standard Form:
Multiplying through by 12:

$$
6x + 4y + 3z = 12
$$

Final Answer:
The equation of the plane is:

$$
6x + 4y + 3z = 12
$$

![alt text](<Screenshot 2024-12-19 at 8.44.53 PM.png>)

#### 9. Calculate the angle between the plane x+y+z=1 and the plane x=0 (i.e., the yz plane).


Normal Vectors:
- Normal vector of Plane 1: $\mathbf{n_1} = [1, 1, 1]$
- Normal vector of Plane 2: $\mathbf{n_2} = [1, 0, 0]$

Formula for Angle Between Planes:

$$
\cos \theta = \frac{|\mathbf{n_1} \cdot \mathbf{n_2}|}{|\mathbf{n_1}| |\mathbf{n_2}|}
$$

Calculation:
1. Dot product: $\mathbf{n_1} \cdot \mathbf{n_2} = 1$
2. Magnitudes: $|\mathbf{n_1}| = \sqrt{3}, |\mathbf{n_2}| = 1$
3. Cosine of the angle: 

$$
\cos \theta = \frac{1}{\sqrt{3}}
$$

4. Angle:

$$
\theta = \cos^{-1} \left( \frac{1}{\sqrt{3}} \right) \approx 54.74^\circ
$$

Final Answer:
The angle between the planes is approximately $54.74^\circ$.

![alt text](<Screenshot 2024-12-19 at 8.47.30 PM.png>)

#### 10. Find the vector perpendicular to the plane x+y+z=1.

Perpendicular Vector:
The vector perpendicular to the plane is the normal vector, which is given by the coefficients of $x$, $y$, and $z$ in the plane equation.

Thus, the normal vector is:

$$
\mathbf{n} = [1, 1, 1]
$$

Final Answer:
The vector perpendicular to the plane $x + y + z = 1$ is $\mathbf{n} = [1, 1, 1]$.

![alt text](<Screenshot 2024-12-19 at 8.50.43 PM.png>)

## 17. Equations of second-order surfaces

#### 1. Write the equation of a sphere with center at point P=(1,2,3) and radius r=3.

Equation of the Sphere:
The general equation of a sphere is:

$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$

Substitute the values:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

Final Answer:
The equation of the sphere is:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

![alt text](<Screenshot 2024-12-19 at 8.54.09 PM.png>)

#### 2. Do the spheres with equations $x^2 + y^2 + z^2 = 1$ and $x^2 + y^2 + z^2 = 2$ have any common points?

Analysis:
Both spheres have the same center at the origin $(0, 0, 0)$, but different radii:
- Radius of Sphere 1: $r_1 = 1$
- Radius of Sphere 2: $r_2 = \sqrt{2} \approx 1.414$

Since their radii are different, the spheres **do not intersect**.

Final Answer:
The spheres do not have any common points.

![alt text](<Screenshot 2024-12-19 at 8.58.13 PM.png>)

#### 3. What curve in space is formed by the intersection of the sphere $x^2 + y^2 + z^2 = 1$ with the sphere $(x - 1)^2 + y^2 + z^2 = 1$? Find the equation of this curve.

Subtract the second sphere's equation from the first:

$$
x^2 + y^2 + z^2 - (x^2 - 2x + 1 + y^2 + z^2) = 0
$$

This simplifies to:

$$
-2x + 1 = 0 \quad \Rightarrow \quad x = \frac{1}{2}
$$

Substitute $x = \frac{1}{2}$ into the first sphere's equation:


$$
\left( \frac{1}{2} \right)^2 + y^2 + z^2 = 1 \quad \Rightarrow \quad y^2 + z^2 = \frac{3}{4}
$$

Final Answer:
The equation of the curve is:

$$
x = \frac{1}{2}, \quad y^2 + z^2 = \frac{3}{4}
$$

This represents a circle with radius $\frac{\sqrt{3}}{2}$ in the plane $x = \frac{1}{2}$.

![alt text](<Screenshot 2024-12-19 at 9.03.08 PM.png>)

#### 4. Write the equation of the tangent plane to the paraboloid $z = (x - 1)^2 + y^2 + 1$ at point $P(1, 0, 1)$.

Compute Partial Derivatives

$$
f_x = 2(x - 1), \quad f_y = 2y
$$

Evaluate at $P(1, 0, 1)$

$$
f_x(1, 0) = 0, \quad f_y(1, 0) = 0
$$

The equation of the tangent plane is:

$$
z = 1
$$

Final Answer:
The equation of the tangent plane is $z = 1$.

![alt text](<Screenshot 2024-12-19 at 9.05.54 PM.png>)

## 18. Functions

#### 1. Draw in a single Geogebra notebook the following functions: 
- $f(x) = x^2$
- $g(x) = x$
- $h(x) = \frac{1}{x}$
- $j(x) = \sin(x)$

Find value of all the above functions at $x = 2$.

- $f(2) = 2^2 = 4$
- $g(2) = 2$
- $h(2) = \frac{1}{2} = 0.5$
- $j(2) = \sin(2) \approx 0.909$

Final Values at $ x = 2$:
- $f(2) = 4$
- $g(2) = 2$
- $h(2) = 0.5$
- $j(2) \approx 0.909$

![alt text](<Screenshot 2024-12-19 at 9.11.26 PM.png>)

#### 2. Let $f(x) = 3x - 1$ and $g(x) = x$. Find: f(g(x)), g(f(x)), f(f(x)), g(g(x)).Visualize functions in a single Geogebra notebook.

Computations:

1. $f(g(x)) = f(x) = 3x - 1$
2. $g(f(x)) = g(3x - 1) = 3x - 1$
3. $f(f(x)) = f(3x - 1) = 9x - 4$
4. $g(g(x)) = g(x) = x$

Final Answers:
- $f(g(x)) = 3x - 1$
- $g(f(x)) = 3x - 1$
- $f(f(x)) = 9x - 4$
- $g(g(x)) = x$

![alt text](<Screenshot 2024-12-19 at 9.16.36 PM.png>)

#### 3. Let $f(x) = e^x$ and $g(x) = \ln(x)$ . Check: f(g(x)) and g(f(x)).What do you notice?

Computations:

1. $f(g(x)) = e^{\ln(x)} = x$
2. $g(f(x)) = \ln(e^x) = x$

Conclusion:
Both $f(g(x))$ and $g(f(x))$ equal $x$, demonstrating that $e^x$ and $\ln(x)$ are inverse functions of each other.

![alt text](<Screenshot 2024-12-19 at 9.20.13 PM.png>)

#### 4. We have function $f = \{(1, 7), (2, 9), (3, 11)\}$. Give inverse function $f^{-1}$.

To find the inverse function $f^{-1}$, we swap the coordinates in each pair:
- $(1, 7)$ becomes $(7, 1)$
- $(2, 9)$ becomes $(9, 2)$
- $(3, 11)$ becomes $(11, 3)$

Thus, the inverse function is:

$$
f^{-1} = \{(7, 1), (9, 2), (11, 3)\}
$$

![alt text](<Screenshot 2024-12-19 at 9.29.15 PM.png>)

#### 5. We have function $f = \{(1, 7), (2, 7), (3, 11)\}$. Give inverse function.

Checking for Inversibility:
For a function to have an inverse, it must be one-to-one. In this case:
- Both $(1, 7)$ and $(2, 7)$ have the same output $7$, so the function is not one-to-one.

Conclusion:
Since the function is not one-to-one, it does not have an inverse.

#### 6. We have function $f(x) = x - 1$.Give inverse function. Show both functions on the same Geogebra notebook.

To find the inverse, we:
1. Swap $x$ and $y$:
   
   $$
   x = y - 1
   $$

2. Solve for $y$:
   
   
   $$
   y = x + 1
   $$

Thus, the inverse function is:

$$
f^{-1}(x) = x + 1
$$

![alt text](<Screenshot 2024-12-19 at 9.34.34 PM.png>)

## 19. Limits of Sequences

#### 1. Calculate

First Limit:

$$
\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1}{2}
$$

Second Limit:

$$
\lim_{n \to \infty} \frac{2n + 3}{3n^3 - 1} = \lim_{n \to \infty} \frac{\frac{2}{n^2} + \frac{3}{n^3}}{3 - \frac{1}{n^3}} = 0
$$

#### 2. Prove using the squeeze theorem

Bound the function

We know that:

$$
-1 \leq \sin(n) \leq 1
$$

Thus:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

Take the limit of the bounds

$$
\lim_{n \to \infty} -\frac{1}{n} = 0 \quad \text{and} \quad \lim_{n \to \infty} \frac{1}{n} = 0
$$

Apply the Squeeze Theorem

Since:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

and both the lower and upper bounds approach 0, we conclude:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$

#### 3. FInd the limit of sequence.

We recognize that the sequence is closely related to the definition of the constant $e$:

$$
e = \lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n
$$

Thus, we conclude that:

$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e
$$

## 20. Limits of Real Functions

#### 1. Compute
We simplify the expression by dividing both the numerator and denominator by $x^4$:

$$
\frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}
$$

As $x \to \infty$, the terms $\frac{1}{x}$, $\frac{2}{x^2}$, and $\frac{3}{x}$ tend to 0, so the expression becomes:

$$
\frac{0 + 0}{1 - 0} = 0
$$

Thus, the limit is:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3} = 0
$$

#### 2. Find: $\lim_{x \to 0} \frac{\sin(3x)}{2x + 1}$

We evaluate the numerator and denominator at $x = 0$:

- The denominator $2x + 1$ at $x = 0$ gives $1$.
- The numerator $\sin(3x)$ at $x = 0$ gives $0$.

Therefore, the limit is:

$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1} = \frac{0}{1} = 0
$$

#### 3. Find
Asymptotes of $f(x) = \frac{x^2 - 1}{x^2 + 1}$:

- **Vertical Asymptotes**: There are no vertical asymptotes since the denominator $x^2 + 1$ never equals 0.
- **Horizontal Asymptotes**: As $x \to \infty$ or $x \to -\infty$, $f(x) \to 1$, so there is a horizontal asymptote at $y = 1$.

Asymptotes of $g(x) = \frac{\sin(x)}{x^2 + 1}$:

- **Vertical Asymptotes**: There are no vertical asymptotes since the denominator $x^2 + 1$ never equals 0.
- **Horizontal Asymptotes**: As $x \to \infty$ or $x \to -\infty$, $g(x) \to 0$, so there is a horizontal asymptote at $y = 0$.
