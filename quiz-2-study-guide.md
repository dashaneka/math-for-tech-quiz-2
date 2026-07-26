# Quiz 2 Study Guide

## Expected Quiz Structure

### Question 1: Integrals

- **1(a): Indefinite integral**
- **1(b): Definite integral**

### Question 2: Improper Integral

### Question 3: First-Order Differential Equation

---

## 1. Indefinite and Definite Integrals

### Files to study

1. `indefinite-integrals-table-and-homework.pdf`
2. `lecture-07-integration.pdf`
3. `lecture-08-integration-by-substitution.pdf`
4. `lecture-09-additional-integration-topics.pdf`
5. `lecture-10-definite-integrals.pdf`

### Indefinite integral checklist

- [ ] Know the basic integration formulas.
- [ ] Remember to include the constant of integration, \(+C\).
- [ ] Apply the sum and constant multiple rules.
- [ ] Integrate powers using:

  \[
  \int x^n\,dx=\frac{x^{n+1}}{n+1}+C,\qquad n\ne -1
  \]

- [ ] Recognize the logarithmic form:

  \[
  \int \frac{1}{x}\,dx=\ln|x|+C
  \]

- [ ] Use substitution when the integral contains a function and its derivative.
- [ ] Use integration by parts when needed:

  \[
  \int u\,dv=uv-\int v\,du
  \]

- [ ] Check an answer by differentiating it.

### Definite integral checklist

- [ ] Find an antiderivative \(F(x)\).
- [ ] Apply the Fundamental Theorem of Calculus:

  \[
  \int_a^b f(x)\,dx=F(b)-F(a)
  \]

- [ ] Do not add \(+C\) to the final answer.
- [ ] Be careful with the order: upper limit minus lower limit.
- [ ] Know how substitution changes the limits of integration.
- [ ] Interpret a definite integral as signed area or accumulated change.
- [ ] Practise area and application problems from Lecture 10.

### Method for Question 1

1. Identify whether the integral is indefinite or definite.
2. Simplify the integrand if possible.
3. Choose the integration rule or technique.
4. Find the antiderivative.
5. For an indefinite integral, add \(+C\).
6. For a definite integral, evaluate \(F(b)-F(a)\).
7. Check signs, arithmetic, and parentheses.

---

## 2. Improper Integrals

### Files to study

1. `lecture-09-additional-integration-topics.pdf`
2. `lecture-11-improper-integrals.pdf`

Focus especially on **Section 7.4: Improper Integrals** in Lecture 11.

### Checklist

- [ ] Recognize an infinite interval:

  \[
  \int_a^\infty f(x)\,dx
  \]

- [ ] Recognize an unbounded integrand, where the function becomes infinite at an endpoint or inside the interval.
- [ ] Replace the problematic boundary with a variable.
- [ ] Rewrite the integral as a limit:

  \[
  \int_a^\infty f(x)\,dx
  =
  \lim_{b\to\infty}\int_a^b f(x)\,dx
  \]

- [ ] Evaluate the ordinary definite integral first.
- [ ] Evaluate the limit.
- [ ] State clearly whether the integral **converges** or **diverges**.
- [ ] If there is a discontinuity inside the interval, split the integral at that point and test both parts.

### Important \(p\)-integral tests

On \([1,\infty)\):

\[
\int_1^\infty \frac{1}{x^p}\,dx
\]

- Converges if \(p>1\).
- Diverges if \(p\le 1\).

On \((0,1]\):

\[
\int_0^1 \frac{1}{x^p}\,dx
\]

- Converges if \(p<1\).
- Diverges if \(p\ge 1\).

### Method for Question 2

1. Identify why the integral is improper.
2. Rewrite it using the correct limit.
3. Find the antiderivative.
4. Evaluate the limit.
5. State **convergent** with its value, or **divergent**.

---

## 3. First-Order Differential Equations

### File to study

1. `lecture-12-first-order-differential-equations.pdf`

### Checklist

- [ ] Understand the general form:

  \[
  \frac{dy}{dx}=f(x,y)
  \]

- [ ] Identify the order of a differential equation.
- [ ] Verify a proposed solution by substitution.
- [ ] Understand initial conditions and initial-value problems.
- [ ] Read and sketch slope fields.
- [ ] Use Euler's method if it is included in the quiz.
- [ ] Recognize and solve separable equations.
- [ ] Apply the initial condition to find the constant.

### Separable-equation method

For an equation that can be written as

\[
\frac{dy}{dx}=g(x)h(y),
\]

use these steps:

1. Separate the variables:

   \[
   \frac{1}{h(y)}\,dy=g(x)\,dx
   \]

2. Integrate both sides:

   \[
   \int\frac{1}{h(y)}\,dy=\int g(x)\,dx
   \]

3. Simplify and solve for \(y\), if possible.
4. Use the initial condition to determine \(C\).
5. Substitute the solution back into the original equation to check it.

### Euler's method

If \(y'=f(x,y)\), step size is \(h\), and the current point is \((x_n,y_n)\):

\[
x_{n+1}=x_n+h
\]

\[
y_{n+1}=y_n+h f(x_n,y_n)
\]

---

## Recommended Study Order

1. Review the indefinite integral table and basic rules.
2. Practise substitution from Lectures 7 and 8.
3. Practise definite integrals and the Fundamental Theorem of Calculus.
4. Study improper integrals and practise convergence questions.
5. Study first-order differential equations from Lecture 12.
6. Solve at least one timed problem from each quiz section.
7. Review mistakes and repeat any weak topic.

## Final Self-Test

- [ ] I can solve an indefinite integral and remember \(+C\).
- [ ] I can solve a definite integral using \(F(b)-F(a)\).
- [ ] I can correctly rewrite an improper integral as a limit.
- [ ] I can decide whether an improper integral converges or diverges.
- [ ] I can solve a separable first-order differential equation.
- [ ] I can use an initial condition to find the constant.
- [ ] I can apply Euler's method if asked.
