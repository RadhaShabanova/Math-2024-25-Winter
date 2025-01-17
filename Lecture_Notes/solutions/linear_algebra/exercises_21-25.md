# 21. Derivatives

### 1. Derivatives of the given functions

1. **Function**: $y(x) = -3x + 3$  
   **Derivative**:  
   $$y'(x) = -3$$

2. **Function**: $y(x) = \pi x + \sin(1)$  
   **Derivative**: 
   $$y'(x) = \pi$$

3. **Function**: $y(x) = 4 + \sin(2)$  
   **Derivative**:  
   $$y'(x) = 0$$

4. **Function**: $y(x) = 2x^3 - 3x^2 + 8x - 9$  
   **Derivative**:  
   $$y'(x) = 6x^2 - 6x + 8$$

5. **Function**: $y(x) = 6x^{1/3}$  
   **Derivative**:  
   $$y'(x) = 2x^{-2/3}$$

6. **Function**: $y(x) = x$  
   **Derivative**:  
   $$y'(x) = 1$$

7. **Function**: $y(x) = \cos(x) + \sin(x)$  
   **Derivative**:  
   $$y'(x) = -\sin(x) + \cos(x)$$

8. **Function**: $y(x) = 2\sin(x)\cos(x)$  
   **Derivative**:  
   $$y'(x) = 2\cos^2(x) - 2\sin^2(x)$$

9. **Function**: $y(x) = x\sin(x)$  
   **Derivative**:  
   $$y'(x) = \sin(x) + x\cos(x)$$

10. **Function**: $y(x) = (x + 1)(x + 1)$  
    **Derivative**:  
    $$y'(x) = 2(x + 1)$$

11. **Function**: $y(x) = \frac{x}{x + 1}$  
    **Derivative**:  
    $$y'(x) = \frac{1}{(x + 1)^2}$$

12. **Function**: $y(x) = (x + 1)\exp(x)$  
    **Derivative**:  
    $$y'(x) = (x + 1)\exp(x) + \exp(x)$$

13. **Function**: $y(x) = \sin(x^2)$  
    **Derivative**:  
    $$y'(x) = 2x\cos(x^2)$$

14. **Function**: $y(x) = \exp(-2x)$ 
    **Derivative**:  
    $$y'(x) = -2\exp(-2x)$$

15. **Function**: $y(x) = \frac{1}{\sin(x + 1)}$  
    **Derivative**:  
    $$y'(x) = -\frac{\cos(x + 1)}{\sin^2(x + 1)}$$

16. **Function**: $y(x) = 2x + 1$  
    **Derivative**:  
    $$y'(x) = 2$$


### 2. Proof:

To prove:  

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \cot(x)
$$

1. **Start with the given function:**

$$
   y = \ln(\sin(x))
$$

2. **Apply the chain rule:**  
   The derivative of $\ln(u)$ with respect to $x$ is $\frac{1}{u} \cdot \frac{du}{dx}$.  
   Here, $u = \sin(x)$.

$$
   \frac{d}{dx} \left( \ln(\sin(x)) \right) = \frac{1}{\sin(x)} \cdot \frac{d}{dx} (\sin(x))
$$

3. **Differentiate $\sin(x)$:**  

$$
   \frac{d}{dx} (\sin(x)) = \cos(x)
$$

4. **Substitute back:** 

$$
   \frac{d}{dx} \left( \ln(\sin(x)) \right) = \frac{\cos(x)}{\sin(x)}
$$

5. **Simplify the result:**  

$$
   \frac{\cos(x)}{\sin(x)} = \cot(x)
$$

#### Conclusion:

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \cot(x)
$$

## 3.Verification:

To verify:  

$$
f(x) = \cos(x) \implies f''(x) = -f(x)
$$

1. **First derivative:**  
   Start with $f(x) = \cos(x)$ .  
   Differentiate once to find $f'(x)$ :  

$$
   f'(x) = \frac{d}{dx} \cos(x) = -\sin(x)
$$

2. **Second derivative:**  
   Differentiate $f'(x) = -\sin(x)$ :  

$$
f''(x) = \frac{d}{dx}(-\sin(x)) = -\cos(x)
$$

3. **Compare \( f''(x) \) and \( -f(x) \):**  
   From the result:  

