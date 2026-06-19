---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 5: Quadratic Standard Form and Factorized Form"
---

# Lesson 5
## Quadratic Standard Form and Factorized Form

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- recognize the standard form and factorized form of a quadratic;
- find roots from a quadratic written in factorized form;
- build a factorized form from known roots;
- use the quadratic formula on a quadratic in standard form;
- rewrite a quadratic from standard form to factorized form;
- rewrite a quadratic from factorized form to standard form.

---

# Big Idea

A quadratic can be written in two important forms:

- standard form: $ax^2+bx+c$;
- factorized form: $a(x-r_1)(x-r_2)$.

The roots connect these two forms.

---

# What Is a Root?

A **root** of a polynomial is a value of $x$ that makes the polynomial equal to $0$.

If

$$
f(x)=x^2-5x+6
$$

then $x=2$ is a root because

$$
f(2)=2^2-5(2)+6=0
$$

Roots are also called **zeros** or **solutions** of $f(x)=0$.

---

# Step 1
## Find Roots from Factorized Form

If a quadratic is written as

$$
a(x-r_1)(x-r_2),
$$

then the roots are

$$
x=r_1 \qquad \text{and} \qquad x=r_2.
$$

Set each factor equal to $0$.

---

# Step 1 Example

$$
x^2-5x+6=(x-2)(x-3)
$$

So

$$
x-2=0 \Rightarrow x=2
$$

and

$$
x-3=0 \Rightarrow x=3
$$

The roots are $2$ and $3$.

---

# Class Practice 1

Find the roots.

1. $(x-6)(x+2)$
2. $3(x+4)(x-1)$
3. $(x-5)^2$

---

# Step 2
## Construct Factorized Form from Known Roots

If the roots are $r_1$ and $r_2$, then the factors are

$$
(x-r_1) \qquad \text{and} \qquad (x-r_2).
$$

So the quadratic has the form

$$
a(x-r_1)(x-r_2),
$$

where $a$ is the leading coefficient.

---

# Step 2 Example

If the roots are $4$ and $-1$, then the factors are

$$
(x-4) \qquad \text{and} \qquad (x+1).
$$

If the quadratic is monic, then

$$
(x-4)(x+1).
$$

If the leading coefficient is $3$, then

$$
3(x-4)(x+1).
$$

---

# Class Practice 2

Write a factorized form for each quadratic.

1. roots $5$ and $-3$
2. roots $2$ and $2$
3. roots $-1$ and $7$, with leading coefficient $2$

---

# Step 3
## Construct Standard Form from Factorized Form

To go from factorized form to standard form:

1. multiply the binomials;
2. distribute any leading coefficient;
3. combine like terms.

---

# Step 3 Example

Expand:

$$
3(x-2)(x+5)
$$

First multiply the binomials:

$$
(x-2)(x+5)=x^2+3x-10
$$

Then multiply by $3$:

$$
3x^2+9x-30
$$

---

# Class Practice 3

Write each quadratic in standard form.

1. $(x-4)(x+1)$
2. $2(x+3)(x-2)$
3. $(x-5)^2$

---

# Class Practice 3 Continued

Given the roots, write each monic quadratic polynomial in standard form.

1. roots $2$ and $-5$
2. roots $-1$ and $4$
3. roots $3$ and $3$

---

# Step 4
## Recall the Quadratic Formula on Standard Form

For

$$
ax^2+bx+c=0,
$$

the roots are

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}.
$$

Use this when the roots are not easy to see from factoring.

---

# Step 4 Example

Solve:

$$
x^2-4x-1=0
$$

Here

$$
a=1,\quad b=-4,\quad c=-1.
$$

---

# Step 4 Example

$$
x=\frac{-(-4)\pm\sqrt{(-4)^2-4(1)(-1)}}{2(1)}
=\frac{4\pm\sqrt{20}}{2}
=\frac{4\pm 2\sqrt{5}}{2}
=2\pm\sqrt{5}
$$

So the roots are

$$
2+\sqrt{5} \qquad \text{and} \qquad 2-\sqrt{5}.
$$

---

# Class Practice 4

Use the quadratic formula to find the roots.

1. $x^2-5x+1=0$
2. $2x^2+x-3=0$
3. $x^2-6x+9=0$

---

# Step 5
## Construct Factorized Form from Standard Form

To factor a quadratic in standard form:

1. find the roots;
2. write one factor for each root;
3. include the leading coefficient if needed.

---

# Step 5 Example

Factor

$$
2x^2+x-3
$$

The roots are

$$
x=1 \qquad \text{and} \qquad x=-\frac{3}{2}.
$$

So the factors are

$$
(x-1) \qquad \text{and} \qquad \left(x+\frac{3}{2}\right).
$$

Equivalent factorized form:

$$
2x^2+x-3=(x-1)(2x+3)
$$

---

# Class Practice 5

Write each quadratic in factorized form.

1. $x^2-7x+10$
2. $x^2-4x-1$
3. $x^2+2x-8$

---

# Exit Ticket

1. The roots are $6$ and $-2$. Write the factorized form.
2. Write $2(x-1)(x+4)$ in standard form.
3. Factor $x^2-3x-10$.
