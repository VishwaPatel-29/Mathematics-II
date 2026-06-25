# 📘 Mathematics-II Important 6 Marks Theory Questions & Answers

## 1. Explain Maxima and Minima of Single Variable Functions

### Answer

Maxima and Minima are used to determine the highest and lowest values of a function.

### Steps:

1. Find the first derivative (f'(x)).
2. Equate it to zero:
   [
   f'(x)=0
   ]
3. Find the critical points.
4. Compute the second derivative (f''(x)).
5. Apply the Second Derivative Test:

   * (f''(x) > 0) ⇒ Local Minimum
   * (f''(x) < 0) ⇒ Local Maximum

### Applications:

* Optimization problems
* Engineering design
* Machine Learning

---

## 2. Explain Taylor and Maclaurin Series

### Answer

### Taylor Series

A function can be expanded around (x=a) as:

[
f(x)=f(a)+(x-a)f'(a)+\frac{(x-a)^2}{2!}f''(a)+\cdots
]

### Maclaurin Series

Special case of Taylor Series when (a=0):

[
f(x)=f(0)+xf'(0)+\frac{x^2}{2!}f''(0)+\cdots
]

### Important Expansions

[
e^x=1+x+\frac{x^2}{2!}+\frac{x^3}{3!}+\cdots
]

[
\sin x=x-\frac{x^3}{3!}+\frac{x^5}{5!}-\cdots
]

[
\cos x=1-\frac{x^2}{2!}+\frac{x^4}{4!}-\cdots
]

### Applications:

* Function approximation
* Numerical methods
* Engineering calculations

---

## 3. Explain Variable Separable Differential Equations

### Answer

A differential equation is said to be separable if it can be written as:

[
\frac{dy}{dx}=f(x)g(y)
]

### Steps:

1. Separate variables:
   [
   \frac{dy}{g(y)}=f(x),dx
   ]
2. Integrate both sides:
   [
   \int \frac{dy}{g(y)}=\int f(x),dx
   ]
3. Add the constant of integration.

Thus, the required solution is obtained.

---

## 4. Explain Linear Differential Equation

### Answer

The standard form of a first-order linear differential equation is:

[
\frac{dy}{dx}+Py=Q
]

where (P) and (Q) are functions of (x).

### Steps:

1. Find the Integrating Factor (IF):
   [
   IF=e^{\int Pdx}
   ]
2. Multiply the equation by IF.
3. Integrate both sides.

### General Solution:

[
y(IF)=\int Q(IF),dx+C
]

### Applications:

* Electrical circuits
* Population growth models
* Engineering systems

---

## 5. Explain Laplace Transform and Its Applications

### Answer

Laplace Transform converts differential equations into algebraic equations, making them easier to solve.

### Definition:

[
L[f(t)]=\int_0^\infty e^{-st}f(t),dt
]

### Applications:

* Solving differential equations
* Control systems
* Dynamic systems
* Signal processing
* Computational modeling

---

## 6. Explain Eigenvalues and Eigenvectors

### Answer

For a square matrix (A),

[
AX=\lambda X
]

where:

* (\lambda) = Eigenvalue
* (X) = Eigenvector

### Procedure:

[
(A-\lambda I)X=0
]

For a non-trivial solution:

[
|A-\lambda I|=0
]

The roots obtained are eigenvalues.

Substituting the eigenvalues into

[
(A-\lambda I)X=0
]

gives the corresponding eigenvectors.

### Applications:

* Data representation
* Machine learning
* Vibrational analysis
* Engineering systems

---

## 7. Explain Diagonalization of Matrix

### Answer

Diagonalization transforms a matrix into a diagonal form.

### Steps:

1. Find eigenvalues.
2. Find eigenvectors.
3. Form matrix (P) using eigenvectors.
4. Form diagonal matrix (D).
5. Use:

[
D=P^{-1}AP
]

### Advantages:

* Simplifies matrix computations
* Useful in solving systems of equations
* Useful in powers of matrices

---

## 8. Explain Basis and Dimension

### Answer

### Basis

A basis of a vector space is a set of vectors that:

* Are linearly independent
* Span the vector space

### Example

For (R^3):

[
(1,0,0), (0,1,0), (0,0,1)
]

form a basis.

### Dimension

Dimension is the number of vectors in the basis.

Hence,

[
\dim(R^3)=3
]

### Importance:

* Determines degrees of freedom
* Fundamental concept in Linear Algebra

---

## 9. Explain Bisection Method

### Answer

Bisection Method is a numerical technique used to find roots of equations.

### Steps:

1. Choose interval ([a,b]).
2. Verify:

[
f(a)f(b)<0
]

3. Compute midpoint:

[
x=\frac{a+b}{2}
]

4. Check the sign change.
5. Repeat until desired accuracy is achieved.

### Advantages:

* Simple
* Reliable
* Guaranteed convergence

---

## 10. Explain Newton-Raphson Method

### Answer

Newton-Raphson Method is an iterative method used to find roots of equations.

### Formula

[
x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}
]

