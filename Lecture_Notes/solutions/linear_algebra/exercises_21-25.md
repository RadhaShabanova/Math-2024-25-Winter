# 21. Derivatives

### 1. Derivatives of the given functions

1. **Function**: $y(x) = -3x + 3$  
   **Derivative**:  
   $$y'(x) = -3$$

2. **Function**: $y(x) = \pi x + \sin(1)$  
   **Derivative**: 

   $$ y'(x) = \pi $$

3. **Function**: \( y(x) = 4 + \sin(2) \)  
   **Derivative**:  
   $$ y'(x) = 0 $$

4. **Function**: \( y(x) = 2x^3 - 3x^2 + 8x - 9 \)  
   **Derivative**:  
   $$ y'(x) = 6x^2 - 6x + 8 $$

5. **Function**: \( y(x) = 6x^{1/3} \)  
   **Derivative**:  
   $$ y'(x) = 2x^{-2/3} $$

6. **Function**: \( y(x) = x \)  
   **Derivative**:  
   $$ y'(x) = 1 $$

7. **Function**: \( y(x) = \cos(x) + \sin(x) \)  
   **Derivative**:  
   $$ y'(x) = -\sin(x) + \cos(x) $$

8. **Function**: \( y(x) = 2\sin(x)\cos(x) \)  
   **Derivative**:  
   $$ y'(x) = 2\cos^2(x) - 2\sin^2(x) $$

9. **Function**: \( y(x) = x\sin(x) \)  
   **Derivative**:  
   $$ y'(x) = \sin(x) + x\cos(x) $$

10. **Function**: \( y(x) = (x + 1)(x + 1) \)  
    **Derivative**:  
    $$ y'(x) = 2(x + 1) $$

11. **Function**: \( y(x) = \frac{x}{x + 1} \)  
    **Derivative**:  
    $$ y'(x) = \frac{1}{(x + 1)^2} $$

12. **Function**: \( y(x) = (x + 1)\exp(x) \)  
    **Derivative**:  
    $$ y'(x) = (x + 1)\exp(x) + \exp(x) $$

13. **Function**: \( y(x) = \sin(x^2) \)  
    **Derivative**:  
    $$ y'(x) = 2x\cos(x^2) $$

14. **Function**: \( y(x) = \exp(-2x) \)  
    **Derivative**:  
    $$ y'(x) = -2\exp(-2x) $$

15. **Function**: \( y(x) = \frac{1}{\sin(x + 1)} \)  
    **Derivative**:  
    $$ y'(x) = -\frac{\cos(x + 1)}{\sin^2(x + 1)} $$

16. **Function**: \( y(x) = 2x + 1 \)  
    **Derivative**:  
    $$ y'(x) = 2 $$


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

   As \( x \to \infty \), both the numerator and denominator approach infinity, creating an indeterminate form \( \frac{\infty}{\infty} \). We apply de l'Hospital's Rule.

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

