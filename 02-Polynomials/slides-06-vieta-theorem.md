---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 6: Vieta's Theorem"
---

# Lesson 6
## Vieta's Theorem

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- state Vieta's theorem for a quadratic equation;
- find the sum and product of the roots without solving for the roots;
- use Vieta's theorem to evaluate expressions involving the roots;
- decide when a question about the roots can be answered directly from the coefficients.

---

# Big Idea

Sometimes we do **not** need the roots themselves.

Vieta's theorem lets us answer questions about the roots using only the coefficients of the quadratic.

---

# Knowledge Point 1

For

$$
ax^2+bx+c=0
$$

with roots $r_1$ and $r_2$:

$$
r_1+r_2=-\frac{b}{a}
$$

and

$$
r_1r_2=\frac{c}{a}.
$$

---

# Why This Is Useful

We can answer questions such as:

- what is $r_1+r_2$;
- what is $r_1r_2$;
- what is $\dfrac{1}{r_1}+\dfrac{1}{r_2}$;
- what is $r_1^2+r_2^2$.

All of this can be done without solving for the roots first.

---

# Worked Example 1

For

$$
2x^2-7x+3=0,
$$

find the sum and product of the roots.

Since $a=2$, $b=-7$, and $c=3$:

$$
r_1+r_2=\frac{7}{2}
$$

and

$$
r_1r_2=\frac{3}{2}.
$$

---

# Class Practice 1

Without solving the equation, find the sum and product of the roots.

1. $x^2-8x+12=0$
2. $3x^2+5x-2=0$
3. $5x^2-20=0$

---

# Knowledge Point 2

To find

$$
\frac{1}{r_1}+\frac{1}{r_2},
$$

rewrite it as

$$
\frac{r_1+r_2}{r_1r_2}.
$$

Then use Vieta's theorem.

This only makes sense when neither root is $0$.

---

# Worked Example 2

For

$$
2x^2-7x+3=0,
$$

find

$$
\frac{1}{r_1}+\frac{1}{r_2}.
$$

Use

$$
\frac{1}{r_1}+\frac{1}{r_2}=\frac{r_1+r_2}{r_1r_2}.
$$

So

$$
\frac{1}{r_1}+\frac{1}{r_2}=\frac{7/2}{3/2}=\frac{7}{3}.
$$

---

# Class Practice 2

Without solving for the roots, find each value.

1. For $x^2-5x+6=0$, find $\dfrac{1}{r_1}+\dfrac{1}{r_2}$.
2. For $x^2+4x-5=0$, find $\dfrac{1}{r_1}+\dfrac{1}{r_2}$.
3. For $2x^2+x-3=0$, find $\dfrac{1}{r_1}+\dfrac{1}{r_2}$.

---

# Knowledge Point 3

To find

$$
r_1^2+r_2^2,
$$

use

$$
r_1^2+r_2^2=(r_1+r_2)^2-2r_1r_2.
$$

Again, Vieta gives the sum and product.

---

# Worked Example 3

For

$$
x^2+4x-1=0,
$$

find

$$
r_1^2+r_2^2.
$$

Here

$$
r_1+r_2=-4,\qquad r_1r_2=-1.
$$

So

$$
r_1^2+r_2^2=(-4)^2-2(-1)=16+2=18.
$$

---

# Class Practice 3

Without solving for the roots, find each value.

1. For $x^2-6x+7=0$, find $r_1^2+r_2^2$.
2. For $2x^2-3x+4=0$, find $r_1^2+r_2^2$.
3. For $x^2+2x-3=0$, find $r_1^2+r_2^2$.

---

# Knowledge Point 4

Many root expressions can be rewritten using

$$
r_1+r_2
$$

and

$$
r_1r_2.
$$

Examples:

$$
(r_1-r_2)^2=(r_1+r_2)^2-4r_1r_2
$$

$$
\frac{r_1}{r_2}+\frac{r_2}{r_1}
=\frac{r_1^2+r_2^2}{r_1r_2}
$$

---

# Worked Example 4

For

$$
x^2-3x-2=0,
$$

find

$$
(r_1-r_2)^2.
$$

Since

$$
r_1+r_2=3,\qquad r_1r_2=-2,
$$

we get

$$
(r_1-r_2)^2=3^2-4(-2)=9+8=17.
$$

---

# Class Practice 4

Without solving for the roots, find each value.

1. For $x^2-5x+3=0$, find $(r_1-r_2)^2$.
2. For $x^2+x-1=0$, find $\dfrac{r_1}{r_2}+\dfrac{r_2}{r_1}$.
3. For $2x^2-8x+5=0$, decide whether $\dfrac{1}{r_1}+\dfrac{1}{r_2}$ can be found directly and explain why.

---

# Exit Ticket

For

$$
x^2-4x+2=0,
$$

find, without solving for the roots:

1. $r_1+r_2$
2. $\dfrac{1}{r_1}+\dfrac{1}{r_2}$
3. $r_1^2+r_2^2$
