# 📘 Mathematics-II Important 6 Marks Sums with Solutions

---

# UNIT 1: Differential & Multivariable Calculus

## 1. Find Maxima and Minima of

[
f(x)=x^3-6x^2+9x+1
]

### Solution

First derivative:

[
f'(x)=3x^2-12x+9
]

[
3(x^2-4x+3)=0
]

[
(x-1)(x-3)=0
]

Critical points:

[
x=1,;x=3
]

Second derivative:

[
f''(x)=6x-12
]

At (x=1):

[
f''(1)=-6<0
]

⇒ Maximum

At (x=3):

[
f''(3)=6>0
]

⇒ Minimum

### Answer

Maximum at (x=1)

Minimum at (x=3)

---

## 2. Find Partial Derivatives

[
z=x^2y^3+3xy
]

### Solution

[
\frac{\partial z}{\partial x}=2xy^3+3y
]

[
\frac{\partial z}{\partial y}=3x^2y^2+3x
]

### Answer

[
\frac{\partial z}{\partial x}=2xy^3+3y
]

[
\frac{\partial z}{\partial y}=3x^2y^2+3x
]

---

## 3. Expand (e^x) by Maclaurin Series

### Solution

Formula:

[
e^x=1+x+\frac{x^2}{2!}+\frac{x^3}{3!}+\cdots
]

### Answer

[
e^x=1+x+\frac{x^2}{2}+\frac{x^3}{6}+\cdots
]

---

# UNIT 2: Differential Equations

## 4. Solve Variable Separable Equation

[
\frac{dy}{dx}=xy
]

### Solution

Separate variables:

[
\frac{dy}{y}=x,dx
]

Integrate:

[
\int \frac{dy}{y}=\int x,dx
]

[
\ln y=\frac{x^2}{2}+C
]

[
y=Ce^{x^2/2}
]

### Answer

[
y=Ce^{x^2/2}
]

---

## 5. Solve Linear Differential Equation

[
\frac{dy}{dx}+y=e^x
]

### Solution

[
P=1
]

Integrating Factor:

[
IF=e^{\int1dx}=e^x
]

Multiply throughout by (e^x):

[
e^x\frac{dy}{dx}+e^xy=e^{2x}
]

[
\frac{d}{dx}(ye^x)=e^{2x}
]

Integrate:

[
ye^x=\frac{1}{2}e^{2x}+C
]

[
y=\frac{1}{2}e^x+Ce^{-x}
]

### Answer

[
y=\frac{1}{2}e^x+Ce^{-x}
]

---

## 6. Solve Second Order Differential Equation

[
(D^2-5D+6)y=0
]

### Solution

Auxiliary equation:

[
m^2-5m+6=0
]

[
(m-2)(m-3)=0
]

Roots:

[
m=2,;3
]

### Answer

[
y=C_1e^{2x}+C_2e^{3x}
]

---

## 7. Find Laplace Transform

[
L(t^2)
]

### Solution

Formula:

[
L(t^n)=\frac{n!}{s^{n+1}}
]

For (n=2):

[
L(t^2)=\frac{2!}{s^3}
]

### Answer

[
L(t^2)=\frac{2}{s^3}
]

---

# UNIT 3: Linear Algebra

## 8. Find Eigenvalues and Eigenvectors

[
A=
\begin{bmatrix}
2 & 1\
1 & 2
\end{bmatrix}
]

### Solution

Characteristic equation:

[
\begin{vmatrix}
2-\lambda & 1\
1 & 2-\lambda
\end{vmatrix}=0
]

[
(2-\lambda)^2-1=0
]

[
\lambda^2-4\lambda+3=0
]

[
(\lambda-1)(\lambda-3)=0
]

Eigenvalues:

[
\lambda=1,;3
]

For (\lambda=3):

Eigenvector:

[
\begin{bmatrix}
1\
1
\end{bmatrix}
]

For (\lambda=1):

Eigenvector:

[
\begin{bmatrix}
1\
-1
\end{bmatrix}
]

### Answer

Eigenvalues:

[
\lambda=1,;3
]

Eigenvectors:

[
v_1=
\begin{bmatrix}
1\
1
\end{bmatrix}
]

[
v_2=
\begin{bmatrix}
1\
-1
\end{bmatrix}
]

---

## 9. Check Orthogonality

[
a=(1,2,3)
]

[
b=(2,-1,0)
]

### Solution

[
a\cdot b=(1)(2)+(2)(-1)+(3)(0)
]

[
=2-2+0
]

[
=0
]

### Answer

Vectors are Orthogonal.

---

# UNIT 4: Numerical Methods

## 10. Newton-Raphson Method

Find root of

[
x^2-4=0
]

Take

[
x_0=3
]

### Solution

[
f(x)=x^2-4
]

[
f'(x)=2x
]

Formula:

[
x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}
]

First iteration:

[
x_1=3-\frac{5}{6}
]

[
x_1=2.167
]

Second iteration:

[
x_2\approx2.006
]

### Answer

[
x\approx2
]

---

## 11. Bisection Method

Find root of

[
x^2-4=0
]

Interval:

[
[1,3]
]

### Solution

Midpoint:

[
x=\frac{1+3}{2}
]

[
x=2
]

Check:

[
f(2)=0
]

### Answer

[
x=2
]

---

## 12. Gauss Elimination Method

Solve

[
x+y=5
]

[
2x+y=8
]

### Solution

Subtract first equation from second:

[
x=3
]

Substitute into first equation:

[
3+y=5
]

[
y=2
]

### Answer

[
x=3,\quad y=2
]

---

# 🎯 TOP 6 SUMS TO DO BEFORE SLEEP

## 1. Maxima-Minima using Second Derivative Test

[
f(x)=x^3-6x^2+9x+1
]

### Answer

Maximum at (x=1)

Minimum at (x=3)

---

## 2. Linear Differential Equation using Integrating Factor

[
\frac{dy}{dx}+y=e^x
]

### Answer

[
y=\frac{1}{2}e^x+Ce^{-x}
]

---

## 3. Eigenvalues & Eigenvectors of 2×2 Matrix

[
A=
\begin{bmatrix}
2 & 1\
1 & 2
\end{bmatrix}
]

### Answer

Eigenvalues:

[
\lambda=1,;3
]

Eigenvectors:

[
\begin{bmatrix}
1\
1
\end{bmatrix}
,
\begin{bmatrix}
1\
-1
\end{bmatrix}
]

---

## 4. Newton-Raphson Method

[
x^2-4=0
]

### Answer

[
x\approx2
]

---

## 5. Gauss Elimination Method

[
x+y=5
]

[
2x+y=8
]

### Answer

[
x=3,\quad y=2
]

---

## 6. Variable Separable Differential Equation

[
\frac{dy}{dx}=xy
]

### Answer

[
y=Ce^{x^2/2}
]

---

## 🚀 Last Minute Revision Tip

If time is very less before exam, revise these 6 sums first:

✅ Maxima-Minima using Second Derivative Test

✅ Linear Differential Equation using Integrating Factor

✅ Eigenvalues & Eigenvectors of 2×2 Matrix

✅ Newton-Raphson Method

✅ Gauss Elimination Method

✅ Variable Separable Differential Equation

These are among the most repeated and high-probability questions in Mathematics-II.
