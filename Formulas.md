# 📘 Mathematics-II Formula Sheet (Semester 2)

# UNIT 1: DIFFERENTIAL & MULTIVARIABLE CALCULUS

## 1. Derivative Formulas (Very Important MCQ)

### Basic

d/dx (x^n) = n x^(n−1)

d/dx (e^x) = e^x

d/dx (a^x) = a^x ln(a)

d/dx (ln x) = 1/x

d/dx (sin x) = cos x

d/dx (cos x) = -sin x

d/dx (tan x) = sec²x

---

## 2. Product Rule

d/dx (uv) = u(dv/dx) + v(du/dx)

---

## 3. Quotient Rule

d/dx (u/v) = [v(du/dx) - u(dv/dx)] / v²

---

## 4. Chain Rule

dy/dx = (dy/du) × (du/dx)

---

## Taylor Series

f(x) = f(a) + (x-a)f'(a) + ((x-a)²/2!)f''(a) + ...

---

## Maclaurin Series

(Taylor Series at a = 0)

### Important Expansions

e^x

= 1 + x + x²/2! + x³/3! + ...

sin x

= x - x³/3! + x⁵/5! - ...

cos x

= 1 - x²/2! + x⁴/4! - ...

ln(1+x)

= x - x²/2 + x³/3 - x⁴/4 + ...

---

## Partial Derivatives

If

z = f(x,y)

Then

∂z/∂x

Treat y constant.

∂z/∂y

Treat x constant.

---

## Gradient

∇f = (∂f/∂x , ∂f/∂y)

---

## Maxima and Minima (Most Important 6 Marks)

### Single Variable

Find

f'(x) = 0

Then find

f''(x)

If

f''(x) > 0

Minimum

If

f''(x) < 0

Maximum

### Two Variables

D = fxx fyy - (fxy)²

If

D > 0 and fxx > 0

Minimum

If

D > 0 and fxx < 0

Maximum

If

D < 0

Saddle Point

---

# UNIT 2: DIFFERENTIAL EQUATIONS

## Variable Separable

dy/dx = f(x)g(y)

Separate variables:

dy/g(y) = f(x) dx

Integrate both sides.

---

## Linear Differential Equation

Standard form

dy/dx + Py = Q

Integrating Factor

IF = e^(∫Pdx)

Solution

y(IF) = ∫Q(IF)dx + C

⭐ VERY IMPORTANT

---

## Second Order Differential Equation

aD² + bD + c = 0

Auxiliary Equation

am² + bm + c = 0

### Cases

Distinct roots

y = C₁e^(m₁x) + C₂e^(m₂x)

Equal roots

y = (C₁ + C₂x)e^(mx)

Imaginary roots

y = e^(αx)(C₁cosβx + C₂sinβx)

---

## Laplace Transform

### Important Table

L(1) = 1/s

L(t) = 1/s²

L(tⁿ) = n!/s^(n+1)

L(e^(at)) = 1/(s-a)

L(sin at) = a/(s²+a²)

L(cos at) = s/(s²+a²)

---

# UNIT 3: LINEAR ALGEBRA

## Eigenvalues

Find

|A - λI| = 0

The roots are Eigenvalues.

---

## Eigenvectors

(A - λI)X = 0

Solve for X.

⭐ Guaranteed Important

---

## Orthogonality

Vectors are orthogonal if

a · b = 0

---

## Projection Formula

Projection of a on b

Projb(a) = (a·b / |b|²)b

---

## Diagonalization

Steps:

1. Find Eigenvalues
2. Find Eigenvectors
3. Form Matrix P
4. Use

D = P⁻¹AP

---

## Positive Definite Matrix

For matrix A

xᵀAx > 0

for all non-zero x.

⭐ MCQ Favorite Topic

---

# UNIT 4: NUMERICAL METHODS

## Bisection Method

Formula

x = (a+b)/2

Condition

f(a)f(b) < 0

Repeat until root obtained.

---

## Newton-Raphson Method

⭐ MOST IMPORTANT

Formula

x(n+1) = x(n) - f(x(n))/f'(x(n))

Frequently asked as 6 Marks.

---

## Gauss Elimination

Steps:

1. Write Augmented Matrix
2. Convert into Upper Triangular Form
3. Back Substitution

---

## Gradient Descent

Formula

x(new) = x(old) - η(df/dx)

where η is learning rate.
