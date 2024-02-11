# Random Variable

A *random variable* is a [[function]] from the set of [[outcomes]] $\Omega$ to the reals. This is motivated by the fact that the result of every random experiment need not be a number, however it is useful to quantify the elements of the [[sample space]]. 

More precisely, a random variable $X : \Omega \mapsto \mathbb{R}$ is a [[measurable function]] such that every [[pre-image]] of finite / infinite volume is an [[event]], i.e.,

$$
X^{-1}([-\infty, a]) \in \varepsilon \quad \forall a \in \mathbb{R}. 
$$


A random variable $X: \Omega \mapsto \mathbb{R}$ translates the [[probability space]] $(\Omega, \varepsilon, P)$ to $(\mathbb{R}, \varepsilon_{X}, P_{X})$, where 

$$
\varepsilon_{X} := \{A \subseteq \mathbb{R} \,\, | \,\, X^{-1}(A) \in  \varepsilon\}
$$