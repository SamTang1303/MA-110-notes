---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-08-29
# Pre-Work Problems 1 Through 7 MA-110

> [!problem] Problem 1.1
> Which of the following are binary operations on the specified set? If not, explain why not.
> 1. Addition on $\mathbb{Z}$, the set of integers.
> 2. Subtraction on $\mathbb{Z}$, the set of integers.
> 3. Subtraction on $\mathbb{N}$, the set $\{ 1,2,3,\dots \}$ of natural numbers.
> 4. Division on $\mathbb{R}$, the set of real numbers.
> 5. Division on $\mathbb{Z}\setminus \{ 0 \}$.
> 6. Composition on [[D 4 - The group symmetries of a square]].
> 7. Composition on the set of rotations in [[D 4 - The group symmetries of a square]].
> 8. Multiplication modulo 6 on $\mathbb{Z}_{6}$.

1. Yes
2. Yes
3. No, $2-3 = -1 \notin \mathbb{N}$.
4. No: $\frac{1}{0}$ is undefined and therefore not in $\mathbb{R}$.
5. No: $1\div 4 \notin \mathbb{Z}\setminus \{ 0 \}$
6. Yes
7. Yes
8. Yes

> [!problem] Problem 1.2
> Refer back to those operations in Problem 1 that were binary operations. Do the following for each of these binary operations.
> 1. Determine whether the operation is associative, and if not, prove that the operation is not associative.
> 2. State whether there is an identity for the operation, and if so, identify it.
> 3. If there is an identity for the operation, determine any elements (if any) have inverses.

- Addition on $\mathbb{Z}$:
    1. Yes, it is associative.
    2. Yes, the identity for the operation is $0$.
    3. All elements of $\mathbb{Z}$ have inverses (their negative.)
- Subtraction on $\mathbb{Z}$:
    1. No, it is not associative. $(1-2)-3=-4\neq1-(2-3)=2$.
    2. Yes, the identity for the operation is $0$.
    3. All elements of $\mathbb{Z}$ have an inverses under subtraction (their negative.)
- Composition on [[D 4 - The group symmetries of a square]].
    1. Yes, $D_{4}$ is associative because it is a group.
    2. Yes, the identity is $\rho_{0}$.
    3. All elements of $D_{4}$ have inverses.
- Composition on the set of rotations in [[D 4 - The group symmetries of a square]].
    1. The set of rotations of $D_{4}$ is also a group, and therefore is associative.
    2. The identity of the set of rotations of $D_{4}$ is similarly $\rho_{0}$.
    3. All elements of the set of rotations of $D_{4}$ have inverses.
- Multiplication modulo 6 in $\mathbb{Z}_{6}$.
    1. Yes, it is associative.
    2. Yes, the identity for the operation is 1.
    3. Only. $1,5$  have inverse elements under multiplication modulo 6.

> [!problem] Problem 1.3
> Determine which of the binary operations in Problem 1 are commutative, and if not, provide proof that the operation is not commutative.

- Addition on $\mathbb{Z}$: Is commutative.
- Subtraction on $\mathbb{Z}$: Is not commutative. $1-2=-1\neq2-1$.
- Composition on [[D 4 - The group symmetries of a square]]: Is commutative.
- Composition on the set of rotations in [[D 4 - The group symmetries of a square]]: Is commutative.
- Multiplication modulo 6 in $\mathbb{Z}_{6}$: Is commutative.

> [!problem] Problem 1.4
> Prove that if a binary operation $*$ on a set $A$ has an identity element, then that identity element is unique.

Let $*$ be an operation on a set with identity elements $e_{1}$ and $e_{2}$. By definition of an identity,
$$
\begin{align}
e_{1} * e_{2} &= e_{1}\\
&\text{and}\\
e_{1} * e_{2} &= e_{2}\\
\end{align}
$$
Thus $e_{1}=e_{2}$, and the identity is unique.

