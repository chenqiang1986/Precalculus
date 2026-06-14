---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 3: Increasing, Decreasing, Even, and Odd Functions"
---

# Lesson 3
## Increasing, Decreasing, Even, and Odd Functions

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- describe where a function is increasing or decreasing;
- read increasing and decreasing behavior from a graph, table, or formula;
- identify intervals of increase and decrease;
- define even and odd functions;
- test whether a function is even, odd, or neither;
- connect even and odd functions to graph symmetry.

---

# Function Behavior

We often want to describe how a function changes as $x$ changes.

Questions to ask:

- As we move left to right, does the graph go up?
- As we move left to right, does the graph go down?
- Does the behavior stay the same everywhere?

---

# Increasing Function

A function is **increasing** on an interval if larger inputs give larger outputs.

Rigorous definition:

if $x_1<x_2$, then

$$
f(x_1)<f(x_2)
$$

In simple language:

- move to the right;
- the output goes up.

---

# Decreasing Function

A function is **decreasing** on an interval if larger inputs give smaller outputs.

Rigorous definition:

if $x_1<x_2$, then

$$
f(x_1)>f(x_2)
$$

In simple language:

- move to the right;
- the output goes down.

---

# Constant Behavior

A function is **constant** on an interval if the output stays the same.

That means:

- different inputs can give the same output;
- the graph is flat on that interval.

---

# First Example

Consider

$$
f(x)=2x+1
$$

As $x$ increases, $2x+1$ also increases.

So this function is **increasing on all real numbers**.

---

# Table Example

| $x$ | $-2$ | $-1$ | $0$ | $1$ | $2$ |
|---|---|---|---|---|---|
| $f(x)$ | $-3$ | $-1$ | $1$ | $3$ | $5$ |

Observation:

- as $x$ goes up, $f(x)$ goes up;
- this table shows increasing behavior.

---

# Decreasing Example

Consider

$$
g(x)=-3x+4
$$

As $x$ increases, $-3x+4$ gets smaller.

So this function is **decreasing on all real numbers**.

---

# Quadratic Example

Consider

$$
h(x)=x^2
$$

This function does **not** behave the same way everywhere.

- on $(-\infty,0]$, it is decreasing;
- on $[0,\infty)$, it is increasing.

---

# Why Intervals Matter

Some functions change behavior.

For

$$
h(x)=x^2
$$

- moving from $x=-3$ to $x=-1$, outputs go down;
- moving from $x=1$ to $x=3$, outputs go up.

So we describe behavior using **intervals**.

---

# Trig Example

Consider

$$
f(x)=\cos x
$$

On the interval $[0,\pi]$:

- as $x$ increases, $\cos x$ decreases;
- so $f(x)=\cos x$ is decreasing on $[0,\pi]$.

---

# Same Function, Different Interval

Now keep the same function

$$
f(x)=\cos x
$$

On the interval $[\pi,2\pi]$:

- as $x$ increases, $\cos x$ increases;
- so $f(x)=\cos x$ is increasing on $[\pi,2\pi]$.

This shows that function behavior depends on the interval.

---

# Class Practice 1

Decide whether each function is increasing, decreasing, or neither on all real numbers.

1. $f(x)=5x-2$
2. $g(x)=-x+7$
3. $h(x)=4$

Explain your reasoning in words.

---

# Class Practice 2

For

$$
p(x)=\sin x
$$

identify:

- where the function is increasing on $[-\pi,\pi]$;
- where the function is decreasing on $[-\pi,\pi]$;
- the $x$-values where the behavior changes.

---

# Piecewise Behavior Example

Consider

$$
f(x)=
\begin{cases}
x+2, & x<0 \\
3, & 0\le x<2 \\
-x+5, & x\ge 2
\end{cases}
$$

Describe the behavior on each interval.

---

# Solving the Piecewise Example

For

$$
f(x)=
\begin{cases}
x+2, & x<0 \\
3, & 0\le x<2 \\
-x+5, & x\ge 2
\end{cases}
$$

