September 4th, 2024
##### Topics:

1. Functions, Review of Chapter 1, Trigonometry (Chapter 1, Appendices A, B, C, D). 
2. Limits and Continuity, Evaluating Limits at Infinity, Derivatives, The Chain Rule (2.1- 2.6,3.1-3.3). 
3. Implicit differentiation, Derivatives of trigonometric functions, Inverse functions (3.4, 3.5, 3.7, 3.8). 
4. Inverse trigonometric functions and their derivatives, L'Hospital's Rule (3.9, 3.10). 
5. Exponentials and Logarithms and their derivatives, (4.1-4.6). 
6. Anti-derivatives, The Indefinite Integral, Definite Integrals (6.1, 6.2). 
7. Integration by substitution (change of variable) (6.3, 7.1, 7.2). 
8. Integration by Parts (7.3). 
9. Partial Fractions, Powers of Sines and Cosines, Trigonometric substitutions (7.4-7.6). 
10. Improper Integrals, Area between Two Curves (7.8, 8.2). 
11. Volumes of Solids of Revolution (8.3-8.5).

# Review: Functions and Their Properties

#### Review of Exponents and Radicals

- Identities:
	- $a^ma_n = a^{m+n}$
	- $(a^m)^n = a^{mn}$
	- $(ab)^m = a^mb^m$
	- $a^{-1} = \frac{1}{a}$
#### Equation of a Line

Line passes through $(x_1, y_1) and (x_2, y_2)$ is $m = \frac{y_2 - y_1}{x_2 - x_1}$ and $b = y_1 - mx_1$
### Functions

- A function $f: A -> B$ is a rule that assigns each element $x$ in a set A, called domain, exactly one element called $f(x)$, in a set $B$  called a range.

--- 
Example: Find the domain of the function $f(x) = \sqrt{x - 3}$

$D: \{x: x \geq 3\}$

---
Example: Find the domain of the function: $g(x) = \sqrt{9 - x^2}$

$D: \{|x| \leq 3\}$
$D [-3, 3]$

---
- Power functions (eg. $x^4$)
	- $x^{\frac{-1}{x}}$ is also a power function.
- Polynomial functions (eg. $a_nx^n + a_{n - 1}x^{x-1}+...+a_1x + a_0$) (degree n polynomial)
- Rational function (polynomial divided by a polynomial)
- Composite function (eg. $(f \cdot g)(x)$ )
	- $(f \cdot g)(x) = f(g(x))$
		- Domain of $f$ includes the range of $g$
	- The reverse is not always example
	- Example: $f(x) = \sqrt{x}$ and $g(x) = x^2 + 3$. Find composites of these two functions:
		- $(f \cdot g)(x) = \sqrt{x^2 + 3}$
		- $(g \cdot f)(x) = (\sqrt{x})^2 + 3$
- One-to-one function
	- Each input and output are uniquely mapped.
	- Different inputs will never give the same output.
	- $x_1 \neq x_2$ therefore $f(x_1) \neq f(x_2)$
	- $f(x_1) = f(x_2)$ therefore $x_1 = x_2$ 
- Inverse function
	- Let $f: A$ -> $B$ be a one-to-one function, then the inverse function is $f^{-1}:$ $B$ -> $A$
	- The domain of $f$ is the range of $f^{-1}$ and the range of $f$ is the domain of $f^{-1}$
	- To get the inverse:
		- Put $y = f(x)$
		- Solve the equation in terms of $y$ that is $x = f^{-1}(y)$
		- Interchange $x$ and $y$
	- Example $f(x) = 3x$
		- $y = 3x$
		- $\frac{y}{3} = x$
		- $\frac{x}{3} = y$
	- Symmetric/mirrored across $y=x$
- Piecewise functions
	- Defined with multiple sub-functions; each with an interval in the domain
	- Sign function
		- Piecewise function, denoted by $syn$ which maps negatives to 0 and positives to 1
	- Absolute functions
		- Makes all functions to positives. Defined by $x$ for $x \geq 0$ and $-x$ for $x < 0$
		- $|x + y| \leq |x| + |y|$
		- $\sqrt{x^2} = |x|$
		- $|-x| = |x|$
	- Floor function
		- $\lfloor x \rfloor$ is the largest integer less than or equal to $x$
		- $\lfloor 3.1 \rfloor = 3$
		- $\lfloor -3.1 \rfloor = -4$
	- Ceil function 
		- Smallest integer less than or equal to $x$
