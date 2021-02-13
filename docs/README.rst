====================
 FM1
====================


Rewrite Stirling's series to give $\Gamma(z+1)$ instead of $\ln \Gamma(z+1)$
$$
\text { ANS. } \quad \Gamma(z+1)=\sqrt{2 \pi} z^{z+1 / 2} e^{-z}\left(1+\frac{1}{12 z}+\frac{1}{288 z^{2}}-\frac{139}{51,840 z^{3}}+\cdots\right)
$$

Consider the Stirling's formula: 
$$\ln \Gamma(z+1)=\frac{1}{2} \ln 2 \pi+\left(z+\frac{1}{2}\right) \ln z-z+\sum_{n=1}^{\infty} \frac{B_{2 n}}{2 n(2 n-1) z^{2 n-1}}$$
Where $B_{2 n}$ are the Bernoulli's numbers. Use the first few Bernoulli's numbers and rewrite the above Stirling's formula as equivalent to
$$\ln \Gamma(z+1) \sim \frac{1}{2} \ln (2 \pi)+\left(z+\frac{1}{2}\right) \ln z-z+\frac{1}{12 z}-\frac{1}{360 z^{2}}+\frac{1}{1260 z^{3}}-\ldots$$
The Stirling's formula can be rewritten using Gamma function as follows.
Let us take exponential form and collect similar terms to get equivalent form as follows.
$$
\Gamma(z+1) \sim \sqrt{2 \pi}+z^{\left(z+\frac{1}{2}\right)} e^{-z}\left(1+\frac{1}{12 z}+\frac{1}{288 z^{2}}-\frac{139}{51840 z^{3}}+\ldots\right)
$$
Hence, the required result is $$\Gamma(z+1) \sim \sqrt{2 \pi}+z^{\left(z+\frac{1}{2}\right)} e^{-z}\left(1+\frac{1}{12 z}+\frac{1}{288 z^{2}}-\frac{139}{51840 z^{3}}+\ldots\right)$$

=============
Ejemplo 2
=============

Test the convergence
$$
\sum_{p=0}^{\infty}\left[\frac{\Gamma\left(p+\frac{1}{2}\right)}{p !}\right]^{2} \frac{2 p+1}{2 p+2}=\pi \sum_{p=0}^{\infty} \frac{(2 p-1) ! !(2 p+1) ! !}{(2 p) ! !(2 p+2) ! !}
$$
This series arises in an attempt to describe the magnetic field created by and enclosed by a current loop.

Consider the series obtained in the magnetic field created by and enclosed by a current loop:
$$
\sum_{p=0}^{\infty} \frac{\Gamma\left(p+\frac{1}{2}\right)}{p !}\left(\frac{2 p+1}{2 p+2}\right)=\pi \sum_{p=0}^{\infty} \frac{(2 p-1) ! !(2 p+1) ! !}{(2 p) ! !(2 p+2) ! !}
$$
Now, we will test the convergence of the series using Stirling asymptotic formula given by
$$
\Gamma(z+1) \sim \sqrt{2 \pi} z^{z+\frac{1}{2}} e^{-z}
$$
$$
\frac{\Gamma\left(p+\frac{1}{2}\right)}{\Gamma(p+1)} \sim \sqrt{e} \frac{\left(\frac{p+\frac{1}{2}}{p+1}\right)^{p+\frac{1}{2}}}{\Gamma(p+1)}
$$
$$
=\frac{\text { constant }}{\Gamma(p+1)}
$$
Hence, the series converges.