$$
   f''(x) = -\cos(x)
$$  

   From \( f(x) \):  

$$
   -f(x) = -\cos(x)
$$

   Therefore:  

$$
   f''(x) = -f(x)
$$

#### Conclusion:

$$
f(x) = \cos(x) \implies f''(x) = -f(x)
$$

## 4. Using de l'Hospital's Rule to Evaluate Limits

#### 1. $\lim_{x \to 0} \frac{\sin(x)}{x}$

1. The given limit is:  

$$
   \lim_{x \to 0} \frac{\sin(x)}{x}
$$

   As $x \to 0$, both the numerator and denominator approach 0, creating an indeterminate form $\frac{0}{0}$. We apply de l'Hospital's Rule.

2. Differentiate the numerator and denominator:  

$$
   \frac{d}{dx}[\sin(x)] = \cos(x), \quad \frac{d}{dx}[x] = 1
$$

3. Rewrite the limit:  

$$
   \lim_{x \to 0} \frac{\sin(x)}{x} = \lim_{x \to 0} \frac{\cos(x)}{1}
$$

4. Evaluate the limit:  

$$
   \lim_{x \to 0} \cos(x) = 1
$$

   **Conclusion:**  

$$
   \lim_{x \to 0} \frac{\sin(x)}{x} = 1
$$

---

#### 2. $\lim_{x \to \infty} \frac{\ln(x)}{x}$

1. The given limit is:  

$$
   \lim_{x \to \infty} \frac{\ln(x)}{x}
$$

   As $x \to \infty$, both the numerator and denominator approach infinity, creating an indeterminate form $\frac{\infty}{\infty}$. We apply de l'Hospital's Rule.

2. Differentiate the numerator and denominator:  

$$
   \frac{d}{dx}[\ln(x)] = \frac{1}{x}, \quad \frac{d}{dx}[x] = 1
$$

3. Rewrite the limit:  

$$
   \lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1}
$$

4. Simplify and evaluate:  

$$
   \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x} = 0
$$

   **Conclusion:**  

$$
   \lim_{x \to \infty} \frac{\ln(x)}{x} = 0
$$

---

#### 3. $\lim_{x \to \infty} \frac{\exp(x)}{x}$

1. The given limit is:  

$$
   \lim_{x \to \infty} \frac{\exp(x)}{x}
$$

   As $x \to \infty$, both the numerator and denominator approach infinity, creating an indeterminate form $\frac{\infty}{\infty}$. We apply de l'Hospital's Rule.

2. Differentiate the numerator and denominator:  

$$
   \frac{d}{dx}[\exp(x)] = \exp(x), \quad \frac{d}{dx}[x] = 1
$$

3. Rewrite the limit:  

$$
   \lim_{x \to \infty} \frac{\exp(x)}{x} = \lim_{x \to \infty} \frac{\exp(x)}{1}
$$

4. Evaluate the limit:  

$$
   \lim_{x \to \infty} \exp(x) = \infty
$$

   **Conclusion:**  

$$
   \lim_{x \to \infty} \frac{\exp(x)}{x} = \infty
$$

## 5. Finding Velocity and Acceleration

The position of the particle is given by:  

$$
x(t) = 3t^2 - 6t + 1
$$

#### 1. **Velocity** (\( V(t) = x'(t) \))  

1. Differentiate $x(t)$ to find the velocity $V(t)$:  

$$
   V(t) = \frac{d}{dt} \left( 3t^2 - 6t + 1 \right)
$$

   Differentiate term by term:  

$$
   V(t) = 6t - 6
$$

2. Evaluate $V(t)$ at $t = 2$:  

$$
   V(2) = 6(2) - 6 = 12 - 6 = 6
$$

   **Conclusion:**  

$$
   V(2) = 6
$$

---

#### 2. **Acceleration** (\( a(t) = V'(t) = x''(t) \))  

1. Differentiate $V(t)$ to find the acceleration $a(t)$: 

$$
   a(t) = \frac{d}{dt} \left( 6t - 6 \right)
$$

   Differentiate term by term:  

$$
   a(t) = 6
$$

2. Since $a(t)$ is constant, the acceleration at $t = 2$ is:  

$$
   a(2) = 6
