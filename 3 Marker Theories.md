# ⭐ Mathematics-II Important 3 Marks Questions with Answers

## Unit 1: Calculus

### 1. Define Partial Derivative.

**Answer:**

If a function depends on two or more variables, the derivative with respect to one variable while keeping the other variables constant is called a **partial derivative**.

For:

[
z=f(x,y)
]

Partial derivatives are:

[
\frac{\partial z}{\partial x}, \quad \frac{\partial z}{\partial y}
]

---

### 2. What is Gradient?

**Answer:**

The gradient of a scalar function is a vector containing all first-order partial derivatives.

[
\nabla f=\left(\frac{\partial f}{\partial x},\frac{\partial f}{\partial y}\right)
]

It points in the direction of maximum increase of the function.

---

### 3. Define Taylor Series.

**Answer:**

Taylor Series represents a function as an infinite sum of derivatives evaluated at a point.

[
f(x)=f(a)+(x-a)f'(a)+\frac{(x-a)^2}{2!}f''(a)+\cdots
]

It is used to approximate complicated functions.

---

### 4. Define Maclaurin Series.

**Answer:**

Maclaurin Series is a special case of Taylor Series expanded about (x=0).

[
f(x)=f(0)+xf'(0)+\frac{x^2}{2!}f''(0)+\cdots
]

---

### 5. State the Second Derivative Test.

**Answer:**

For a critical point where:

[
f'(x)=0
]

* If (f''(x)>0), the point is a **minimum**.
* If (f''(x)<0), the point is a **maximum**.
* If (f''(x)=0), the test fails.

---

## Unit 2: Differential Equations & Laplace Transform

### 6. Define Differential Equation.

**Answer:**

An equation involving derivatives of a dependent variable with respect to an independent variable is called a **differential equation**.

Example:

[
\frac{dy}{dx}+y=0
]

---

### 7. What is Integrating Factor?

**Answer:**

Integrating Factor (IF) is used to solve linear differential equations.

For:

[
\frac{dy}{dx}+Py=Q
]

[
IF=e^{\int P,dx}
]

---

### 8. Define Laplace Transform.

**Answer:**

Laplace Transform converts a function from the time domain to the frequency domain.

[
L[f(t)] = \int_0^\infty e^{-st}f(t),dt
]

It helps solve differential equations easily.

---

### 9. State Laplace Transform of Important Functions.

**Answer:**

| Function  | Laplace Transform   |
| --------- | ------------------- |
| (1)       | (\frac{1}{s})       |
| (t)       | (\frac{1}{s^2})     |
| (e^{at})  | (\frac{1}{s-a})     |
| (\sin at) | (\frac{a}{s^2+a^2}) |
| (\cos at) | (\frac{s}{s^2+a^2}) |

---

### 10. State Advantages of Laplace Transform.

**Answer:**

* Converts differential equations into algebraic equations.
* Simplifies calculations.
* Widely used in engineering and control systems.

---

## Unit 3: Linear Algebra

### 11. Define Vector Space.

**Answer:**

A set of vectors satisfying closure under addition and scalar multiplication is called a **vector space**.

---

### 12. Define Linear Independence.

**Answer:**

Vectors are linearly independent if no vector can be expressed as a linear combination of the others.

Mathematically:

[
c_1v_1+c_2v_2+\cdots+c_nv_n=0
]

has only the trivial solution:

[
c_1=c_2=\cdots=c_n=0
]

---

### 13. Define Basis of a Vector Space.

**Answer:**

A basis is a set of linearly independent vectors that span the entire vector space.

Example:

[
(1,0),\ (0,1)
]

form a basis of (R^2).

---

### 14. Define Dimension of a Vector Space.

**Answer:**

The number of vectors in a basis of a vector space is called its **dimension**.

Example:

Dimension of (R^3) is **3**.

---

### 15. Define Eigenvalue and Eigenvector.

**Answer:**

For a matrix (A),

[
AX=\lambda X
]

where:

* (\lambda) = Eigenvalue
* (X) = Eigenvector

---

### 16. What is Orthogonality?

**Answer:**

Two vectors are orthogonal if their dot product is zero.

[
a \cdot b = 0
]

Orthogonal vectors are perpendicular to each other.

---

### 17. What is Diagonalization?

**Answer:**

Diagonalization is the process of converting a matrix into a diagonal matrix using eigenvalues and eigenvectors.

[
D=P^{-1}AP
]

where (D) is a diagonal matrix.

---

### 18. Define Positive Definite Matrix.

**Answer:**

A matrix (A) is positive definite if

[
x^TAx>0
]

for every non-zero vector (x).

Such matrices frequently occur in optimization problems.

---

## Unit 4: Numerical Methods & Optimization

### 19. What is Bisection Method?

**Answer:**

Bisection Method is a numerical technique used to find roots of equations.

Formula:

[
x=\frac{a+b}{2}
]

Condition:

[
f(a)f(b)<0
]

---

### 20. What is Newton-Raphson Method?

**Answer:**

A root-finding technique based on tangent approximation.

Formula:

[
x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}
]

It converges faster than the Bisection Method.

---

### 21. Define Gradient Descent.

**Answer:**

Gradient Descent is an optimization algorithm used to minimize a function.

[
x_{new}=x_{old}-\eta\nabla f
]

where (\eta) is the learning rate.

---

### 22. What is Optimization?

**Answer:**

Optimization is the process of finding the maximum or minimum value of a function subject to given conditions.

Applications include engineering, economics, and machine learning.

---

### 23. What is Machine Learning Loss Function?

**Answer:**

A loss function measures the error between predicted and actual values.

Gradient Descent is used to minimize the loss function.

---

## Unit 5: Continuity & Advanced Concepts

### 24. What is Continuity of a Function?

**Answer:**

A function (f(x)) is said to be continuous at (x=a) if

[
\lim_{x\to a}f(x)=f(a)
]

That is, the left-hand limit, right-hand limit, and function value are equal.

---

## 📌 Exam Tip

These 24 questions cover the most frequently asked **3-mark theory questions** in Mathematics-II and are highly useful for last-day revision.
