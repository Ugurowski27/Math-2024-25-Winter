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

## Question 24: Integral Solutions

### Question 1: Compute the following integrals

### (a) $\int 1 \, dx$

**Solution:**  

The integral of a constant is:  

$$\int 1 \, dx = x + C$$

**Answer:**  

$$x + C$$

---

### (b) $\int x^2 \, dx$

**Solution:**  

Apply the power rule:  

$$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$  

For $n = 2$:  

$$\int x^2 \, dx = \frac{x^3}{3} + C$$

**Answer:**  

$$\frac{x^3}{3} + C$$

---

### (c) $\int 2x \, dx$

**Solution:**  

Factor out the constant and apply the power rule:  

$$2 \int x \, dx = 2 \left(\frac{x^2}{2}\right) + C = x^2 + C$$

**Answer:**  

$$x^2 + C$$

---

### (d) $\int x^3 \, dx$

**Solution:**  

Apply the power rule:  

$$\int x^3 \, dx = \frac{x^4}{4} + C$$

**Answer:**  

$$\frac{x^4}{4} + C$$

---

### (e) $\int \frac{1}{x} \, dx$

**Solution:**  

The integral of $\frac{1}{x}$ is:  

$$\int \frac{1}{x} \, dx = \ln |x| + C$$

**Answer:**  

$$\ln |x| + C$$

---

### (f) $\int \left(x^4 - 5\right) \, dx$

**Solution:**  

Apply the power rule to each term:  

$$\int x^4 \, dx - \int 5 \, dx = \frac{x^5}{5} - 5x + C$$

**Answer:**  

$$\frac{x^5}{5} - 5x + C$$

---

### (g) $\int \left(\sin^2 x + \cos^2 x\right) \, dx$

**Solution:**  

Since $\sin^2 x + \cos^2 x = 1$,  

$$\int 1 \, dx = x + C$$

**Answer:**  

$$x + C$$

---

### (h) $\int \left(5\sin x + 3e^x\right) \, dx$

**Solution:**  

Integrate each term separately:  

$$5 \int \sin x \, dx + 3 \int e^x \, dx$$  

The integrals are:  

$$\int \sin x \, dx = -\cos x \quad \text{and} \quad \int e^x \, dx = e^x$$  

So,  

$$-5 \cos x + 3 e^x + C$$

**Answer:**  

$$-5 \cos x + 3 e^x + C$$

---

### (i) $\int \sqrt{10x} \, dx$

**Solution:**  

Rewrite the square root:  

$$\int \sqrt{10x} \, dx = \int \left(10x\right)^{1/2} \, dx$$  

Apply the power rule:  

$$\frac{10^{1/2}}{3/2} x^{3/2} + C = \frac{2\sqrt{10}}{3} x^{3/2} + C$$

**Answer:**  

$$\frac{2\sqrt{10}}{3} x^{3/2} + C$$

---

### (j) $\int \cos\left(\frac{\pi}{2}x + 3\right) \, dx$

**Solution:**  

The integral of cosine is:  

$$\int \cos(kx + c) \, dx = \frac{1}{k} \sin(kx + c) + C$$  

Here, $k = \frac{\pi}{2}$:  

$$\int \cos\left(\frac{\pi}{2}x + 3\right) \, dx = \frac{2}{\pi} \sin\left(\frac{\pi}{2}x + 3\right) + C$$

**Answer:**  

$$\frac{2}{\pi} \sin\left(\frac{\pi}{2}x + 3\right) + C$$

---

### (k) $\int \sinh x \, dx$

**Solution:**  

The integral of $\sinh x$ is:  

$$\int \sinh x \, dx = \cosh x + C$$

**Answer:**  

$$\cosh x + C$$

---

### (l) $\int e^{-x^2} \, dx$

**Solution:**  

The integral $\int e^{-x^2} \, dx$ does not have a closed-form elementary solution. It is expressed in terms of the error function:  

$$\int e^{-x^2} \, dx = \frac{\sqrt{\pi}}{2} \text{erf}(x) + C$$

**Answer:**  

$$\frac{\sqrt{\pi}}{2} \text{erf}(x) + C$$ 
---

### **Question 25: Differential Equations**



## Question 1: First-Order Ordinary Differential Equations

### (a) Solve $y'(x) = y$

**Step 1:**  

Rewrite the equation:  

$$\frac{dy}{dx} = y$$

**Step 2:**  

Separate variables:  

$$\frac{dy}{y} = dx$$

**Step 3:**  

Integrate both sides:  

$$\int \frac{1}{y} \, dy = \int 1 \, dx$$  

$$\ln |y| = x + C$$  

**Step 4:**  

Solve for $y$:  

$y(x) = e^{x + C} = Ae^x$, where $A = e^C$ is a constant.

**Final Answer:**  

$y(x) = Ae^x$

---