### Steps:

1. Choose an initial approximation.
2. Compute (f(x_n)) and (f'(x_n)).
3. Calculate next approximation.
4. Repeat until convergence.

### Advantages:

* Fast convergence
* High accuracy
* Widely used in numerical computation

---

## 11. Explain Gradient Descent Algorithm

### Answer

Gradient Descent is an optimization algorithm used to minimize a function.

### Formula

[
x_{new}=x_{old}-\eta \nabla f
]

where:

* (\eta) = Learning Rate
* (\nabla f) = Gradient

### Steps:

1. Start with an initial value.
2. Compute gradient.
3. Update variables.
4. Repeat until minimum is reached.

### Applications:

* Machine Learning
* Neural Networks
* Data Science
* Optimization Problems

---

## 12. Explain Chain Rule with Example

### Answer

The Chain Rule is used to differentiate composite functions.

If

[
y=f(u)
]

and

[
u=g(x)
]

then

[
\frac{dy}{dx}=\frac{dy}{du}\cdot\frac{du}{dx}
]

### Example

[
y=(x^2+1)^5
]

Let

[
u=x^2+1
]

Then

[
y=u^5
]

Differentiating:

[
\frac{dy}{du}=5u^4
]

[
\frac{du}{dx}=2x
]

Therefore,

[
\frac{dy}{dx}=10x(x^2+1)^4
]

### Applications:

* Calculus
* Optimization
* Machine Learning

---

## 13. Explain Orthogonality and Projection

### Answer

### Orthogonality

Two vectors are orthogonal if:

[
a\cdot b=0
]

### Projection

Projection of vector (a) onto vector (b) is:

[
Proj_b(a)=\frac{a\cdot b}{|b|^2}b
]

### Applications:

* Computer Graphics
* Signal Processing
* Machine Learning

---

## 14. Explain Vector Space and Subspace

### Answer

### Vector Space

A vector space is a collection of vectors closed under:

* Vector Addition
* Scalar Multiplication

### Subspace

A subspace is a subset of a vector space that also satisfies all vector space properties.

### Example

[
{(x,y,0)}
]

is a subspace of (R^3).

### Applications:

* Data Representation
* Linear Algebra
* Computer Science

---

## 15. Explain Positive Definite Matrix

### Answer

A matrix (A) is positive definite if:

[
x^TAx>0
]

for every non-zero vector (x).

### Properties:

1. All eigenvalues are positive.
2. Matrix is symmetric.
3. Determinants of principal minors are positive.

### Applications:

* Optimization
* Statistics
* Machine Learning
* Engineering

---

## 16. Explain Gauss Elimination Method

### Answer

Gauss Elimination is used to solve systems of linear equations.

### Steps:

1. Write equations in augmented matrix form.
2. Convert matrix into upper triangular form.
3. Apply elementary row operations.
4. Use back substitution to obtain solutions.

### Advantages:

* Efficient for large systems
* Widely used in numerical methods
* Easy implementation

---

## 17. Explain Applications of Eigenvalues and Eigenvectors

### Answer

Eigenvalues and Eigenvectors are widely used in science and engineering.

### Applications:

1. Principal Component Analysis (PCA)
2. Data Compression
3. Image Processing
4. Vibration Analysis
5. Machine Learning
6. Control Systems

For matrix (A),

[
AX=\lambda X
]

where:

* (\lambda) = Eigenvalue
* (X) = Eigenvector

They simplify matrix operations and help in efficient data representation.

---

# ⭐ Very Short Theory Answers (1–2 Lines)

### What is Gradient?

A vector consisting of all partial derivatives of a function.

### What is Eigenvalue?

A scalar (\lambda) satisfying:

[
AX=\lambda X
]

### What is Laplace Transform?

A technique that converts differential equations into algebraic equations.

### What is Newton-Raphson Method?

An iterative numerical method for finding roots of equations.

### What is Bisection Method?

A root-finding method based on repeatedly halving an interval.
