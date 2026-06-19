---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 1: Introduction to Polynomials"
---

# Lesson 1
## Introduction to Polynomials

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- define a polynomial function;
- decide whether a function is a polynomial or not;
- explain why some expressions are not polynomials;
- identify terms, coefficients, and the constant term;
- write a polynomial in standard form;
- find the degree and leading coefficient of a polynomial.

---

# Big Idea

A polynomial is built from simple power terms:

$$
a_kx^k
$$

where:

- the coefficient $a_k$ is a real number;
- the exponent $k$ must be a whole number.

---

# Knowledge Point 1

A **polynomial function** has the form

$$
f(x)=a_nx^n+a_{n-1}x^{n-1}+\cdots+a_2x^2+a_1x+a_0
$$

with:

- $n$ a nonnegative integer;
- each coefficient $a_i$ a real number;
- $a_n\ne 0$ for a nonzero polynomial.

---

# What Exponents Are Allowed?

Allowed exponents:

- $0,1,2,3,\dots$

Not allowed in a polynomial:

- negative exponents;
- fractional exponents;
- variables in denominators or radicals.

---

# Class Practice 1

Decide whether each function is a polynomial.

1. $f(x)=3x^2-5x+1$
2. $g(x)=x^{-1}+2$
3. $h(x)=7$
4. $p(x)=4x^{0.5}-1$
5. $q(x)=2x^4+x$

If it is not a polynomial, say what rule is broken.

---

# Knowledge Point 2

Each part of a polynomial is called a **term**.

Example:

$$
p(x)=4x^3-2x^2+7x-5
$$

- terms: $4x^3,\ -2x^2,\ 7x,\ -5$
- coefficients: $4,\ -2,\ 7$
- constant term: $-5$

---

# Class Practice 2

For

$$
r(x)=-3x^4+6x^2-x+8
$$

identify:

- the terms;
- the coefficient of $x^4$;
- the coefficient of $x$;
- the constant term.

---

# Knowledge Point 3

A constant in the denominator is fine, because it is just part of the coefficient.

Example:

$$
\frac{x^2+x+5}{\pi}
=\frac{1}{\pi}x^2+\frac{1}{\pi}x+\frac{5}{\pi}
$$

This **is** a polynomial.

---

# Important Contrast

Compare these two expressions:

$$
\frac{x^2+x+5}{\pi}
\qquad\text{and}\qquad
\frac{1}{x+1}
$$

- $\pi$ is a constant, so the first expression is a polynomial;
- $x+1$ contains a variable in the denominator, so the second is not.

---

# Class Practice 3

Decide whether each function is a polynomial.

1. $f(x)=\dfrac{3x^4-1}{2}$
2. $g(x)=\dfrac{x^2+x+5}{\pi}$
3. $h(x)=\dfrac{x+1}{x-1}$
4. $p(x)=\dfrac{5}{3}x^2-4x+9$

For each "yes," say the degree.

---

# Knowledge Point 4

Common non-polynomial examples:

$$
x^{-1},\qquad x^{0.5},\qquad \sqrt{x},\qquad \sin x,\qquad \frac{1}{x+1}
$$

Why not?

- $x^{-1}$ has a negative exponent;
- $x^{0.5}$ and $\sqrt{x}$ have fractional exponents;
- $\sin x$ is trigonometric, not a sum of power terms;
- $\frac{1}{x+1}$ has a variable in the denominator.

---

# Rewriting Helps

Sometimes the reason becomes clearer after rewriting.

$$
\frac{1}{x+1}
$$

cannot be written as a finite sum of terms $a_kx^k$ with whole-number exponents.

Also,

$$
\sqrt{x}=x^{1/2}
$$

so it is not a polynomial.

---

# Class Practice 4

State why each function is **not** a polynomial.

1. $f(x)=\sqrt{x}+2$
2. $g(x)=\sin x+1$
3. $h(x)=\dfrac{1}{x+1}$
4. $p(x)=x^{-3}+x$

Answer in a short sentence for each.

---

# Knowledge Point 5

A polynomial is in **standard form** when the terms are written in descending powers of $x$.

Example:

$$
2-3x^4+x^2+7x
$$

in standard form becomes

$$
-3x^4+x^2+7x+2
$$

---

# Degree and Leading Coefficient

For a nonzero polynomial in standard form:

- the **degree** is the highest exponent;
- the **leading term** is the term with the highest exponent;
- the **leading coefficient** is the coefficient of the leading term.

Example:

$$
-3x^4+x^2+7x+2
$$

- degree: $4$
- leading term: $-3x^4$
- leading coefficient: $-3$

---

# Class Practice 5

Write each polynomial in standard form, then give its degree and leading coefficient.

1. $f(x)=5-x^3+2x^5-x$
2. $g(x)=9+4x^2$
3. $h(x)=-7x+x^6-3x^2+1$

---

# Knowledge Point 6

Special cases:

- a nonzero constant, such as $5$ or $-\dfrac{2}{3}$, is a polynomial of degree $0$;
- the zero polynomial $0$ is a polynomial, but its degree is undefined in this course.

---

# Class Practice 6

For each function:

- say whether it is a polynomial;
- if yes, give the degree;
- if no, give the reason.

1. $f(x)=0$
2. $g(x)=\dfrac{x^3-2x+1}{4}$
3. $h(x)=x+\sqrt{x}$
4. $p(x)=\cos x$
5. $q(x)=6$

---

# Exit Ticket

1. Write the definition of a polynomial function in your own words.
2. Explain why $\dfrac{x^2+x+5}{\pi}$ is a polynomial.
3. Explain why $\dfrac{1}{x+1}$ is not a polynomial.
4. Give one example of a polynomial of degree $3$.

---

# Summary

Today we learned:

- a polynomial is a finite sum of terms $a_kx^k$;
- the exponents must be whole numbers;
- constants may be coefficients, even in denominators;
- negative exponents, fractional exponents, radicals, trig functions, and variable denominators are not allowed;
- every polynomial has terms, coefficients, and a degree.
