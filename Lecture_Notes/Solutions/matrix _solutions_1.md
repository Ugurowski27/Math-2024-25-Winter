### **Question 23: Taylor Series**

1. Find the Taylor series for the following functions up to the 4th degree:

   - (a) $(f(x) = \cos(x)$) around $(x = 0$):  

     $$f(x) = \cos(x) \approx 1 - \frac{x^2}{2} + \frac{x^4}{24}$$  

   - (b) $(h(x) = \frac{1}{1-x}$) around $(x = 0$):  

     $$h(x) \approx 1 + x + x^2 + x^3 + x^4$$  

   - (c) $(g(x) = \sin(x)$) around $(x = 0$):  

     $$g(x) \approx x - \frac{x^3}{6}$$  

2. Find the tangent line to $(f(x) = \sin(x)$) at $(x_0 = \pi\):  

   Derivative of $(\sin(x)$) is $(\cos(x)$).  

   At $(x = \pi$),  

   $$\sin(\pi) = 0 \quad \text{and} \quad \cos(\pi) = -1.$$  

   Tangent line:  

   $$y = -1(x - \pi) + 0 = -x + \pi.$$

---

### **Question 24: Integrals**

1. Compute the following integrals:

   (a)  

   $$\int 1 \, dx = x + C$$  

   (b)  

   $$\int 2x \, dx = x^2 + C$$  

   (c)  

   $$\int 2x^2 \, dx = \frac{2x^3}{3} + C$$  

   (d)  

   $$\int x^4 \, dx = \frac{x^5}{5} + C$$  

   (e)  

   $$\int \left(\frac{x^4}{5} - 5\right) \, dx = \frac{x^5}{25} - 5x + C$$  

   (f)  

   $$\int (\sin^2(x) + \cos^2(x)) \, dx$$  

   Since $(\sin^2(x) + \cos^2(x) = 1$),  

   $$\int 1 \, dx = x + C$$  

   (g)  

   $$\int (\sin(x) + 3e^x) \, dx = \int \sin(x) \, dx + \int 3e^x \, dx$$  

   $$= -\cos(x) + 3e^x + C$$  

   (h)  

   $$\int \frac{1}{10}x \, dx = \frac{1}{10} \int x \, dx = \frac{1}{20}x^2 + C$$  

   (i)  

   $$\int \cos\left(\frac{x}{2} + 3\right) \, dx$$  

   Let $(u = \frac{x}{2} + 3$),  

   $$\int \cos(u) \frac{dx}{2} = 2\sin\left(\frac{x}{2} + 3\right) + C$$  

   (j)  

   $$\int e^{\ln(x)} \, dx$$  

   Since $(e^{\ln(x)} = x$),  

   $$\int x \, dx = \frac{x^2}{2} + C$$  

   (k)  

   $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$  

   (l)  

   $$\int a^x \, dx = \frac{a^x}{\ln(a)} + C$$  

2. **Calculate the area between** $(f(x) = 2x + 1$) and $(g(x) = x^2$) on $([0, 1]$):  

   $$\int_0^1 \left(2x + 1 - x^2\right) \, dx$$  

---

### **Question 25: Differential Equations**

1. Solve $(y' = y$):  

   $$y = Ce^x$$  

2. Solve $(y' = \frac{1}{y}$):  

   $$y \, dy = dx$$  

   $$\frac{y^2}{2} = x + C$$  

   Solution:  

   $$y = \sqrt{2x + C}$$ 