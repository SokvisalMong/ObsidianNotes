# Functions

Often identified with the formulas that define them. Ex: f(x) = x<sup>2</sup>

In Discrete Mathematics, functions aren't necessarily defined over real numbers

Functions are also referred to as Mappings and Transformations

#### Notation
A and B are nonempty sets, A function f from A to B is an assignment of exactly one element to of B to each element of A.

If b is the unique element of B assigned by the function f to the element A, denote it by f(a) = b
If f is a function from A to B, denote it by A → B

f(a) = b, if b is the element of B assigned under f to the element of A, read as f maps A to B

#### Domains and CoDomains
If f is a function from A to B,
A is the domain of f
B is the codomain of f
The **range**, or image of f is the set of all images of elements of A.

Given a function f(x)
f(a) is called the **image** of a
a is called the **pre-image** of f(a)
The range of f is defined by f(A) = {f(a) | a ∈ A}

Example:
f: Z → R is given by f(x) = x<sup>2</sup>
The **domain** is Z, **co-domain** is R
An **image** of 3 is f(3) = 9
**pre-images** of 4 is {-2, 2}
**Range** of f(Z) is {0, 1, 4, 9, ...}

#### Summations

f1 and f2 are functions from A to R, then f1 + f2 and f1 * f2 are also functions from A to R, for all x ∈ A
(f1 + f2)(x) = f1(x) + f2(x)
(f1 * f2)(x) = f1(x) * f2(x)

#### Subsets

Let f be a function from A to B and let S be a subset of A.

S is a subset of B consisting of f(S).
Denoted by: f(S) = {t | ∃s ∈ S (t = f(s))}
Shorthanded by: {f(s) | s ∈ S}, formally: f(S) = {f(s) | s ∈ S}

### One-to-One Functions (or Injunction)
is a function that never assigns the same value to 2 different domain elements.

A one-to-one function is **injective**.

Basically it never assigns the same value again.

### Onto Functions (Surjection)
is a function that for every elemeent of B there is an element of A with f(a) = b.

An onto function is surjective.

Basically all elements of codomain must be mapped to by images of the domain.

### Bijective Functions (Bijection)
is one-to-one and onto functions.

# Sequence
is a discrete structure used to represent an ordered list.

A sequence is a function from a subset, usually either the set {0, 1, 2...} or {1, 2, 3...} to a set S.

Denoted with a<sub>n</sub> to denote the image of interer n.
a<sub>n</sub> is called a term of the sequence

### Geometric Sequence (Exponential)
a sequence that uses exponentials.
a, ar, ar<sup>2</sup>, ..., ar<sup>n</sup>
where a and r are real numbers, r is common ratio

basically f(x) = ar<sup>x</sup>

### Arithmetic Sequence (Linear)
a sequence that uses a linear function.
a, a+d, a+2d, ..., a+nd
where a and d are real numbers, d is common difference

basically f(x) = a+xd, example: y = mx + b

#### Sequences in ComSci

Finite sequences are called strings. Strings are denoted by a<sup>1</sup>a<sup>2</sup>...a<sup>n</sup>

The lenght of a string is the terms in the string (n)

The empty string, denoted by <tag>&lambda;</tag> (lambda), is a string with no terms.

### Recurrence Relation

Basically a recursive function.

A sequence is called a solution of a recurrence relation if its terms satisfy the recurrence relation.

*We need to know the a<sub>0</sub> of the function tho*

Example: a<sub>n</sub> = a<sub>n-1</sub> + 3 for n = 1,2,3,... a<sub>0</sub> = 2 (required)

# Summations

Basically a for loop

$$\sum_{j=m}^{n}a_j$$
For example:
$$\sum_{i=j}^{k}a_i$$
is a for loop (in terms of pseudocode)
``` cpp
int sum;
for (int i = j, i <= k, i++) {
	sum += a(i)
}
```

<tag>&Sigma;</tag> is called a Sigma (DUN, DUN DUN DUN DUN)

# Matrices
is a rectangular array of numbers (nD array).

A matric with m columns (up down) and n rows (left right) is called an m x n matrix.

A matrix where m = n is called a square.

## Arithmetic

### Addition

The sum of 2 matrices can only be added if m and n of the matrices are the same.

$$
\begin{pmatrix}
a1 & a2 \\
a3 & a4
\end{pmatrix}
 +
\begin{pmatrix}
b1 & b2 \\
b3 & b4
\end{pmatrix}
=
\begin{pmatrix}
a1+b1 & a2+b2 \\
a3+b3 & a4+b4
\end{pmatrix}
$$
Simple init fam yuhyuh

### Product

say matrices A is m x k matrix and B is k x n matrix. AB would have m x n.

Calc Method:
This is fucking wack, i understood but i aint explaining it

AB is not the same as BA.

### Transpose

The tranpose of matrix
$$
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{pmatrix}
->
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6
\end{pmatrix}
$$

### Symmetric Matrix

A square matrix A is called symmetric if A = A<sup>t</sup>. Thus A = [a<sub>ij</sub>] is symmetric if a<sub>ij</sub> = a<sub>ji</sub> for all i and j

m = n (required)