$$

   **Conclusion:**  

$$
   a(2) = 6
$$

---

### Final Results:
1. Velocity at $t = 2$:  

$$
   V(2) = 6
$$

2. Acceleration at $t = 2$:  

$$
   a(2) = 6
$$

# 22. Extremum

### 1. Maximizing Profit

The profit function is given as:  

$$
P(u) = -2u^2 + 50u - 300
$$

To maximize profit, find the critical points by setting the derivative $P'(u)$ to zero.

1. Compute the derivative:  

$$
   P'(u) = \frac{d}{du} \left( -2u^2 + 50u - 300 \right)
$$

   Differentiate term by term: 

$$
   P'(u) = -4u + 50
$$

2. Set $P'(u) = 0$ and solve for $u$:  

$$
   -4u + 50 = 0
$$

$$
   u = \frac{50}{4} = 12.5
$$

3. Verify that this is a maximum using the second derivative: 

$$
   P''(u) = \frac{d}{du}(-4u + 50) = -4
$$

   Since $P''(u) < 0$, $P(u)$ has a maximum at $u = 12.5$.

**Conclusion:**  
The number of units that maximizes profit is:  

$$
u = 12.5
$$

---

### 2. Maximizing the Area of a Rectangle

You have 10 meters of string, so the perimeter of the rectangle is:  

$$
2l + 2w = 10 \quad \implies \quad l + w = 5
$$

To maximize the area $A$, express it in terms of one variable.

1. Write the area as:  

$$
   A = l \cdot w
$$

2. Substitute $w = 5 - l$:  

$$
   A = l(5 - l) = 5l - l^2
$$

3. Maximize $A$ by finding the critical points of $A(l)$:  
   Compute the derivative: 

$$
   A'(l) = \frac{d}{dl} (5l - l^2) = 5 - 2l
$$

4. Set $A'(l) = 0$ and solve for $l$:  

$$
   5 - 2l = 0 \quad \implies \quad l = 2.5
$$

5. Find $w$ using $w = 5 - l$:  

$$
   w = 5 - 2.5 = 2.5
$$

**Conclusion:**  
The dimensions of the rectangle that maximize the area are: 

$$
l = 2.5 \, \text{m}, \, w = 2.5 \, \text{m}
$$

---

### 3. Extremum of $f(x) = x^2 + 3x - 5$

1. Compute the derivative:  

$$
   f'(x) = \frac{d}{dx} (x^2 + 3x - 5) = 2x + 3
$$

2. Set $f'(x) = 0$ and solve for $x$:  

$$
   2x + 3 = 0 \quad \implies \quad x = -\frac{3}{2}
$$

3. Verify the nature of the extremum using the second derivative:  

$$
   f''(x) = \frac{d}{dx}(2x + 3) = 2
$$

   Since $f''(x) > 0$, $f(x)$ has a minimum at $x = -\frac{3}{2}$.

4. Find the value of $f(x)$ at $x = -\frac{3}{2}$:  

$$
   f\left(-\frac{3}{2}\right) = \left(-\frac{3}{2}\right)^2 + 3\left(-\frac{3}{2}\right) - 5
$$

$$
   = \frac{9}{4} - \frac{9}{2} - 5 = \frac{9}{4} - \frac{18}{4} - \frac{20}{4} = -\frac{29}{4}
$$

**Conclusion:**  
The minimum value of $f(x)$ is: 

$$
f\left(-\frac{3}{2}\right) = -\frac{29}{4}
$$

---

### 4. Extremum of $f(x) = \frac{x^2 + 2x + 1}{x - 1}$

1. Compute the derivative using the quotient rule:  
   If $f(x) = \frac{g(x)}{h(x)}$, then:  

$$
   f'(x) = \frac{g'(x)h(x) - g(x)h'(x)}{[h(x)]^2}
$$

   Here, $g(x) = x^2 + 2x + 1$ and $h(x) = x - 1$.  
   Compute derivatives:  

$$
   g'(x) = 2x + 2, \quad h'(x) = 1
$$

2. Substitute into the quotient rule:  

$$
   f'(x) = \frac{(2x + 2)(x - 1) - (x^2 + 2x + 1)(1)}{(x - 1)^2}
$$

   Simplify the numerator: 

