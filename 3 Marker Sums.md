# 📘 Mathematics-II (BECE0202) – Important 3 Mark Sums with Solutions

## UNIT 1: Differential & Multivariable Calculus

### 1. Differentiate (x^3 + 5x^2 - 2x + 1)

**Solution:**

[
\frac{d}{dx}(x^3)=3x^2
]

[
\frac{d}{dx}(5x^2)=10x
]

[
\frac{d}{dx}(-2x)=-2
]

[
\frac{d}{dx}(1)=0
]

**Answer:**

[
\boxed{3x^2 + 10x - 2}
]

---

### 2. Differentiate (e^x \sin x)

**Using Product Rule:**

[
\frac{d}{dx}(uv)=u\frac{dv}{dx}+v\frac{du}{dx}
]

[
\frac{d}{dx}(e^x\sin x)
=e^x\sin x+e^x\cos x
]

**Answer:**

[
\boxed{e^x(\sin x+\cos x)}
]

---

### 3. Find (\frac{\partial z}{\partial x})

Given:

[
z=x^2y+xy^2
]

Treat (y) as constant.

[
\frac{\partial z}{\partial x}
=2xy+y^2
]

**Answer:**

[
\boxed{2xy+y^2}
]

---

### 4. Find (\frac{\partial z}{\partial y})

Given:

[
z=x^2y+xy^2
]

Treat (x) as constant.

[
\frac{\partial z}{\partial y}
=x^2+2xy
]

**Answer:**

[
\boxed{x^2+2xy}
]

---

### 5. Find Gradient of (f(x,y)=x^2+y^2)

[
\nabla f=
\left(
\frac{\partial f}{\partial x},
\frac{\partial f}{\partial y}
\right)
]

# [

(2x,2y)
]

**Answer:**

[
\boxed{\nabla f=(2x,2y)}
]

---

# UNIT 2: Differential Equations

### 6. Find Integrating Factor

Given:

[
\frac{dy}{dx}+2y=x
]

[
P=2
]

[
IF=e^{\int 2dx}
=e^{2x}
]

**Answer:**

[
\boxed{e^{2x}}
]

---

### 7. Solve

[
\frac{dy}{dx}=3x^2
]

Integrating both sides,

[
y=\int 3x^2dx
]

[
y=x^3+C
]

**Answer:**

[
\boxed{y=x^3+C}
]

---

### 8. Find Laplace Transform of (1)

[
L(1)=\frac{1}{s}
]

**Answer:**

[
\boxed{\frac{1}{s}}
]

---

### 9. Find Laplace Transform of (t)

[
L(t)=\frac{1}{s^2}
]

**Answer:**

[
\boxed{\frac{1}{s^2}}
]

---

### 10. Find Laplace Transform of (e^{3t})

[
L(e^{3t})=\frac{1}{s-3}
]

**Answer:**

[
\boxed{\frac{1}{s-3}}
]

---

### 11. Find Laplace Transform of (\sin 2t)

[
L(\sin at)=\frac{a}{s^2+a^2}
]

For (a=2),

[
L(\sin 2t)=\frac{2}{s^2+4}
]

**Answer:**

[
\boxed{\frac{2}{s^2+4}}
]

---

# UNIT 3: Linear Algebra

### 12. Find Eigenvalues

Given:

[
A=
\begin{bmatrix}
2 & 0\
0 & 3
\end{bmatrix}
]

[
|A-\lambda I|=0
]

[
(2-\lambda)(3-\lambda)=0
]

**Answer:**

[
\boxed{\lambda=2,;3}
]

---

### 13. Check Orthogonality

[
a=(1,2)
]

[
b=(2,-1)
]

[
a\cdot b=(1)(2)+(2)(-1)
]

[
=2-2=0
]

**Answer:**

[
\boxed{\text{Vectors are Orthogonal}}
]

---

### 14. Find Dimension

Basis:

[
(1,0,0),(0,1,0),(0,0,1)
]

Number of basis vectors = 3

**Answer:**

[
\boxed{3}
]

---

### 15. Find Trace

[
A=
\begin{bmatrix}
2 & 3\
1 & 4
\end{bmatrix}
]

[
\text{Trace}=2+4
]

**Answer:**

[
\boxed{6}
]

---

### 16. Find Determinant

[
A=
\begin{bmatrix}
2 & 3\
1 & 4
\end{bmatrix}
]

[
|A|=(2)(4)-(1)(3)
]

[
=8-3
]

**Answer:**

[
\boxed{5}
]

---

# UNIT 4: Numerical Methods

### 17. One Iteration of Newton-Raphson Method

Given:

[
f(x)=x^2-4
]

[
x_0=3
]

[
f(3)=5
]

[
f'(3)=6
]

[
x_1=x_0-\frac{f(x_0)}{f'(x_0)}
]

[
=3-\frac{5}{6}
]

[
=2.167
]

**Answer:**

[
\boxed{x_1=2.167}
]

---

### 18. One Iteration of Bisection Method

Given:

[
a=1,\quad b=3
]

[
x=\frac{a+b}{2}
]

[
=\frac{1+3}{2}
]

[
=2
]

**Answer:**

[
\boxed{2}
]

---

### 19. Solve Using Back Substitution

Given:

[
x+y=5
]

[
y=2
]

Substituting:

[
x+2=5
]

[
x=3
]

**Answer:**

[
\boxed{x=3,; y=2}
]

---

### 20. One Gradient Descent Step

Given:

[
f(x)=x^2
]

[
x=4
]

[
\eta=0.1
]

Gradient:

[
\nabla f=2x=8
]

Update Rule:

[
x_{new}=x-\eta\nabla f
]

[
=4-(0.1)(8)
]

[
=3.2
]

**Answer:**

[
\boxed{3.2}
]

---

# ⭐ Exam Tip

Memorize these frequently used formulas:

[
\frac{d}{dx}(e^x)=e^x
]

[
\frac{d}{dx}(\sin x)=\cos x
]

[
L(1)=\frac{1}{s}
]

[
L(t)=\frac{1}{s^2}
]

[
L(e^{at})=\frac{1}{s-a}
]

[
L(\sin at)=\frac{a}{s^2+a^2}
]

[
\nabla f=
\left(
\frac{\partial f}{\partial x},
\frac{\partial f}{\partial y}
\right)
]

These are among the most repeated formulas in Mathematics-II university examinations.
