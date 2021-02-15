.. _Phase_space_Lagrangian:

Mathematical Preliminaries
======================================
.. _Regular_derivation:

Infinite Series
-------------------

* Prove that if $\lim _{n \rightarrow \infty} n^{p} u_{n}=A<\infty, p>1,$ the series $\sum_{n=1}^{\infty} u_{n}$ converges.
* Prove that if $\lim _{n \rightarrow \infty} n u_{n}=A>0,$ the series diverges. (The test fails for $\left.A=0 .\right)$ These two tests, known as limit tests, are often convenient for establishing the convergence of a series. They may be treated as comparison tests, comparing with
$$
\sum_{n} n^{-q}, \quad 1 \leq q<p
$$

$\boxed{\textbf{Solution}}$ For $(a)$ Let 
$$\lim _{n \rightarrow \infty} n^{p} u_{n}=A<\infty, \quad p>1$$
Define 
$$
u_{n}=\frac{1}{n^{p}}, \quad  p>1
$$
be a series. Let 
$$
\lim _{m \rightarrow \infty} n^{p} u_{n}=A<\infty, \quad p>1
$$
then $\sum_{n=1}^{\infty} u_{n}$ is convergent by limit comparision test as 
$$
\lim _{n \rightarrow \infty} \frac{u_{n}}{u_{n}}=\lim _{n \rightarrow \infty} \frac{u_{n}}{1 / n^{p}}
$$
$$
=\lim _{n \rightarrow \infty} n^{p} u_{n}=A<\infty
$$
If $A\neq 0$ both, the series $\sum_{n=1}^{\infty} u_{n}$ and $\sum_{n=1}^{\infty} u_{n}$ behave alike as 
$$\sum_{n=1}^{\infty} u_{n} = \sum_{n=1}^{\infty} \frac{1}{n^{p}}$$ is convergent series. If $A\neq 0$ then by limit comparision test, if $
\sum_{n=1}^{\infty} u_{n}$ is convergent then $$\sum_{n=1}^{\infty} \frac{1}{n^p}, \quad p>1$$
is convergent by $p-$test. Therefore $\sum_{n=1}^{\infty} u_{n}$ is convergent series. 


