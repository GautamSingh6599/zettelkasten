---
title: Differentiable Functions
---
Start with an [[interval]] $L$. A [[function]] $f:J \mapsto \mathbb{R}$ is *differentiable* at a point $c \in J$ if the following [[limit]] exists

$$
\lim_{ x \mapsto c } \frac{f(x) - f(c)}{x - c}. 
$$
We denote this quantity as
$$
f'(c) = \lim_{ x \mapsto c } \frac{f(x) - f(c)}{x - c}. 
$$

More precisely, there exists $\alpha \in \mathbb{R}$ such that for any $\epsilon > 0$ there exists $\delta > 0$ so that the following conditions hold

$$
\forall x \in (c - \epsilon, c + \epsilon), \quad |f(x) - f(c) - \alpha(x - c)| < \epsilon \, |x - c|. 
$$
## Theorem 1

The following statement is equivalent to saying that a function $f$ is differentiable some $c \in J$. 

- Suppose that there exists a function $f_{1}: J \mapsto \mathbb{R}$ which satisfies the following condition 
$$
f(x) = f(c) + f_{1}(x)(x - c) \quad \forall x\in J.
$$
- Also $f_{1}$ is continuous at $c$.

Then $f$ is differentiable at $c$ and $f'(c) = f_{1}(c)$.

Also if $f_{1}$ and $f$ satisfy the above conditions then 
$$
f_{1}(x) = \frac{f(x) - f(c)}{x - c} \quad \text{for }x \neq c
$$
[[differentiable functions#Theorem 1| Theorem 1]] also shows that a differentiable function is also continuous.

We can also see that differentiability at a point is a local phenomenon (obviously!) and we need not know the function over it's whole domain. Just knowing the function over a neighbourhood suffices for our objective (which is to determine differentiability).