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

---

### Visualization in Geogebra:
1. **Define functions:**  
   - $f(x) = \cos(x)$, $h(x) = \frac{1}{1-x}$, $g(x) = \sin(x)$  
   - Include sliders $s$ for exploration.

2. **Tangent Line Setup:**  
   - Define $f(x) = e^{\sin(x)}$.  
   - Use the slider $s$ for $x_0$.  
   - Define the tangent line as $y = f'(s)(x-s) + f(s)$.  
   - Plot the point $P(s, f(s))$ to visualize the tangent line moving with $s$.

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
