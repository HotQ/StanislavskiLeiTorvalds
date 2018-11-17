# Bernoulli distribution
___
## Definition

If $X$ is a random variable with this distribution, we have:
$$\begin{aligned}
    Pr(X=1)&=p \\
    Pr(X=0)&=q=1-p 
\end{aligned}$$

The <u>probability mass function</u> $f$ of this distribution, over possible outcomes $k$, is
$$\begin{aligned}
    f(k;p) &= {\begin{cases}p&{\text{if }}k=1,\\[6pt]1-p&{\text{if }}k=0.\end{cases}} \\
    \\
    &=p^{k}(1-p)^{1-k} &{\text{for }}k\in \{0,1\} \\
    \\
    &=pk+(1-p)(1-k) &{\text{for }}k\in \{0,1\}
\end{aligned}$$