### (b) Solve $y'(x) = \frac{1}{2y(x)}$

**Step 1:**  

Rewrite the equation:  

$$\frac{dy}{dx} = \frac{1}{2y}$$

**Step 2:**  

Separate variables:  

$$2y \, dy = dx$$

**Step 3:**  

Integrate both sides:  

$$\int 2y \, dy = \int dx$$  

$$y^2 = x + C$$

**Step 4:**  

Solve for $y$:  

$$y(x) = \pm \sqrt{x + C}$$

**Final Answer:**  

$$y(x) = \pm \sqrt{x + C}$$

---

## Question 2: First-Order ODEs with Separation of Variables

### (a) Solve $\frac{dy}{dx} = \frac{x}{y}$

**Step 1:**  

Separate variables:  

$$y \, dy = x \, dx$$

**Step 2:**  

Integrate both sides:  

$$\int y \, dy = \int x \, dx$$  

$$\frac{y^2}{2} = \frac{x^2}{2} + C$$  

**Step 3:**  

Simplify:  

$$y^2 = x^2 + 2C$$

**Final Answer:**  

$$y(x) = \pm \sqrt{x^2 + 2C}$$

---

### (b) Solve $\frac{dy}{dx} = xy$

**Step 1:**  

Separate variables:  

$$\frac{dy}{y} = x \, dx$$

**Step 2:**  

Integrate both sides:  

$$\int \frac{1}{y} \, dy = \int x \, dx$$  

$$\ln |y| = \frac{x^2}{2} + C$$  

**Step 3:**  

Solve for $y$:  

$y(x) = Ae^{\frac{x^2}{2}}$, where $A = e^C$.

**Final Answer:**  

$$y(x) = Ae^{\frac{x^2}{2}}$$

---

### (c) Solve $\frac{dy}{dx} = xy$

(Identical to part **(b)** above).

---

## Question 3: Second-Order Ordinary Differential Equations

### (a) Solve $y''(x) + y'(x) = 0$  

**Boundary Conditions:** $y(0) = 2, \quad y'(0) = -1$

**Step 1:**  

Rewrite the characteristic equation:  

$$r^2 + r = 0$$ 

Factor:  

$$r(r + 1) = 0$$  

So, $r = 0$ or $r = -1$.

**Step 2:**  

The general solution is:  

$$y(x) = C_1 + C_2 e^{-x}$$

**Step 3:**  

Apply boundary conditions:  

1. $$y(0) = 2 \Rightarrow C_1 + C_2 = 2$$  

2. $$y'(x) = -C_2 e^{-x} \Rightarrow y'(0) = -C_2 = -1 \Rightarrow C_2 = 1$$  

So, $C_1 = 1$.

**Final Answer:**  

$$y(x) = 1 + e^{-x}$$

---

### (b) Solve $y''(x) - y(x) = 0$  

**Boundary Conditions:** $y(0) = 2, \quad y'(0) = 0$

**Step 1:**  

Solve the characteristic equation:  

$$r^2 - 1 = 0 \Rightarrow r = \pm 1$$

**Step 2:**  

The general solution is:  

$$y(x) = C_1 e^x + C_2 e^{-x}$$

**Step 3:**  

Apply boundary conditions:  

1. $$y(0) = 2 \Rightarrow C_1 + C_2 = 2$$  

2. $$y'(x) = C_1 e^x - C_2 e^{-x} \Rightarrow y'(0) = 0 \Rightarrow C_1 = C_2$$  

From these, $C_1 = C_2 = 1$.

**Final Answer:**  

$$y(x) = e^x + e^{-x}$$

---

### (c) Solve $\frac{d^2 y}{dx^2} = -\omega^2 y(x)$

**Step 1:**  

The general solution is:  

$$y(x) = A \cos(\omega x) + B \sin(\omega x)$$

**Final Answer:**  

$$y(x) = A \cos(\omega x) + B \sin(\omega x)$$

---

## Question 4: Verify the wave equation

**Given:**  

$$\psi(t, x) = A \cos(\omega t + kx)$$  

where  

$$\frac{\omega}{k} = v = \frac{2\pi}{T} / \frac{2\pi}{\lambda}$$

**Step 1:**  

Compute partial derivatives:  

1. $$\frac{\partial^2 \psi}{\partial t^2} = -A \omega^2 \cos(\omega t + kx)$$  

2. $$\frac{\partial^2 \psi}{\partial x^2} = -A k^2 \cos(\omega t + kx)$$

**Step 2:**  

Substitute into the wave equation:  

$$\frac{\partial^2 \psi}{\partial t^2} = v^2 \frac{\partial^2 \psi}{\partial x^2}$$  

Since $v = \frac{\omega}{k}$,  

$\omega^2 = v^2 k^2$, so the equation is satisfied.

**Conclusion:**  

The given function satisfies the wave equation. 