> [!problem] Problem 1.5
> Which of the following are groups? If not, explain why not.
> 1. $\langle \mathbb{Z},+\rangle$
> 2. $\langle \mathbb{Z},-\rangle$
> 3. $\langle \mathbb{Z},\times \rangle$
> 4. $\langle \mathbb{Z},\div\rangle$
> 5. $\langle \mathbb{R}^{+}, \times \rangle$
> 6. The set of symmetries of a regular pentagon with operation composition.
> 7. $\mathbb{Z}_{6}$ with operation addition mod 6.
> 8. $\mathbb{Z}_{6}$ with operation multiplication mod 6.
> 9. $\mathbb{Z}_{6}\setminus \{ 0 \}$ with operation multiplication mod 6.
> 10. $\mathbb{Z}_{5}\setminus \{ 0 \}$ with operation multiplication mod 5.

^problem1-5

1. Is a group.
2. Is not a group. It is not associative.
3. Is not a group. There are no inverse elements.
4. Is not a group. There is no identity element, nor is it associative, nor does it have inverses.
5. It is a group.
6. It is a group.
7. It is a group.
8. It is not a group. $2,3,4$ all don't have inverses.
9. It is not a group for the same reason as 8.
10. It is a group.

> [!problem] Problem 1.6
> Prove that the following is, or is not a group, as appropriate. The set $\mathbb{R}\setminus \{ 1 \}$ with operation defined by $a*b=a+b-ab$ for all $a,b \in S$.

$\langle S,*\rangle$ is a group, with an identity element $0$ and and inverse, for any element $a \in S$, of $\frac{a}{a-1}$.

*Proof.* First notice that the $*$ operator is clearly commutative. Let $s \in S$. $0*s=s*0=s+0-0 \cdot s=s$. Therefore $0$ is the identity element.

Let $a,b \in S$ and suppose $b = \frac{a}{a-1}$.
$$
\begin{align}
a*b &= a + \frac{a}{a-1} - a  \cdot \frac{a}{a-1}\\
&= \frac{a^{2}-a}{a-1}+\frac{a}{a-1}-\frac{a^{2}}{a-1}\\
&= \frac{0}{a-1}\\
&= 0
\end{align}
$$
Thus, $b$ is the inverse of a, and every element of $S$ has an inverse. Note the last equality relies on $1$ being  from $S$, otherwise $\frac{0}{a-1}=0$ would not hold because the left hand side could be undefined.

Let $a,b,c \in S$.
$$
\begin{align}
(a * b) * c &= (a + b - ab) + c - c(a + b - ab)\\
&= a+b-ab+c-ac-bc+abc\\
&= a+b+c -ab -ac -bc + abc\\
a * (b*c) &= a + (b+c-bc) - a(b+c-bc)\\
&= a + b +c -bc -ab - ac +abc\\
&= a + b +c -ab - ac -ab + abc.
\end{align}
$$
Because these two quantities are equal, the operation is distributive and all of the criteria for a group have been satisfied.

> [!problem] Problem 1.7
> Prove that the following is, or is not a group, as appropriate: The set $M_{2}(\mathbb{R})$ of all 2 by 2 matrices, with real numbers as entries, and operation matrix multiplication.

^4bdde9

Let $M_{2}(\mathbb{R})$ be the set of all two by two matrices with real number entries along with the operation, $\cdot$ of matrix multiplication. Let $a,b,c,d \in \mathbb{R}$. Suppose
$$
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}^{-1}
$$
exists
$$
I =
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}=
\begin{align}
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
\cdot 
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix} 
=
\begin{bmatrix}
a + c & b + d \\
a + c & b+d
\end{bmatrix}
\end{align}.
$$
This is clearly a contradiction; the columns of the identity matrix cannot have the same value. Therefore, the given matrix has no inverse, and $M_{2}(\mathbb{R})$ is not a group.