$$
   f'(x) = \frac{(2x^2 - 2x + 2x - 2) - (x^2 + 2x + 1)}{(x - 1)^2}
$$

$$
   f'(x) = \frac{2x^2 - 2 - x^2 - 2x - 1}{(x - 1)^2} = \frac{x^2 - 2x - 3}{(x - 1)^2}
$$

3. Set $f'(x) = 0$:  
   The numerator must be zero: 

$$
   x^2 - 2x - 3 = 0
$$

   Factorize:  

$$
   (x - 3)(x + 1) = 0
$$

$$
   x = 3 \, \text{or} \, x = -1
$$

4. Verify the nature of the extremum by examining the second derivative or the behavior of $f'(x)$.  

**Conclusion:**  
The function $f(x) = \frac{x^2 + 2x + 1}{x - 1}$ has critical points at:  

$$
x = 3 \, \text{and} \, x = -1
$$


# 23. Taylor Series

#### What is a Taylor Series?

The **Taylor series** is a way to represent a smooth function as an infinite sum of terms calculated from the values of its derivatives at a single point. It is a powerful mathematical tool that approximates a function by a polynomial, which becomes increasingly accurate as more terms are included.

---

#### Formula for the Taylor Series

The Taylor series of a function \(f(x)\) around a point \(a\) is given by:

$$
f(x) = f(a) + f'(a)(x - a) + \frac{f''(a)}{2!}(x - a)^2 + \frac{f'''(a)}{3!}(x - a)^3 + \cdots
$$

In summation notation, it can be written as:

$$
f(x) = \sum_{n=0}^\infty \frac{f^{(n)}(a)}{n!} (x - a)^n
$$

---

#### Explanation of Terms:

- \(f^{(n)}(a)\): The \(n\)-th derivative of \(f(x)\) evaluated at \(x = a\),
- \(n!\) (read as "n factorial"): The product of all positive integers from \(1\) to \(n\),
- \((x - a)^n\): The distance of \(x\) from the point \(a\), raised to the power of \(n\).

---

#### 1. Taylor Series for $f(x) = \cos(x)$ around $x = 0$ (up to 4th degree)
The Taylor series for $\cos(x)$ is given by:  

$$
\cos(x) = \sum_{n=0}^\infty \frac{(-1)^n}{(2n)!} x^{2n}
$$

For $n = 0, 1, 2$:  
- For $n = 0$: $\frac{(-1)^0}{(2 \cdot 0)!} x^{2 \cdot 0} = 1$  
- For $n = 1$: $\frac{(-1)^1}{(2 \cdot 1)!} x^{2 \cdot 1} = -\frac{x^2}{2}$  
- For $n = 2$: $\frac{(-1)^2}{(2 \cdot 2)!} x^{2 \cdot 2} = \frac{x^4}{24}$

Thus, the Taylor series is:  

$$
f(x) = \cos(x) \approx 1 - \frac{x^2}{2} + \frac{x^4}{24}
$$

---

#### 2. Taylor Series for $h(x) = \frac{1}{1-x}$ around $x = 0$ (up to 4th degree)
The Taylor series for $\frac{1}{1-x}$ is given by:  

$$
\frac{1}{1-x} = \sum_{n=0}^\infty x^n
$$

For $n = 0, 1, 2, 3$:  
- For $n = 0$: $x^0 = 1$
- For $n = 1$: $x^1 = x$  
- For $n = 2$: $x^2 = x^2$ 
- For $n = 3$: $x^3 = x^3$

Thus, the Taylor series is:  

$$
h(x) = \frac{1}{1-x} \approx 1 + x + x^2 + x^3
$$

---

#### 3. Taylor Series for $g(x) = \sin(x)$ around $x = \pi$ (up to 4th degree)
The Taylor series for $\sin(x)$ around $x = \pi$ is given by: 

$$
\sin(x) = \sum_{n=0}^\infty \frac{(-1)^n}{(2n+1)!} (x-\pi)^{2n+1}
$$

For $n = 0, 1, 2$:  
- For $n = 0$: $\frac{(-1)^0}{1!} (x-\pi)^1 = (x-\pi)$ 
- For $n = 1$: $\frac{(-1)^1}{3!} (x-\pi)^3 = -\frac{(x-\pi)^3}{6}$

