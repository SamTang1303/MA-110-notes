---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.112 MA-110

> [!problem] Problem 7.112
> The ring $\mathbb{Z}_{2}[x]/(x^{2})$ has four elements. List them, and make an addition and multiplication table. Is this ring isomorphic to any other rings that you have seen before?

Any term with degree greater than two has a factor of $x^{2}$, meaning it is in $(x^{2})$ and will get absorbed if it is part of a coset representative of $(x^{2})$. Thus, none of our elements can have greater than degree two. This leaves us with only four possible options left in $\mathbb{Z}_{2}[x]$.
$$
\mathbb{Z}_{2}[x]/(x^{2}) =\{ 0+(x^{2}), 1+(x^{2}), x+(x^{2}), (x+1) + (x^{2}) \}.
$$
Note: The $+(x^{2})$ is omitted in all the following (i.e. $0+(x^{2})$ is written simply as $0$), because it applies to every given term.

| $+$ |$0$  |$1$  |$x$  |$x+1$|
| -------- | --- | --- | --- | --- |
|$0$       |$0$  |$1$  |$x$  |$x+1$|
|$1$       |$1$  |$0$  |$x+1$|$x$  |
|$x$       |$x$  |$x+1$|$0$  |$1$  |
|$x+1$     |$x+1$|$x$  |$1$  |$0$  | 

| $\times$ |$0$  |$1$  |$x$  |$x+1$|
| -------------- | --- | --- | --- | --- |
|$0$             |$0$  |$0$  |$0$  |$0$  |
|$1$             |$0$  |$1$  |$x$  |$x+1$|
|$x$             |$0$  |$x$  |$0$  |$x$  |
|$x+1$           |$0$  |$x+1$|$x$  |$1$  | 

This ring is isomorphic to the subring $\{ 0,3,6,9 \}$ of $\mathbb{Z}_{12}$ with addition and multiplication modulo twelve. The elements map as follows:
$$
\begin{align}
0 &\mapsto 0+(x^{2})\\
9 &\mapsto 1 + (x^{2}) \\
6 &\mapsto x + (x^{2}) \\
3 &\mapsto x+1 + (x^{2}).
\end{align}
$$