- increasing on $(-\infty,0)$;
- constant on $[0,2)$;
- decreasing on $[2,\infty)$.

---

# Graph Reading Practice

When reading a graph:

- left to right up $\Rightarrow$ increasing
- left to right down $\Rightarrow$ decreasing
- flat $\Rightarrow$ constant

Use Desmos or a sketch to test your ideas.

---

# Transition: Another Kind of Pattern

Increasing and decreasing describe **change**.

Now we study a different idea:

- what happens when we compare $f(x)$ and $f(-x)$?

This leads to **even** and **odd** functions.

---

# Even Functions

A function is **even** if

$$
f(-x)=f(x)
$$

for every $x$ in the domain.

Graph meaning:

- the graph is symmetric about the $y$-axis.

---

# Even Function Example

Consider

$$
f(x)=x^2
$$

Check:

$$
f(-x)=(-x)^2=x^2=f(x)
$$

So $f(x)=x^2$ is **even**.

---

# Another Even Example

Consider

$$
g(x)=\cos x
$$

Then

$$
g(-x)=\cos(-x)=\cos x=g(x)
$$

So $g$ is also **even**.

---

# Odd Functions

A function is **odd** if

$$
f(-x)=-f(x)
$$

for every $x$ in the domain.

Graph meaning:

- the graph has symmetry about the origin.

---

# Odd Function Example

Consider

$$
f(x)=\sin x
$$

Check:

$$
f(-x)=\sin(-x)=-\sin x=-f(x)
$$

So $f(x)=\sin x$ is **odd**.

---

# Another Odd Example

Consider

$$
g(x)=x^5-2x
$$

Then

$$
g(-x)=(-x)^5-2(-x)=-x^5+2x=-(x^5-2x)
$$

So $g$ is **odd**.

---

# Neither Even Nor Odd

Some functions are neither.

Example:

$$
f(x)=x^2+x
$$

Then

$$
f(-x)=x^2-x
$$

This is not equal to $f(x)$ and not equal to $-f(x)$.

So the function is **neither**.

---

# How To Test a Function

To decide whether a function is even, odd, or neither:

1. Replace $x$ with $-x$.
2. Simplify.
3. Compare with $f(x)$ and $-f(x)$.

---

# Class Practice 3

Determine whether each function is even, odd, or neither.

1. $f(x)=x^6$
2. $g(x)=x^3+1$
3. $h(x)=x^5+x$

Show the test by replacing $x$ with $-x$.

---

# Class Practice 4

Determine whether each function is even, odd, or neither.

1. $f(x)=|x|$
2. $g(x)=\frac{1}{x}$
3. $h(x)=x^2-4x$

Also describe the symmetry, if any.

---

# Important Note About Domain

The domain matters when testing even and odd functions.

Example:

$$
f(x)=\frac{1}{x}
$$

Its domain is all real numbers except $0$.

Since

$$
f(-x)=\frac{1}{-x}=-\frac{1}{x}=-f(x)
$$

the function is **odd** on its domain.

---

# Mixed Review Example

Consider

$$
f(x)=x^3
$$

This function is:

- increasing on all real numbers;
- odd;
- symmetric about the origin.

One function can have more than one useful property.

---

# Quick Check

For each function, answer both questions:

1. Is it increasing, decreasing, or mixed?
2. Is it even, odd, or neither?

Functions:

- $x^2$
- $\sin x$
- $-x$
- $\cos x$

---

# Summary

- Increasing means outputs rise as inputs increase.
- Decreasing means outputs fall as inputs increase.
- Some functions change behavior, so we describe intervals.
- Even functions satisfy $f(-x)=f(x)$ and have $y$-axis symmetry.
- Odd functions satisfy $f(-x)=-f(x)$ and have origin symmetry.
- Some functions are neither even nor odd.

---

# Exit Ticket

Write 2 to 3 sentences answering:

- What does it mean for a function to be increasing?
- Why do we sometimes use intervals instead of one label for the whole function?
- How can you test whether a function is even or odd?
- What kind of symmetry matches even and odd functions?
