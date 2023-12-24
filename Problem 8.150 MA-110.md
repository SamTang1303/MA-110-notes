---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.150 MA-110

> [!problem] Problem 8.150
> Revisit [[Problem 8.145 MA-110|Problem 145]]. Write the greatest common divisor of $f(x)=x^{4}2x^{3}+2x+1$ and $g(x)=x^{3}+2x^{2}+x+2$ in $\mathbb{Z}_{3}[x]$ as a linear combination of $f$ and $g$. Is $g+(f)$ a unit in $\mathbb{Z}_{3}[x]/(f)$.

> [!warning] This is very wrong. It is based on the wrong $\gcd$ for $f$ and $g$.

We found that the $\gcd$ of $f$ and $g$ from Problem 145 is -3. Back substituting gives
$$
\begin{align}
-3 &= (-x^{2}+1)-\left( \frac{x}{2}+1 \right)(2x+4) \\
&= (-x^{2}+1)-\left( \frac{x}{2}+1 \right)(g-(x-2)(-x^{2}+1)) \\
&= (-x^{2}+1)+\left( \frac{x}{2}+1 \right)(x-2)(-x^{2}+1) -\left( \frac{x}{2}+1 \right)g \\
&= (-x^{2}+1)\left( 1 + \left( \frac{x}{2}+1 \right)(x-2) \right) - \left( \frac{x}{2}+1 \right)g \\
&= (f-xg)\left( 1+\left( \frac{x}{2}+1 \right)(x-2) \right) - \left( \frac{x}{2}+1 \right)g \\
&= f\left( 1+\left( \frac{x}{2}+1 \right)(x-2) \right) - xg\left( 1+\left( \frac{x}{2}+1 \right)(x-2) \right) - \left( \frac{x}{2}+1 \right)g \\
&= f\left( \frac{x^{2}}{2}+1 \right)-g\left( x\left( \frac{x}{2}^{2}+1 \right) -\frac{x}{2}\right) \\
&= f\left( \frac{x^{2}}{2} + 1 \right) - g\left( \frac{x^{3}}{2} + \frac{x}{2} \right).
\end{align}
$$
[[Problem 8.141 MA-110|Problem 141]] tells us $g+(f)$ will be a unit in $\mathbb{Z}_{3}[x]/(f)$ because $g$ is relatively prime to $f$.