Thus, the Taylor series is:  

$$
g(x) = \sin(x) \approx (x-\pi) - \frac{(x-\pi)^3}{6}
$$

---

#### 4. Tangent Line to $f(x) = e^{\sin(x)}$ at $x_0 = \pi$
The tangent line formula is:  

$$
y = f'(x_0)(x-x_0) + f(x_0)
$$

1. Compute $f(x)$ at $x_0 = \pi$: 

$$
   f(x) = e^{\sin(x)} \quad \implies \quad f(\pi) = e^{\sin(\pi)} = e^0 = 1
$$

2. Compute $f'(x)$:  
   Using the chain rule: 

$$
   f'(x) = e^{\sin(x)} \cdot \cos(x)
$$  

   At $x_0 = \pi$:  

$$
   f'(\pi) = e^{\sin(\pi)} \cdot \cos(\pi) = e^0 \cdot (-1) = -1
$$

3. Write the tangent line equation: 

$$
   y = f'(\pi)(x-\pi) + f(\pi)
$$

   Substitute $f'(\pi) = -1$ and $f(\pi) = 1$:  

$$
   y = -1(x-\pi) + 1
$$

   Simplify:  

$$
   y = -x + \pi + 1
$$


### Final Results:
- Taylor series for $f(x) = \cos(x)$:  

$$
  f(x) \approx 1 - \frac{x^2}{2} + \frac{x^4}{24}
$$

- Taylor series for $h(x) = \frac{1}{1-x}$:  

$$
  h(x) \approx 1 + x + x^2 + x^3
$$

- Taylor series for $g(x) = \sin(x)$:  

$$
  g(x) \approx (x-\pi) - \frac{(x-\pi)^3}{6}
$$

- Tangent line to $f(x) = e^{\sin(x)}$ at $x_0 = \pi$:  

$$
  y = -x + \pi + 1
$$

# 24. Integrals

### First, lets recall the Power Rule for Integration

The power rule for integration states that for any constant \(a\) and exponent \(n \neq -1\):

$$
\int a x^n \, dx = \frac{a x^{n+1}}{n+1} + C
$$

where:

- \(a\) is a constant multiplier,
- \(n\) is the exponent of \(x\),
- \(C\) is the constant of integration, which accounts for any constant that could have been present before differentiation.


### 1. Compute the following integrals:

#### a) $\int 1 \, dx$

The integral of 1 is:  

$$
\int 1 \, dx = x + C
$$

---

#### b) $\int (x^2 + 2) \, dx$

The integral of $x^2 + 2$ is:  

$$
\int (x^2 + 2) \, dx = \frac{x^3}{3} + 2x + C
$$

---

#### c) $\int 2 \sin(x) \, dx$

The integral of $2 \sin(x)$ is:  

$$
\int 2 \sin(x) \, dx = -2 \cos(x) + C
$$

---

#### d) $\int 3x \, dx$

The integral of $3x$ is:  

$$
\int 3x \, dx = \frac{3x^2}{2} + C
$$

---

#### e) $\int \frac{1}{x^2} \, dx$

The integral of $\frac{1}{x^2}$ is:  

$$
\int \frac{1}{x^2} \, dx = -\frac{1}{x} + C
$$

---

#### f) $\int \left( \frac{1}{3}x^4 - 5 \right) \, dx$

The integral of $\frac{1}{3}x^4 - 5$ is: 

$$
\int \left( \frac{1}{3}x^4 - 5 \right) \, dx = \frac{1}{15}x^5 - 5x + C
$$

---

#### g) $\int \left( \sin^2(x) + \cos^2(x) \right) \, dx$

Using the identity $\sin^2(x) + \cos^2(x) = 1$, we get:  

$$
\int \left( \sin^2(x) + \cos^2(x) \right) \, dx = \int 1 \, dx = x + C
$$

---

#### h) $\int \left( 5 \sin(x) + 3 e^x \right) \, dx$

The integral of $5 \sin(x) + 3 e^x$ is:  

$$
\int \left( 5 \sin(x) + 3 e^x \right) \, dx = -5 \cos(x) + 3 e^x + C
$$

---

#### i) $\int x^3 \, dx$

The integral of $x^3$ is: 

