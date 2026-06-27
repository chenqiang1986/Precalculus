---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 2: Composition and Inverse Functions"
---

# Lesson 2
## Composition and Inverse Functions

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- compute a function composition;
- explain why composition order matters;
- evaluate a composition from formulas or raw mappings;
- explain what an inverse function does;
- find the inverse of a linear function;
- check whether two functions are inverses;
- decide when an inverse exists.

---

# Function Composition

Composition means applying one function after another.

$$
(f \circ g)(x)=f(g(x))
$$

Read this as:

$$
\text{$f$ after $g$}
$$

---

# Composition Example

Let

$$
f(x)=2x+1,\qquad g(x)=x^2
$$

Then

$$
(f \circ g)(x)=f(x^2)=2x^2+1
$$

---

# Order Matters

Using the same functions:

$$
(g \circ f)(x)=g(2x+1)=(2x+1)^2
$$

So in general:

$$
f \circ g \ne g \circ f
$$

---

# Composition with Raw Mappings

Suppose

$$
g: 1 \to 3,\quad 2 \to 1,\quad 3 \to 2
$$

$$
f: 1 \to 5,\quad 2 \to 7,\quad 3 \to 9
$$

Find $(f \circ g)(2)$.

---

# Solving the Composition

First:

$$
g(2)=1
$$

Then:

$$
f(1)=5
$$

Therefore:

$$
(f \circ g)(2)=5
$$

---

# What Is an Inverse?

An **inverse function** undoes the original function.

If

$$
f(a)=b
$$

then

$$
f^{-1}(b)=a
$$

---

# Inverse Idea

The roles of input and output are reversed.

If a function sends

$$
x \to f(x)
$$

then the inverse sends

$$
f(x) \to x
$$

---

# Finding an Inverse

Suppose a function is given by a table:

| $x$ | $-1$ | $0$ | $2$ |
| --- | --- | --- | --- |
| $f(x)$ | $3$ | $5$ | $9$ |

To find the inverse, reverse each input-output pair.

---

# Inverse Table Example

The inverse table is:

| $x$ | $3$ | $5$ | $9$ |
| --- | --- | --- | --- |
| $f^{-1}(x)$ | $-1$ | $0$ | $2$ |

For example, since $f(2)=9$, we have $f^{-1}(9)=2$.

---

# Finding an Inverse from an Expression

Let

$$
f(x)=3x-4
$$

Start with

$$
y=3x-4
$$

Solve for $x$ in terms of $y$.

---

# Inverse Example Continued


$$
y=3x-4
$$

Solve:

$$
y+4=3x
$$

$$
x=\frac{y+4}{3}
$$

So

$$
f^{-1}(y)=\frac{y+4}{3}
$$

---

# Checking an Inverse

An inverse should satisfy:

$$
f\left(f^{-1}(x)\right)=x
$$

and

$$
f^{-1}(f(x))=x
$$

---

# Example Check

If

$$
f(x)=3x-4,\qquad f^{-1}(x)=\frac{x+4}{3}
$$

then

$$
f\left(f^{-1}(x)\right)=3\left(\frac{x+4}{3}\right)-4=x
$$

---

# When Does an Inverse Exist?

A function has an inverse only if it is **one-to-one**.

That means different inputs must produce different outputs.

If two different inputs give the same output, the inverse would not know which input to return.

---

# Table Example That Fails

Suppose

| $x$ | $1$ | $2$ | $3$ |
| --- | --- | --- | --- |
| $f(x)$ | $4$ | $4$ | $6$ |

Here, $f(1)=4$ and $f(2)=4$.

If we reverse the pairs, then $4$ would have to map to both $1$ and $2$.

So the inverse is not a function.

---

# Why $x^2$ Fails

$$
f(x)=x^2
$$

gives

$$
f(2)=4,\qquad f(-2)=4
$$

So $f(x)=x^2$ is not one-to-one on all real numbers.

---

# Domain Restriction

If we restrict the domain of

$$
f(x)=x^2
$$

to

$$
x \ge 0
$$

then the inverse exists and is

$$
f^{-1}(x)=\sqrt{x}
$$

---

# Another Domain Restriction

Now keep the same function

$$
f(x)=x^2
$$

but restrict the domain to

$$
x \le 0
$$

What should the inverse be?

---

# Horizontal Line Test

The horizontal line test helps decide whether a function is one-to-one.

- passes the horizontal line test $\Rightarrow$ inverse may exist
- fails the horizontal line test $\Rightarrow$ no inverse on that domain

---

# Examples

- $f(x)=2x+1$ passes the horizontal line test
- $f(x)=x^2$ fails on all real numbers
- $f(x)=x^3$ passes

---

# Summary

- Composition means applying functions in sequence.
- In composition, order matters.
- An inverse undoes a function.
- To find an inverse, swap $x$ and $y$ and solve.
- A function must be one-to-one to have an inverse.
- The horizontal line test checks whether a graph is one-to-one.

---

# Quick Practice

1. If $f(x)=x+4$ and $g(x)=2x$, find $(f \circ g)(x)$.
2. Explain why $(f \circ g)(x)$ and $(g \circ f)(x)$ are not always the same.
3. Find the inverse of $f(x)=2x+5$.
4. Check whether $f(x)=x^2$ has an inverse on all real numbers.
5. What does the horizontal line test tell you?
6. Why does restricting a domain sometimes create an inverse?

---

# Exit Ticket

Write 2 to 3 sentences answering:

- Why does order matter in composition?
- What does an inverse function do?
- Why must a function be one-to-one to have an inverse?
- How does the horizontal line test help?
