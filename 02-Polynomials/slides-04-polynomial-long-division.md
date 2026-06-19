---
marp: true
theme: default
paginate: true
math: mathjax
title: "Lesson 4: Polynomial Long Division"
---

# Lesson 4
## Polynomial Long Division

Precalculus

---

# Learning Goals

By the end of this lesson, you should be able to:

- write polynomials in standard form before dividing;
- use zero coefficients for missing powers;
- divide a polynomial by a binomial using long division;
- organize the divide, multiply, subtract, and bring down steps;
- state the quotient and remainder correctly;
- check a division answer by multiplication.

---

# Big Idea

Polynomial long division is the reverse of polynomial multiplication.

We repeatedly ask:

- what term should go in the quotient;
- what product should be subtracted;
- what expression is left to divide next.

---

# Knowledge Point 1

Before dividing, write the dividend and divisor in standard form.

If a power is missing, use a zero coefficient as a placeholder.

Example:

$$
x^3-4x+1=x^3+0x^2-4x+1
$$

That missing $0x^2$ helps keep the work lined up.

---

# Placeholder Example

Rewrite each polynomial with missing powers shown.

$$
2x^4+x^2-7=2x^4+0x^3+x^2+0x-7
$$

$$
x^5+3=x^5+0x^4+0x^3+0x^2+0x+3
$$

This is especially important in long division.

---

# Class Practice 1

Rewrite each polynomial in standard form with missing powers included.

1. $x^3-5x+2$
2. $3x^4+x-9$
3. $x^5+2x^2-1$
4. $4x^3+7$

---

# Knowledge Point 2

The first quotient term comes from dividing the leading terms.

Example:

$$
\frac{x^2+5x+7}{x+2}
$$

Start with:

$$
x^2\div x=x
$$

So the first term in the quotient is $x$.

---

# Long Division Cycle

For each step:

1. divide the leading terms;
2. write that term in the quotient;
3. multiply the divisor by that term;
4. subtract the result;
5. bring down the next term.

Then repeat until the remainder has smaller degree than the divisor.

---

# Worked Example 1

Divide:

$$
\begin{array}{r}
x+3\\
x+2 \enclose{longdiv}{x^2+5x+7}\\
\begin{align}
\underline{x^2+2x}&\\
3x&+7\\
3x&+6\\
&\overline{\space\space\space\space\space 1}
\end{align}

\end{array}
$$

So the quotient is

$$
x+3
$$

with remainder $1$.

---

# Class Practice 2

Divide and simplify.

1. $\dfrac{x^2+7x+10}{x+5}$
2. $\dfrac{x^2-x-10}{x-4}$
3. $\dfrac{2x^2+9x+8}{x+3}$

---

# Knowledge Point 3

Missing terms matter during division.

Example:

$$
\frac{x^3-4x+1}{x-2}
$$

must be written as

$$
\frac{x^3+0x^2-4x+1}{x-2}
$$

Without the $0x^2$, the subtraction steps get misaligned.

---

# Worked Example 2

Divide:

$$
\frac{x^3+0x^2-4x+1}{x-2}
$$

First term:

$$
x-2 \enclose{longdiv}{x^3+0x^2-4x+1}\\
$$


---

# Class Practice 3

Divide. State the quotient and remainder.

1. $\dfrac{x^3-4x+1}{x-2}$
2. $\dfrac{x^3+x^2-2x-2}{x+1}$
3. $\dfrac{2x^3-3x^2-8x+12}{x+2}$

---

# Knowledge Point 4

Every polynomial division answer fits this pattern:

$$
\text{dividend}=(\text{divisor})(\text{quotient})+\text{remainder}
$$

Also:

$$
\deg(\text{remainder})<\deg(\text{divisor})
$$

For the last example:

$$
x^3-4x+1=(x-2)(x^2+2x)+1
$$

---

# Checking the Answer

To check a long division result:

1. multiply the divisor and quotient;
2. add the remainder;
3. make sure you get the original dividend.

If the check does not match, there is an error in the division work.

---

# Class Practice 4

For each result, verify whether it is correct.

1. $\dfrac{x^2+5x+6}{x+2}=x+3$
2. $\dfrac{x^3-4x+1}{x-2}=x^2+2x$ with remainder $1$
3. $\dfrac{2x^3-5x^2+4x-1}{x-2}=2x^2-x+2$ with remainder $3$

Use multiplication to check.

---

# Exit Ticket

1. Rewrite in standard form with placeholders:

$$
x^4-3x+2
$$

2. What is the first quotient term in

$$
\frac{2x^3+x^2-5}{x+1} \, ?
$$

3. Divide:

$$
\frac{x^2+6x+8}{x+2}
$$

4. Write the answer to

$$
\frac{x^3-4x+1}{x-2}
$$

in the form quotient with remainder.

---

# Summary

Today we learned:

- long division works best when polynomials are in standard form;
- missing powers should be shown with zero coefficients;
- each cycle is divide, multiply, subtract, and bring down;
- the remainder must have smaller degree than the divisor;
- you can check your answer by multiplying back.
