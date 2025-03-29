## 1 DIMENSION INFINITY SQUARE WELL PROBLEM
### Side conditional.
---
#### Outside the potential $(x < 0, x > a)$.
$$\psi(0) = \psi(a) = 0$$
#### Inside the potential $(0 < x < a), V(x) = 0$
	$$-\frac{\hbar^2}{2m} \frac{d^2\psi}{dx^2} = E\psi$$
	$$\implies \frac{d^2\psi}{dx^2} = -k^2\psi \ k \equiv \frac{\sqrt{ 2mE }}{\hbar}$$
### Root.
---
	$$\psi(x) = A\sin(kx) + B\cos(kx)$$

Continuous condition of $\psi(x)$ at $x = 0$ and $a$ for root $\psi(0) = \psi(a) = 0$
$$\psi(0) = A\sin(0) + B\cos(0) = 0 \to B = 0$$
$$\implies \psi(x) = A\sin(kx) \implies \psi(a) = A\sin(ka) = 0$$
$$\Leftrightarrow \begin{cases}
A = 0  \\
\sin(ka) = 0 \implies k = \pm n\pi
\end{cases}$$
$$k = 0 \implies \psi(x) = 0$$ 
$\sin(-\theta) = -\sin(\theta)$ and “-” depend on $A$ 
	 $$\implies k_{n} = \frac{n\pi}{a} \ (n = 1,2,3,\dots)$$
	 $$k = \frac{\sqrt{ 2mE }}{\hbar} \implies k_{n} = \frac{\sqrt{ 2mE_{n} }}{\hbar}$$
	 $$\implies E_{n} = \frac{\hbar^2k_{n}^2}{2m} = \frac{\hbar^2n^2\pi^2}{2ma^2}$$
### Normalization.
---
$$\psi(x) = A\sin(kx)$$
#### Normalization coditions
$$\int^a_{0} |A|^2\sin^2(kx)\, dx = |A|^2 \frac{a}{2} = 1 \implies |A|^2 = \frac{2}{a}$$
> $$\psi_{n}(x) = \sqrt{ \frac{2}{a} }\sin\left( \frac{n\pi}{a}x \right)$$

