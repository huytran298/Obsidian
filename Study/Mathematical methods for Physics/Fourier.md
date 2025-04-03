### Chuỗi Fourier
Dao động có chu kì : $T = 2L \ \in(-L, L)$
$$f(x) = a_{0} + \sum^\infty_{n = 1}\left( a_{n}\cdot \cos\left( \frac{n\pi x}{L} \right)  + b_{n}\sin\left( \frac{n\pi x}{L} \right)\right)$$
Trong đó :
$$a_{0} = \frac{1}{2L}\int^L_{-L}f(x)\,dx$$
$$a_{n} = \frac{1}{L}\int^L_{-L}f(x)\cos\left( \frac{n\pi x}{L}\right)\, dx$$
$$b_{n} = \frac{1}{L}\int^L_{-L}f(x)\sin\left( \frac{n\pi x}{L}\right)\, dx$$
#### Ví dụ
Cho $f(x) = f(x + 2\pi)$
$$f(x) = \begin{cases}
x & 0 \leq x \leq \pi \\
0 & -\pi \leq x \leq 0
\end{cases}$$
$\implies T = 2\pi, L = \pi$
$$a_{0} = \frac{1}{2\pi}\int^\pi_{-\pi}f(x)\, dx = \frac{1}{2\pi}\left[ \int^0_{-\pi} 0dx + \int^\pi_{0} x \, dx \right] = \frac{\pi}{4}$$
$$a_{n} = \frac{1}{\pi}\int^\pi_{-\pi}f(x)\cos(nx)\, dx $$
$$\begin{align}
= \frac{1}{\pi}\left[ \int^0_{-\pi} 0dx + \int^\pi_{0} x\cos(nx) \, dx \right] \\
= \frac{1}{\pi}\left[ \frac{x\sin(nx)}{n}|^\pi_{0} - \int^\pi_{0} \frac{\sin(nx)}{n} \,dx \right] \\ \\
= \frac{1}{\pi}\left[ \frac{\pi \sin(n\pi)}{n} - \left( -\frac{\cos(nx)}{n^2} \right)|^\pi_{0} \right]\\ \\
= \frac{1}{\pi}\left[ \frac{\pi \sin(n\pi)}{n} + \frac{\cos(n\pi)}{n^2} - \frac{1}{n^2} \right] \\
= \frac{(-1)^n - 1}{\pi n^2 }
\end{align}$$
$$\begin{align}
b_{n} = \frac{1}{\pi}\int^\pi_{-\pi} f(x)\sin(nx)\, dx  \\
= \frac{1}{\pi}\left[ \int_{-\pi}^0 0\, dx + \int^\pi_{0}x \sin(nx)\, dx\right] \\
= \frac{1}{\pi}\left[-\frac{x\cos(nx)}{n}|^\pi_{0} + \int^\pi_{0} \frac{\cos (nx)}{n}\, dx\right] \\
= \frac{1}{\pi}\left[ -\frac{\pi \cos(nx)}{n} + \frac{\pi}{n} +  \frac{\sin(nx)}{n^2}|^\pi_{0}\right]  \\
= -\frac{(-1)^n}{n} + \frac{1}{n} = \frac{1-(-1)^n}{n}
\end{align}$$
$$\implies f(x) = \frac{\pi}{4} + \sum^\infty_{n = 1} \frac{(-1)^n - 1}{\pi n^2 }\cos(nx) + \frac{1-(-1)^n}{n} \sin(nx)$$
### Tính chẵn lẻ
- chẵn * chẵn = chẵn
- lẻ * chẵn = lẻ
- lẻ * lẻ = chẵn

| f(x)    | Chẵn                                                              | Lẻ                                                                 |
| ------- | ----------------------------------------------------------------- | ------------------------------------------------------------------ |
| $a_{0}$ | $\frac{1}{L}\int^L_{0}f(x)$                                       | 0                                                                  |
| $a_{n}$ | $\frac{2}{L}\int L_{0}f(x)\cos\left( \frac{n\pi}{L} \, dx\right)$ | 0                                                                  |
| $b_{n}$ | 0                                                                 | $\frac{2}{L}\int^L_{0}f(x)\sin\left( \frac{n\pi x}{L} \right)\,dx$ |
#### Ví dụ
Cho hàm :
$$f(t) = \begin{cases}
1 & 0 \leq t \leq \pi  \\
-1 & -\pi\leq t \leq 0
\end{cases}$$
Có : $T = 2\pi \ \in (-\pi, \pi), L = \pi$
$$f(-t) = \begin{cases}
1 & 0 \leq -t \leq t \\
-1 & -\pi\leq t \leq 0
\end{cases} \Leftrightarrow f(-t) = \begin{cases}
1 & -\pi \leq t \leq 0 \\
-1 & 0 \leq t \leq \pi
\end{cases}$$
$$\implies f(-t) = -f(t) \ \text{ là hàm lẻ}$$
$$\implies a_{0} = a_{n} = 0, b_{n} = \int^\pi_{0}f(x)\sin(nx)dx $$
$$= -\frac{2}{n\pi}[\cos(n\pi) - 1]$$
$$\implies f(t) = \frac{\sum^\infty_{n = 1}2}{\pi n}(1 - (-1)^n)\sin(nx)$$