Suppose $f$ is a function on $[a, b]$. We call $f$ *convex* if an only if for all $t \in [a, b]$ and for all $x, y \in [a, b]$ $$
f(t x + (1 - t) y) \le tf(x) + (1 - t)f(y).
$$

## Theorem 1

A function $f$ over $[a, b]$ is convex if and only if the following holds true $$
\frac{f(z) - f(x)}{z - x} \le \frac{f(y) - f(x)}{y - x} \le \frac{f(y) - f(z)}{y - z}
$$
for all $x, y, z \in [a, b]$ and $x < z < y$.

## Theorem 2

A differentiable function $f$ is convex if and only if $f'$ is increasing.

## Theorem 3

A differentiable function $f$ is convex if and only if the following holds true
$$
f(x) \ge f(y) + f'(y) (x - y) \quad \forall x, y \in[a, b].
$$