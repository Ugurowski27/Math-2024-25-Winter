### **5. Inverse of a Matrix from the Formula**

#### 1. Find the inverse matrix for:  
$$  
A = \begin{pmatrix} 2 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 2 & 0 \end{pmatrix}  
$$  

**Step-by-Step Solution:**

1. Compute the determinant of \(A\):  
   $$
   \det(A) = 2 \left| \begin{matrix} 1 & 0 \\ 2 & 0 \end{matrix} \right| - 0 \left| \begin{matrix} 0 & 0 \\ 1 & 0 \end{matrix} \right| + 1 \left| \begin{matrix} 0 & 1 \\ 1 & 2 \end{matrix} \right|
   $$  
   $$
   \det(A) = 2(1 \times 0 - 0 \times 2) + 1(0 \times 2 - 1 \times 1) = 0 - 1 = -1
   $$  

2. Find the matrix of cofactors, adjugate, and inverse matrix using $\frac{1}{\det(A)}$.  
   The inverse is:  
   $$
   A^{-1} = \frac{1}{-1} \begin{pmatrix} 0 & 2 & -1 \\ 0 & 2 & 1 \\ 1 & -1 & 0 \end{pmatrix} = \begin{pmatrix} 0 & -2 & 1 \\ 0 & -2 & -1 \\ -1 & 1 & 0 \end{pmatrix}
   $$  

---

### **6. Inverse of a Matrix using the Gauss Method**

1. Find the inverse matrices using the Gauss method for:  

$$
A = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \quad B = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 1 \\ 2 & 3 & 2 \end{pmatrix}, \quad C = \begin{pmatrix} 0 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 0 & 0 \end{pmatrix}
$$

Use elementary row operations to transform each matrix into the identity matrix.

---

### **7. Linear Equations Old School**

Solve the following system of equations without using matrices:

$$
\begin{cases}
3x - 2y = 5 \\
2x + 3y = 7
\end{cases}
$$

#### Step-by-Step Solution:

1. Start with the given system:  
   $$
   3x - 2y = 5 \quad (1)
   $$  
   $$
   2x + 3y = 7 \quad (2)
   $$

2. Multiply equation (1) by 3 and equation (2) by 2 to align the coefficients of \(y\):  
   $$
   3(3x - 2y) = 3 \times 5 \quad \Rightarrow \quad 9x - 6y = 15
   $$
   $$
   2(2x + 3y) = 2 \times 7 \quad \Rightarrow \quad 4x + 6y = 14
   $$

3. Add the two new equations to eliminate \(y\):  
   $$
   (9x - 6y) + (4x + 6y) = 15 + 14
   $$
   $$
   13x = 29 \quad \Rightarrow \quad x = \frac{29}{13}
   $$

4. Substitute $x = \frac{29}{13}$ into one of the original equations to find \(y\). Using equation (1):  
   $$
   3x - 2y = 5 \quad \Rightarrow \quad 3\left(\frac{29}{13}\right) - 2y = 5
   $$
   $$
   \frac{87}{13} - 2y = 5
   $$
   $$
   -2y = 5 - \frac{87}{13} = \frac{65}{13} - \frac{87}{13} = -\frac{22}{13}
   $$
   $$
   y = \frac{-\frac{22}{13}}{-2} = \frac{22}{26} = \frac{11}{13}
   $$

5. **Solution**:  
   $$
   x = \frac{29}{13}, \quad y = \frac{11}{13}
   $$

Thus, the solution to the system is:  
   $$
   \left( \frac{29}{13}, \frac{11}{13} \right)
   $$

---

### **8. Linear Equations by Cramer's Rule**

Solve the system of equations:

$$
\begin{cases}
2x_1 - 3x_2 = 7 \\
3x_1 + 5x_2 = 2
\end{cases}
$$

1. The coefficient matrix is:  
   $$
   A = \begin{pmatrix} 2 & -3 \\ 3 & 5 \end{pmatrix}
   $$  

2. Compute the determinant of \(A\):  
   $$
   \det(A) = 2 \times 5 - (-3) \times 3 = 10 + 9 = 19
   $$  

3. Find the determinants of matrices \(A_1\) and \(A_2\):  
   $$
   A_1 = \begin{pmatrix} 7 & -3 \\ 2 & 5 \end{pmatrix}, \quad \det(A_1) = 7 \times 5 - (-3) \times 2 = 35 + 6 = 41
   $$  
   $$
   A_2 = \begin{pmatrix} 2 & 7 \\ 3 & 2 \end{pmatrix}, \quad \det(A_2) = 2 \times 2 - 7 \times 3 = 4 - 21 = -17
   $$  

4. Use Cramer’s Rule:  
   $$
   x_1 = \frac{\det(A_1)}{\det(A)} = \frac{41}{19}, \quad x_2 = \frac{\det(A_2)}{\det(A)} = \frac{-17}{19}
   $$  

---

### **9. Linear Equations by Gauss Elimination**

Solve the system:

$$
\begin{cases}
x + y + z - t = 2 \\
x - z + 2t = 6 \\
2x - 3y + t = 4 \\
3x + y + 3z - 4t = -2
\end{cases}
$$

1. Set up the augmented matrix:  
   $$
   \begin{pmatrix}
   1 & 1 & 1 & -1 & 2 \\
   1 & 0 & -1 & 2 & 6 \\
   2 & -3 & 0 & 1 & 4 \\
   3 & 1 & 3 & -4 & -2
   \end{pmatrix}
   $$

2. Use row operations to reduce it to row-echelon form and solve for the variables.

---

### **10. Linear Equations by Matrix Inversion**


Solve the system of equations using the inverse matrix method:

$$
\begin{cases}
x + 2y + 3z = 41 \\
4x + 5y + 6z = 93 \\
7x + 8y + 9z = 145
\end{cases}
$$

#### Step-by-Step Solution:

1. The coefficient matrix \( A \), the variable matrix \( X \), and the constant matrix \( B \) are:  

   $$
   A = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{pmatrix}, \quad X = \begin{pmatrix} x \\ y \\ z \end{pmatrix}, \quad B = \begin{pmatrix} 41 \\ 93 \\ 145 \end{pmatrix}
   $$

2. Compute the determinant of \( A \):  

   $$
   \det(A) = 1 \left| \begin{matrix} 5 & 6 \\ 8 & 9 \end{matrix} \right| - 2 \left| \begin{matrix} 4 & 6 \\ 7 & 9 \end{matrix} \right| + 3 \left| \begin{matrix} 4 & 5 \\ 7 & 8 \end{matrix} \right|
   $$

   Compute each minor determinant:  

   $$
   \det \begin{pmatrix} 5 & 6 \\ 8 & 9 \end{pmatrix} = 5 \times 9 - 6 \times 8 = 45 - 48 = -3
   $$
   $$
   \det \begin{pmatrix} 4 & 6 \\ 7 & 9 \end{pmatrix} = 4 \times 9 - 6 \times 7 = 36 - 42 = -6
   $$
   $$
   \det \begin{pmatrix} 4 & 5 \\ 7 & 8 \end{pmatrix} = 4 \times 8 - 5 \times 7 = 32 - 35 = -3
   $$

   Substituting into the determinant formula:  

   $$
   \det(A) = 1(-3) - 2(-6) + 3(-3) = -3 + 12 - 9 = 0
   $$

3. **Conclusion**: Since the determinant of \( A \) is zero, the matrix \( A \) is **singular**.  
   Therefore, the system **does not have a unique solution**, and matrix inversion cannot be used to solve this system.
