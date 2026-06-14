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
- read a function described by an expression;
- connect a function rule to its graph.

---

# What Is a Function?

A **function** is a rule that assigns each input to **exactly one** output.

$$
f: A \to B
$$

- $A$ is the domain
- $B$ is the codomain
- the **range** $f(A)$ is the set of actual outputs produced by the function
- $f(x)$ is the output for input $x$

**Note:** The **range** and **codomain** are not always the same.

- the **codomain** is the full target set declared in $f: A \to B$
- the **range** is the part of the codomain the function actually reaches

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
f: \{1,2,3\} \to \{2,4,6,8\}
$$

defined by

$$
1 \to 2,\quad 2 \to 4,\quad 3 \to 6
$$

Analysis:

- Domain: $\{1,2,3\}$
- Codomain: $\{2,4,6,8\}$
- Range: $\{2,4,6\}$

Notice that $8$ is in the codomain, but it is not in the range.

---

# Example That Is Not a Function

$$
1 \to 2,\quad 1 \to 5,\quad 2 \to 4
$$

This is **not** a function because input $1$ has two outputs.

---

# Function Table Example

| $x$ | $-2$ | $-1$ | $0$ | $1$ | $2$ |
|---|---|---|---|---|---|
| $f(x)$ | $4$ | $1$ | $0$ | $1$ | $4$ |


Analysis:

- Domain: $\{-2,-1,0,1,2\}$
- Codomain: if we use the outputs shown in the table, $\{0,1,4\}$
- Range: $\{0,1,4\}$

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

# Practice: Find Domain, Codomain, Range

For the function

$$
f: \{0,1,2,3\} \to \{1,3,5,7,9\}
$$

defined by

$$
0 \to 1,\quad 1 \to 3,\quad 2 \to 5,\quad 3 \to 7
$$

identify:

- the domain;
- the codomain;
- the range.

---

# Another Practice Example

Use the table to identify the domain, codomain, and range.

| $x$ | $-2$ | $0$ | $1$ | $4$ |
|---|---|---|---|---|
| $g(x)$ | $3$ | $1$ | $3$ | $5$ |

Also decide:

- whether this relation is a function;
- whether the codomain and range are the same.

---

# Functions Described by Expressions

Sometimes a function is given by a formula instead of a table or mapping.

Example:

$$
f(x)=2x+3
$$

This means:

- start with an input $x$;
- multiply by $2$;
- add $3$ to get the output.

---

# Reading a Function Rule

If

$$
f(x)=x^2-1
$$

then:

- $f(0)=-1$
- $f(2)=3$
- $f(-3)=8$

The expression tells us how each input is matched with exactly one output.

---

# Expression Example to Analyze

Consider

$$
f: \mathbb{R} \to \mathbb{R}
$$

given by

$$
f(x)=x^2+1
$$

Identify:

- the domain;
- the codomain;
- the range.

---

# Another Expression Example

Consider

$$
g: \mathbb{R} \to \mathbb{R}
$$

given by

$$
g(x)=2x
$$

Decide:

- the domain;
- the codomain;
- the range;
- whether the codomain and range are the same.

---

# Same Rule, Different Domain

Now consider the same rule

$$
g(x)=2x
$$

but with

$$
g:[1,2]\to\mathbb{R}
$$

Identify:

- the domain;
- the codomain;
- the range.

How does changing the domain change the range?

---

# Default Domain Convention

If a domain is **not** stated explicitly, we usually assume the domain is

$$
\text{all real numbers for which the expression is well-defined.}
$$

That means:

- denominators cannot be zero;
- expressions inside square roots must be nonnegative.

---

# Domain Practice: Fraction Example

Find the domain and range of

$$
f(x)=\frac{3}{x-2}
$$

Ask:

- which value makes the denominator zero?
- which real numbers are allowed?
- which output values can never occur?

---

# Domain Practice: Square Root Example

Find the domain and range of

$$
g(x)=\sqrt{2x+5}
$$

Ask:

- when is the expression under the square root nonnegative?
- which real numbers satisfy that condition?
- what values can a square root output?

---

# Mixed Domain Practice

Find the domain and range of

$$
h(x)=\frac{\sqrt{x-1}}{x-3}
$$

Ask:

- what conditions must both parts satisfy at the same time?
- what output values seem possible?

---

# Piecewise Functions

A **piecewise function** uses different rules on different parts of its domain.

Example:

$$
f(x)=
\begin{cases}
x+1, & x<0 \\
x^2, & x\ge 0
\end{cases}
$$

To evaluate a piecewise function, first decide which condition the input satisfies.

---

# Piecewise Example to Analyze

Find the domain and range of

$$
f(x)=
\begin{cases}
2x+1, & x<1 \\
3, & x\ge 1
\end{cases}
$$

Ask:

- what values of $x$ are covered by the pieces?
- what outputs come from each piece?

---

# Another Piecewise Example

Find the domain and range of

$$
g(x)=
\begin{cases}
\sqrt{x+2}, & -2\le x<2 \\
x-1, & x\ge 2
\end{cases}
$$

Ask:

- what is the domain of each piece?
- what is the combined domain?
- what outputs come from each piece?

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
- how outputs change as inputs change.

---

# Desmos Graph Practice

Use Desmos to visualize each function graph.

For each example, notice:

- the overall shape;
- where the graph crosses the axes;
- how the output changes as the input changes.

---

# Graph Example 1

$$
f(x)=2x+1
$$

What do you notice about its graph?

---

# Graph Example 2

$$
g(x)=x^2
$$

What do you notice about its graph?

---

# Graph Example 3

$$
h(x)=
\begin{cases}
x+2, & x<0 \\
x^2, & x\ge 0
\end{cases}
$$

What do you notice about this piecewise graph?

---

# Vertical Line Test

A graph represents a function if every vertical line intersects it at most once.

- passes the vertical line test $\Rightarrow$ function
- fails the vertical line test $\Rightarrow$ not a function

---

# Summary

- A function maps each input to exactly one output.
- Function construction method:
    - Defining Table
    - Expression
    - Piecewise Expression
    - Other
- Graphs help us understand function behavior.
