# Lesson 1: Introduction to Functions

## Learning Goals

By the end of this lesson, you should be able to:

- define a function using mapping language;
- read and build examples from raw mappings;
- compute a function composition;
- decide when an inverse function exists and find it when possible;
- connect a function rule with its graph.

## 1. Function Definition Using Map

A **function** is a rule that maps each input in a domain to **exactly one** output in a range.

We often write:

```text
f: A -> B
```

This means:

- `f` is the name of the function;
- `A` is the **domain**, the set of allowed inputs;
- `B` is the **codomain**, the set where outputs live.

If an element `x` in the domain is sent to an element `y` in the codomain, we write:

```text
f(x) = y
```

### Mapping Idea

Think of a function as a machine or arrow diagram:

```text
x -> f(x)
```

For a relation to be a function:

- every input must have an output;
- no input can have two different outputs.

### Example

Let

```text
f: {1, 2, 3} -> {2, 4, 6}
```

defined by:

```text
1 -> 2
2 -> 4
3 -> 6
```

This is a function because each input has exactly one output.

### Not a Function Example

```text
1 -> 2
1 -> 5
2 -> 4
```

This is **not** a function because the input `1` maps to two outputs.

## 2. Function Examples Using Raw Mapping

Sometimes a function is given directly as a list of ordered pairs or arrows instead of a formula.

### Example A: A Function

```text
{(0, 3), (1, 5), (2, 7), (3, 9)}
```

This is a function because each first coordinate appears only once.

We can read:

- `f(0) = 3`
- `f(1) = 5`
- `f(2) = 7`
- `f(3) = 9`

### Example B: Not a Function

```text
{(1, 2), (1, 4), (2, 5)}
```

This is not a function because input `1` has two outputs.

### Example C: Raw Mapping Table

| x | f(x) |
|---|------|
| -2 | 4 |
| -1 | 1 |
| 0 | 0 |
| 1 | 1 |
| 2 | 4 |

This table describes the function `f(x) = x^2` for the listed inputs.

From the table:

- `f(-2) = 4`
- `f(0) = 0`
- `f(2) = 4`

Different inputs may share the same output. That is allowed.

### Example D: Real-World Mapping

Let `T` map a temperature in Celsius to Fahrenheit:

```text
T(c) = (9/5)c + 32
```

Sample mappings:

- `0 -> 32`
- `10 -> 50`
- `20 -> 68`

This is a function because every Celsius temperature gives exactly one Fahrenheit temperature.

## 3. Function Composition

Function composition means applying one function and then using its output as the input of another function.

If we have functions `f` and `g`, then:

```text
(f o g)(x) = f(g(x))
```

Read this as:

```text
f after g
```

### Example 1

Let:

```text
f(x) = 2x + 1
g(x) = x^2
```

Then:

```text
(f o g)(x) = f(g(x)) = f(x^2) = 2x^2 + 1
```

But:

```text
(g o f)(x) = g(f(x)) = g(2x + 1) = (2x + 1)^2
```

So in general:

```text
f o g != g o f
```

### Example 2: Using Raw Mappings

Suppose:

```text
g: 1 -> 3, 2 -> 1, 3 -> 2
f: 1 -> 5, 2 -> 7, 3 -> 9
```

Find `(f o g)(2)`.

Step 1:

```text
g(2) = 1
```

Step 2:

```text
f(1) = 5
```

Therefore:

```text
(f o g)(2) = 5
```

### Why Composition Matters

Composition models multi-step processes:

- convert units, then apply a pricing rule;
- find area, then compute cost;
- evaluate one transformation, then another.

## 4. Inverse Function

An **inverse function** reverses the action of a function.

If `f(a) = b`, then:

```text
f^(-1)(b) = a
```

The inverse undoes the original function.

### Example 1

Let:

```text
f(x) = 3x - 4
```

To find the inverse:

1. Start with `y = 3x - 4`
2. Swap `x` and `y`:

```text
x = 3y - 4
```

3. Solve for `y`:

```text
x + 4 = 3y
y = (x + 4) / 3
```

So:

```text
f^(-1)(x) = (x + 4) / 3
```

### Quick Check

```text
f(f^(-1)(x)) = x
f^(-1)(f(x)) = x
```

### When Does an Inverse Exist?

A function has an inverse function only when it is **one-to-one**.

That means different inputs must give different outputs.

### Example 2: No Inverse on All Real Numbers

```text
f(x) = x^2
```

This does not have an inverse on all real numbers because:

```text
f(2) = 4
f(-2) = 4
```

Two inputs give the same output, so the function is not one-to-one.

If we restrict the domain to `x >= 0`, then the inverse exists and is:

```text
f^(-1)(x) = sqrt(x)
```

## 5. Function Graph

A graph is the set of all points `(x, f(x))`.

The graph helps us visualize:

- the outputs of a function;
- whether the function is increasing or decreasing;
- intercepts, symmetry, and turning points;
- whether the function may have an inverse.

### Example 1: Linear Function

```text
f(x) = 2x + 1
```

Some points are:

| x | f(x) |
|---|------|
| -1 | -1 |
| 0 | 1 |
| 1 | 3 |
| 2 | 5 |

These points lie on a straight line.

### Example 2: Quadratic Function

```text
f(x) = x^2
```

Some points are:

| x | f(x) |
|---|------|
| -2 | 4 |
| -1 | 1 |
| 0 | 0 |
| 1 | 1 |
| 2 | 4 |

These points form a parabola opening upward.

### Vertical Line Test

A graph represents a function exactly when every vertical line intersects the graph at most once.

- passes the vertical line test -> function
- fails the vertical line test -> not a function

### Horizontal Line Test

To decide whether a function has an inverse, use the horizontal line test:

- if every horizontal line meets the graph at most once, the function is one-to-one;
- if not, the function does not have an inverse over that domain.

For example:

- `f(x) = 2x + 1` passes, so it has an inverse;
- `f(x) = x^2` fails on all real numbers, so it does not have an inverse there.

## Summary

- A function maps each input to exactly one output.
- Raw mappings, tables, and ordered pairs can all describe functions.
- Composition means plugging one function into another.
- An inverse function undoes the original function.
- Graphs give a visual way to study function behavior.

## Practice Check

1. Is `{(2, 5), (3, 7), (2, 8)}` a function? Why or why not?
2. If `f(x) = x + 4` and `g(x) = 2x`, find `(f o g)(x)`.
3. Does `f(x) = x^3` have an inverse? Why?
4. What test can you use to tell whether a graph represents a function?
