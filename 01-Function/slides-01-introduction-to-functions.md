---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 1: Introduction to Functions"
---

# Lesson 1
## Introduction to Functions

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- define a function using mapping language;
- read a function from raw mappings;
- compute a function composition;
- find an inverse function when it exists;
- connect a function rule to its graph.

---

# What Is a Function?

A **function** is a rule that assigns each input to **exactly one** output.

$$
f: A \to B
$$

- $A$ is the domain
- $B$ is the codomain
- $f(x)$ is the output for input $x$

---

# Mapping View

Think of a function as a map:

$$
x \to f(x)
$$

A relation is a function only if:

- every input has an output;
- no input has two different outputs.

---

# Example of a Function

$$
f: \{1,2,3\} \to \{2,4,6\}
$$

defined by

$$
1 \to 2,\quad 2 \to 4,\quad 3 \to 6
$$

Each input is matched with exactly one output.

---

# Example That Is Not a Function

$$
1 \to 2,\quad 1 \to 5,\quad 2 \to 4
$$

This is **not** a function because input $1$ has two outputs.

---

# Raw Mappings

Functions are not always given by formulas.

They may be written as:

- ordered pairs;
- arrow diagrams;
- tables.

Example:

$$
\{(0,3),(1,5),(2,7),(3,9)\}
$$

---

# Reading Ordered Pairs

From

$$
\{(0,3),(1,5),(2,7),(3,9)\}
$$

we read:

- $f(0)=3$
- $f(1)=5$
- $f(2)=7$
- $f(3)=9$

---

# Is This a Function?

$$
\{(1,2),(1,4),(2,5)\}
$$

No.

Why?

Because the input $1$ appears with two different outputs.

---

# Function Table Example

| $x$ | $f(x)$ |
|---|---|
| $-2$ | $4$ |
| $-1$ | $1$ |
| $0$ | $0$ |
| $1$ | $1$ |
| $2$ | $4$ |

This matches

$$
f(x)=x^2
$$

---

# Important Observation

Different inputs may share the same output.

For example:

$$
f(-2)=4,\quad f(2)=4
$$

That is still allowed for a function.

The only forbidden case is one input giving multiple outputs.

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

# Inverse Function

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

# Finding an Inverse

Let

$$
f(x)=3x-4
$$

Start with

$$
y=3x-4
$$

Swap $x$ and $y$, then solve for $y$.

---

# Inverse Example Continued

Swap:

$$
x=3y-4
$$

Solve:

$$
x+4=3y
$$

$$
y=\frac{x+4}{3}
$$

So

$$
f^{-1}(x)=\frac{x+4}{3}
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

# When Does an Inverse Exist?

A function has an inverse only if it is **one-to-one**.

That means different inputs must produce different outputs.

Example:

$$
f(x)=x^2
$$

is not one-to-one on all real numbers.

---

# Why $x^2$ Fails

$$
f(2)=4,\qquad f(-2)=4
$$

Two different inputs give the same output.

So $f(x)=x^2$ does **not** have an inverse on all real numbers.

If we restrict the domain to $x \ge 0$, then

$$
f^{-1}(x)=\sqrt{x}
$$

---

# Function Graphs

The graph of a function is the set of points

$$
(x,f(x))
$$

Graphs help us see:

- shape;
- intercepts;
- increase or decrease;
- whether an inverse may exist.

---

# Linear Graph Example

$$
f(x)=2x+1
$$

Sample points:

| $x$ | $f(x)$ |
|---|---|
| $-1$ | $-1$ |
| $0$ | $1$ |
| $1$ | $3$ |
| $2$ | $5$ |

These points form a line.

---

# Quadratic Graph Example

$$
f(x)=x^2
$$

Sample points:

| $x$ | $f(x)$ |
|---|---|
| $-2$ | $4$ |
| $-1$ | $1$ |
| $0$ | $0$ |
| $1$ | $1$ |
| $2$ | $4$ |

These points form a parabola.

---

# Vertical Line Test

A graph represents a function if every vertical line intersects it at most once.

- passes the vertical line test $\Rightarrow$ function
- fails the vertical line test $\Rightarrow$ not a function

---

# Horizontal Line Test

To decide whether a function has an inverse:

- passes the horizontal line test $\Rightarrow$ one-to-one
- fails the horizontal line test $\Rightarrow$ no inverse on that domain

Example:

- $f(x)=2x+1$ passes
- $f(x)=x^2$ fails on all real numbers

---

# Summary

- A function maps each input to exactly one output.
- Raw mappings and tables can describe functions.
- Composition means applying functions in sequence.
- An inverse undoes a function.
- Graphs help us understand function behavior.

---

# Quick Practice

1. Is $\{(2,5),(3,7),(2,8)\}$ a function?
2. If $f(x)=x+4$ and $g(x)=2x$, find $(f \circ g)(x)$.
3. Does $f(x)=x^3$ have an inverse?
4. What test tells whether a graph is a function?

---

# Exit Ticket

Write 2 to 3 sentences answering:

- What makes a relation a function?
- Why does order matter in composition?
- When can a function have an inverse?

