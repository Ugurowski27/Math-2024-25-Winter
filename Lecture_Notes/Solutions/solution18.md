# Solutions18

## **18. Functions**

1. **Draw the functions and find their values at** $x = 2$ using GeoGebra:

   Functions:

   - $f(x) = x^2$

   - $g(x) = \sqrt{x}$

   - $h(x) = \frac{1}{x}$

   - $j(x) = \sin(x)$

   Value at $x = 2$:

   - $f(2) = 2^2 = 4$

   - $g(2) = \sqrt{2} \approx 1.41$

   - $h(2) = \frac{1}{2} = 0.5$

   - $j(2) = \sin(2) \approx 0.909$

2. **Composite Functions**  

   Let $f(x) = 3x - 1$ and $g(x) = \sqrt{x}$.  

   Find:  

   - $f(g(x)) = 3\sqrt{x} - 1$

   - $g(f(x)) = \sqrt{3x - 1}$

   - $f(f(x)) = 3(3x - 1) - 1 = 9x - 4$

   - $g(g(x)) = \sqrt{\sqrt{x}} = x^{1/4}$

3. **Check $f(g(x))$ and $g(f(x))$ for $f(x) = e^x$ and $g(x) = \ln(x)$**:  

   - $f(g(x)) = e^{\ln(x)} = x$  

   - $g(f(x)) = \ln(e^x) = x$

   **Observation**: These are **inverse functions** since they return $x$.

4. **Inverse of $f = \{(1,7), (2,9), (3,11)\}$**:  

   The inverse is:  

   $f^{-1} = \{(7,1), (9,2), (11,3)\}$.

5. **Find the inverse of $f(x) = x - 1$**:  

   To find $f^{-1}(x)$, solve:  

   $y = x - 1$  

   $x = y - 1$ → $y = x + 1$  

   So, $f^{-1}(x) = x + 1$.

---

## **19. Limits of Sequences**

1.  

   $$

   \lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n}  

   $$  

   Divide numerator and denominator by $n^2$:  

   $$

   \lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1 + 0}{2 - 0} = \frac{1}{2}

   $$

2.  

   $$

   \lim_{n \to \infty} \frac{(2n + 3)^3}{n^3 - 1}  

   $$  

   Expand the numerator:  

   $$

   (2n + 3)^3 = 8n^3 + 36n^2 + 54n + 27

   $$  

   Now,  

   $$

   \lim_{n \to \infty} \frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1} = \frac{8 + 0 + 0 + 0}{1 - 0} = 8

   $$

3. **Prove using the squeeze theorem**:  

   $$

   \lim_{n \to \infty} \frac{\sin(n)}{n}  

   $$  

   Since $-1 \leq \sin(n) \leq 1$,  

   $$

   -\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}

   $$  

   As $n \to \infty$, both bounds tend to 0, so by the squeeze theorem,  

   $$

   \lim_{n \to \infty} \frac{\sin(n)}{n} = 0

   $$

4.  

   $$

   a_n = \left(1 + \frac{1}{n}\right)^n  

   $$  

   This limit is well-known as $e$.  

   $$

   \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e

   $$

---

## **20. Limits of Real Functions**

1.  

   $$

   \lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}  

   $$  

   Divide numerator and denominator by $x^4$:  

   $$

   \lim_{x \to \infty} \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}} = 0

   $$

2.  

   $$

   \lim_{x \to 0} \frac{\sin(3x)}{2x + 1}  

   $$  

   Substitute $x = 0$:  

   $$

   \frac{\sin(0)}{2(0) + 1} = 0

   $$

3. **Asymptotes of** $f(x) = \frac{x^2 - 1}{x^2 + 1}$:  

   - Vertical asymptotes: None (denominator is never zero).  

   - Horizontal asymptote:  

     $$

     \lim_{x \to \infty} \frac{x^2 - 1}{x^2 + 1} = 1 

---

## **22. Integrals**

1.  

   $$

   \int x^2 \, dx = \frac{x^3}{3} + C

   $$

2.  

   $$

   \int_0^1 (3x^2 + 2x) \, dx  

   $$  

   First, integrate term-by-term:  

   $$

   \int_0^1 3x^2 \, dx = \left[ x^3 \right]_0^1 = 1  

   $$  

   $$

   \int_0^1 2x \, dx = \left[ x^2 \right]_0^1 = 1  

   $$  

   So,  

   $$

   \int_0^1 (3x^2 + 2x) \, dx = 1 + 1 = 2

   $$

3.  

   $$

   \int \frac{1}{x} \, dx = \ln |x| + C

   $$

4.  

   $$

   \int e^{2x} \, dx  

   $$  

   Let \( u = 2x \), so \( du = 2dx \).  

   $$

   \int e^{2x} \, dx = \frac{1}{2} e^{2x} + C

   $$

5. **Find the area under the curve** \( y = x^2 \) from \( x = 1 \) to \( x = 3 \):  

   $$

   \int_1^3 x^2 \, dx = \left[ \frac{x^3}{3} \right]_1^3  

   $$  

   $$

   = \frac{3^3}{3} - \frac{1^3}{3} = \frac{27}{3} - \frac{1}{3} = \frac{26}{3}

   $$

6. **Solve**:  

   $$

   \int_0^\pi \sin(x) \, dx  

   $$  

   The integral of \(\sin(x)\) is \(-\cos(x)\):  

   $$

   \left[ -\cos(x) \right]_0^\pi = -\cos(\pi) + \cos(0) = -(-1) + 1 = 2

   $$

7. **Evaluate**:  

   $$

   \int_0^1 x e^x \, dx  

   $$  

   Use **integration by parts**:  

   Let \( u = x \), \( dv = e^x dx \).  

   Then, \( du = dx \) and \( v = e^x \).  

   $$

   \int x e^x \, dx = x e^x - \int e^x \, dx = x e^x - e^x + C  

   $$  

   Now,  

   $$

   \int_0^1 x e^x \, dx = \left[ e^x(x - 1) \right]_0^1  

   $$  

   $$

   = e(1 - 1) - (0 - 1) = 1

   $$ 