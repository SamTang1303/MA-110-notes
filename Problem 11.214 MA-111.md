---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.214 MA-111

> [!problem] Problem 11.214
> Use Theorem 11.4 to find a basis for $\mathbb{Q}(\sqrt[3]{2  },\sqrt{ 3 })$ as a vector space over $\mathbb{Q}$. Justify your answer. Use this basis to find an element $\alpha$ such that $\mathbb{Q}(\alpha)=\mathbb{Q}(\sqrt[3]{ 2 }, \sqrt{ 3 })$.

The field $\mathbb{Q}(\sqrt[3]{ 2 })$ is a vector space of dimension three over $\mathbb{Q}$ and the field $\mathbb{Q}(\sqrt{ 3 })$ is a vector space of dimension two over $\mathbb{Q}$. Because $\mathbb{Q}(\sqrt[3]{ 2 },\sqrt{ 3 })$ is a field extension of both $\mathbb{Q}(\sqrt[3]{ 2 })$ and $\mathbb{Q}(\sqrt{ 3 })$, as a vector space over $\mathbb{Q}$ it must be a multiple of both two and three by the Degree Multiplication Theorem. Thus, $\mathbb{Q}(\sqrt[3]{ 2 },\sqrt{ 3 })$ must have a dimension of at least six as a vector space over $\mathbb{Q}$. The Degree Multiplication Theorem says that as a vector space over $\mathbb{Q}(\sqrt[3]{ 2 })$, $\mathbb{Q}(\sqrt[3]{ 2 },\sqrt{ 3 })$ must have dimension $>1$. This implies that $\sqrt{ 3 } \notin \mathbb{Q}(\sqrt[3]{ 2 })$. Thus, $\text{Irr}(\sqrt{ 3 },\mathbb{Q}(\sqrt[3]{ 2 }))=x^{2}-3$ and $\{ 1,\sqrt{ 3 } \}$ is a basis for $\mathbb{Q}(\sqrt[3]{ 2 },\sqrt{ 3 })$ as a vector space over $\mathbb{Q}(\sqrt[3]{ 2 })$.

Using the Degree Multiplication Theorem, $\mathbb{Q}(\sqrt[3]{  2},\sqrt{ 3 })$ will have a basis of
$$
\{ 1 \cdot 1,1 \cdot \sqrt{ 3 }, \sqrt[3]{ 2 } \cdot 1,\sqrt[3]{ 2 }\sqrt{ 3 },\sqrt[3]{ 4 } \cdot 1,\sqrt[3]{ 4 } \cdot \sqrt{ 3 } \}.
$$

Consider $\mathbb{Q}(\alpha)$ where $\alpha=\sqrt{ 3 } + \sqrt[3]{ 2 }$.
$$
\begin{align}
\alpha &= \sqrt{ 3 }+\sqrt[3]{ 2 } &&\in  \mathbb{Q}(\alpha )\ \\
(\sqrt{ 3 }+\sqrt[3]{ 2 })^{2} &= 9 + 2\sqrt{ 3 }\sqrt[3]{ 2 }+\sqrt[3]{ 4 } && \in  \mathbb{Q}(\alpha ) \\
&2\sqrt{ 3 }\sqrt[3]{ 2 }+\sqrt[3]{ 4 } && \in  \mathbb{Q}(\alpha ) \\
(2\sqrt{ 3 }\sqrt[3]{ 2 }+\sqrt[3]{ 4 })^{2}&= 12\sqrt[3]{ 4 }+8\sqrt{ 3 }+2\sqrt[3]{ 2 } && \in  \mathbb{Q}(\alpha ) \\
12\sqrt[3]{ 4 }+8\sqrt{ 3 }+2\sqrt[3]{ 2 } - 8(\sqrt{ 3 }+\sqrt[3]{ 2 }) &= 12\sqrt[3]{ 4 }-6\sqrt[3]{ 2 } && \in  \mathbb{Q}(\alpha ) \\
(2\sqrt[3]{ 4 }-\sqrt[3]{ 2 })^{2} &= 8\sqrt[3]{ 2 }-8+\sqrt[3]{ 4 } &&\in  \mathbb{Q}(\alpha ) \\
(2\sqrt[3]{ 4 }-\sqrt[3]{ 2 }) -2(\sqrt[3]{ 4 }+8\sqrt[3]{ 2 }) &= -17\sqrt[3]{ 2 } && \in  \mathbb{Q}(\alpha ) \\
&\sqrt[3]{ 2 } && \in  \mathbb{Q}(\alpha ) \\
(\sqrt[3]{ 2 })^{2}&=\sqrt[3]{ 4 } && \in  \mathbb{Q}(\alpha ) \\
(\sqrt{ 3 }+\sqrt[3]{ 2 })-\sqrt[3]{ 2 } &= \sqrt{ 3 } && \in  \mathbb{Q}(\alpha ) \\
&\sqrt{ 3 }\sqrt[3]{ 2 }  && \in  \mathbb{Q}(\alpha )\\
&\sqrt{ 3 }\sqrt[3]{ 4 }  && \in  \mathbb{Q}(\alpha ).
\end{align}
$$
Thus, $\mathbb{Q}(\sqrt{ 3 }+\sqrt[3]{ 2 })$ entirely contains the basis for $\mathbb{Q}(\sqrt{ 3 },\sqrt[3]{ 2 })$.  Clearly $\mathbb{Q}(\sqrt{ 3 },\sqrt[3]{ 2 })$ contains $\sqrt{ 3 }+\sqrt[3]{ 2 }$, so the two fields must be the same set.