$$
\int x^3 \, dx = \frac{x^4}{4} + C
$$

---

#### j) $\int 10x \, dx$

The integral of $10x$ is:
 
$$
\int 10x \, dx = 5x^2 + C
$$

---

#### k) $\int \cos\left( \frac{5}{2}x + 3 \right) \, dx$

The integral of $\cos\left( \frac{5}{2}x + 3 \right)$ is: 

$$
\int \cos\left( \frac{5}{2}x + 3 \right) \, dx = \frac{2}{5} \sin\left( \frac{5}{2}x + 3 \right) + C
$$

---

#### l) $\int \cos(\ln(x)) x \, dx$

Using substitution, let $u = \ln(x)$, so $du = \frac{1}{x} dx$:

$$
\int \cos(\ln(x)) x \, dx = \int \cos(u) \, du = \sin(u) + C = \sin(\ln(x)) + C
$$

---

#### m) $\int x \ln(x) \, dx$

Using integration by parts, let $u = \ln(x)$, $dv = x \, dx$, then $du = \frac{1}{x} \, dx$, and $v = \frac{x^2}{2}$:

$$
\int x \ln(x) \, dx = \frac{x^2}{2} \ln(x) - \frac{x^2}{4} + C
$$

---

#### n) $\int x e^x \, dx$

Using integration by parts, let $u = x$, $dv = e^x \, dx$, then $du = dx$, and $v = e^x$:  

$$
\int x e^x \, dx = x e^x - e^x + C
$$

---

### 2. Calculate Integrals Over the Interval $([0, \pi]$

#### a) $\int_0^\pi \left( 2x + 1 \right) \, dx$

First, compute the integral:  

$$
\int_0^\pi \left( 2x + 1 \right) \, dx = \left[ x^2 + x \right]_0^\pi = \pi^2 + \pi - (0 + 0) = \pi^2 + \pi
$$

#### b) $\int_0^\pi x^2 \, dx$

Compute the integral:  

$$
\int_0^\pi x^2 \, dx = \left[ \frac{x^3}{3} \right]_0^\pi = \frac{\pi^3}{3} - 0 = \frac{\pi^3}{3}
$$

---

### 3. Calculate the Area of the Region Bounded by the Lines: $x = 1$, $x = 2$, $y = 0$, and $y = x^2 + 1$

The area is given by:  

$$
A = \int_1^2 (x^2 + 1) \, dx
$$

First, compute the integral:  

$$
\int_1^2 (x^2 + 1) \, dx = \left[ \frac{x^3}{3} + x \right]_1^2 = \left( \frac{2^3}{3} + 2 \right) - \left( \frac{1^3}{3} + 1 \right)
$$  

$$
A = \left( \frac{8}{3} + 2 \right) - \left( \frac{1}{3} + 1 \right) = \left( \frac{8}{3} + \frac{6}{3} \right) - \left( \frac{1}{3} + \frac{3}{3} \right) = \frac{14}{3} - \frac{4}{3} = \frac{10}{3}
$$

---

### 4. Calculate the Area Under the Sine Curve Over the Interval $[0, \pi]$

The area is given by: 

$$
A = \int_0^\pi \sin(x) \, dx
$$

Compute the integral: 

$$
\int_0^\pi \sin(x) \, dx = \left[ -\cos(x) \right]_0^\pi = -\cos(\pi) + \cos(0) = -(-1) + 1 = 2
$$

---

### 5. Calculate the Length of the Sine Curve Over the Interval $[0, \pi]$

The length of a curve is given by:  

