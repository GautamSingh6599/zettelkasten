---
title: Algebra of Differentiable Functions
---
Suppose that we have two real valued functions $f, g$ over an interval $J$  that are [[differentiable functions|differentiable]] at some $c \in J$. Then $f, g$ satisfy several algebraic properties

- The sum of two differentiable functions is differentiable 
$$
(f + g)'(c) = f'(c) + g'(c)
$$
- If $\alpha$ is a real number then $\alpha f$ is differentiable and 
$$
(\alpha f)'(c) = \alpha f'(c)
$$
- The product of two differentiable functions is also differentiable 
$$
(fg)'(c) = f(c)g'(c)+ f'(c)g(c)
$$
- If a function $f$ is never equal to zero and is differentiable then $1 \backslash f$ is also differentiable 
$$
\left(\frac{1}{f} \right)'(c) = - \frac{f'(c)}{f(c)^2} 
$$

## Chain Rule

Suppose $f$ is a function over the interval $J$ that is differentiable at some $c \in J$ . Similarly $g$ is a function over the set $J_{1}$ such that $f(J) \subseteq J_{1}$ and $g$ is differentiable over $f(c)$ then
$$
(g \circ f)'c = g'(f(c))f'(c)
$$