$$
L = \int_0^\pi \sqrt{1 + (f'(x))^2} \, dx
$$

For $f(x) = \sin(x)$, we have $f'(x) = \cos(x)$, so the length is:  

$$
L = \int_0^\pi \sqrt{1 + \cos^2(x)} \, dx
$$

This integral cannot be expressed in elementary terms, so it is typically approximated numerically.

---

### 6. Find the Distance of the Moving Particle Between Time $t = 0$ and $t = 2$

The position function is $x(t) = 3t^2 - 6t + 1$.  
The distance traveled is given by the integral of the speed (the absolute value of the velocity):

1. Compute the velocity:  

$$  
   v(t) = \frac{d}{dt}(3t^2 - 6t + 1) = 6t - 6
$$

2. Compute the speed (absolute value of velocity):  

$$  
   |v(t)| = |6t - 6|
$$

3. Find the point where $v(t) = 0$:  

$$  
   6t - 6 = 0 \quad \implies \quad t = 1
$$

4. Break the distance traveled into intervals based on when the velocity changes sign:
   - For $t \in [0, 1]$, $v(t) = 6t - 6$ is negative, so $|v(t)| = -(6t - 6) = 6 - 6t$.
   - For $t \in [1, 2]$, $v(t) = 6t - 6$ is positive, so $|v(t)| = 6t - 6$.

5. Compute the distance traveled over $[0, 1]$:

$$  
   D_1 = \int_0^1 (6 - 6t) \, dt = \left[ 6t - 3t^2 \right]_0^1 = (6 - 3) - (0) = 3
$$

6. Compute the distance traveled over $[1, 2]$:

$$  
   D_2 = \int_1^2 (6t - 6) \, dt = \left[ 3t^2 - 6t \right]_1^2 = (12 - 12) - (3 - 6) = 0 - (-3) = 3
$$

7. Total distance traveled:

$$  
   D = D_1 + D_2 = 3 + 3 = 6
$$

Thus, the total distance traveled by the particle between $t = 0$ and $t = 2$ is 6 units.

# 25. Differencial equations

### 1. Solve the First-Order Ordinary Differential Equations:

#### a) $y'(x) = y$

We use the method of separation of variables:

$$
\frac{dy}{dx} = y
$$

Separating variables:

$$
\frac{dy}{y} = dx
$$

Now, integrate both sides:

$$
\int \frac{1}{y} \, dy = \int 1 \, dx
$$

$$
\ln |y| = x + C
$$

Exponentiating both sides:

$$
|y| = e^{x + C} = e^C e^x
$$

Let $C_1 = e^C$, so:

$$
y = C_1 e^x
$$

Thus, the solution is:

$$
y(x) = C_1 e^x
$$

#### b) $y'(x) = \frac{1}{2} y(x)$

We use the method of separation of variables:

$$
\frac{dy}{dx} = \frac{1}{2} y
$$

Separating variables:

$$
\frac{1}{y} \, dy = \frac{1}{2} \, dx
$$

Now, integrate both sides:

$$
\int \frac{1}{y} \, dy = \int \frac{1}{2} \, dx
$$

$$
\ln |y| = \frac{x}{2} + C
$$

Exponentiating both sides:

$$
|y| = e^{\frac{x}{2} + C} = e^C e^{\frac{x}{2}}
$$

Let $C_2 = e^C$, so:

$$
y(x) = C_2 e^{\frac{x}{2}}
$$

Thus, the solution is:

$$
y(x) = C_2 e^{\frac{x}{2}}
$$


### 2. Solve the First-Order Ordinary Differential Equations using the Method of Separation of Variables:

#### a) $\frac{dy}{dx} = x y$

We use the method of separation of variables:

$$
\frac{dy}{dx} = x y
$$

Separating variables:

$$
\frac{1}{y} \, dy = x \, dx
$$

Now, integrate both sides:

$$
\int \frac{1}{y} \, dy = \int x \, dx
$$

$$
\ln |y| = \frac{x^2}{2} + C
$$

Exponentiating both sides:

$$
|y| = e^{\frac{x^2}{2} + C} = e^C e^{\frac{x^2}{2}}
$$

Let $C_1 = e^C$, so:

$$
y(x) = C_1 e^{\frac{x^2}{2}}
$$

Thus, the solution is:

$$
y(x) = C_1 e^{\frac{x^2}{2}}
$$

#### b) $\frac{dy}{dx} = y x$

We use the method of separation of variables:

$$
\frac{dy}{dx} = y x
$$

Separating variables:

$$
\frac{1}{y} \, dy = x \, dx
$$

Now, integrate both sides:

$$
\int \frac{1}{y} \, dy = \int x \, dx
$$

$$
\ln |y| = \frac{x^2}{2} + C
$$

Exponentiating both sides:

$$
|y| = e^{\frac{x^2}{2} + C} = e^C e^{\frac{x^2}{2}}
$$

Let $C_2 = e^C$, so:

$$
y(x) = C_2 e^{\frac{x^2}{2}}
$$

Thus, the solution is:

$$
y(x) = C_2 e^{\frac{x^2}{2}}
$$

---

Thus, the general solution for both equations $\frac{dy}{dx} = x y$ and $\frac{dy}{dx} = y x$ is:

$$
y(x) = C e^{\frac{x^2}{2}}
$$

where $C$ is a constant of integration.

---

### 2. Solve the Second-Order Ordinary Differential Equations:

#### a) $y''(x) + y'(x) = 0$, with boundary conditions $y(0) = 2$ and $y'(0) = -1$

We first solve the homogeneous equation $y''(x) + y'(x) = 0$.

The characteristic equation is:

$$
r^2 + r = 0
$$

Factoring:

$$
r(r + 1) = 0
$$

Thus, $r = 0$ or $r = -1$. Therefore, the general solution is:

$$
y(x) = C_1 + C_2 e^{-x}
$$

Now, apply the initial conditions:

- $y(0) = 2$:

$$
C_1 + C_2 = 2
$$

- $y'(0) = -1$:

$$
y'(x) = -C_2 e^{-x}
$$

$$
y'(0) = -C_2 = -1 \quad \implies \quad C_2 = 1
$$

Substitute $C_2 = 1$ into $C_1 + C_2 = 2$:

$$
C_1 + 1 = 2 \quad \implies \quad C_1 = 1
$$

Thus, the solution is:

$$
y(x) = 1 + e^{-x}
$$

#### b) $y''(x) - y(x) = 0$, with boundary conditions $y(0) = 2$ and $y'(0) = 0$

We first solve the homogeneous equation $y''(x) - y(x) = 0$.

The characteristic equation is:

$$
r^2 - 1 = 0
$$

Factoring:

$$
(r - 1)(r + 1) = 0
$$

Thus, $r = 1$ or $r = -1$. Therefore, the general solution is:

$$
y(x) = C_1 e^x + C_2 e^{-x}
$$

Now, apply the initial conditions:

- $y(0) = 2$:

$$
C_1 + C_2 = 2
$$

- $y'(0) = 0$:

$$
y'(x) = C_1 e^x - C_2 e^{-x}
$$

$$
y'(0) = C_1 - C_2 = 0 \quad \implies \quad C_1 = C_2
$$

Substitute $C_1 = C_2$ into $C_1 + C_2 = 2$:

$$
2C_1 = 2 \quad \implies \quad C_1 = 1
$$

Thus, $C_2 = 1$, and the solution is:

$$
y(x) = e^x + e^{-x}
$$

---

#### c) $y''(x) = -\omega^2 y(x)$

The characteristic equation is:

$$
r^2 + \omega^2 = 0
$$

Thus, $r = \pm i\omega$, and the general solution is:

$$
y(x) = C_1 \cos(\omega x) + C_2 \sin(\omega x)
$$

This is the solution for the second-order differential equation.

---

### 3. Check if the Function $\psi(t, x) = A \cos(\omega t + kx)$ is a Solution of the Wave Equation

The wave equation is:

$$
\frac{\partial^2 \psi}{\partial t^2} - v^2 \frac{\partial^2 \psi}{\partial x^2} = 0
$$

First, compute the second derivatives of $\psi(t, x) = A \cos(\omega t + kx)$.

- The second derivative with respect to $t$:

$$
\frac{\partial^2 \psi}{\partial t^2} = -A \omega^2 \cos(\omega t + kx)
$$

- The second derivative with respect to $x$:

$$
\frac{\partial^2 \psi}{\partial x^2} = -A k^2 \cos(\omega t + kx)
$$

Substitute these into the wave equation:

$$
-A \omega^2 \cos(\omega t + kx) - v^2 (-A k^2 \cos(\omega t + kx)) = 0
$$

Simplifying:

$$
-A \cos(\omega t + kx) \left( \omega^2 - v^2 k^2 \right) = 0
$$

For this to hold, we need:

$$
\omega^2 = v^2 k^2
$$

Since $v = \frac{\omega}{k}$, this condition is satisfied, so $\psi(t, x) = A \cos(\omega t + kx)$ is indeed a solution of the wave equation.

---
