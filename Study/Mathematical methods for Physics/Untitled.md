## Ví dụ : BTVN số 5
Đặt $u(x, y) = X(x) \cdot Y(y) \neq 0$
$$\begin{gather}
\frac{\partial^2(X\cdot Y)}{\partial x^2} +\frac{\partial^2(X\cdot Y)}{\partial y^2} = 0 \\
\Leftrightarrow Y\cdot X'' + X\cdot Y = 0 \\
 \frac{X''}{X} + \frac{Y''}{Y} = 0
 \end{gather}$$
 Đặt 
 $$\begin{cases}
\frac{X''}{X} = \lambda \\
\frac{Y''}{Y} = -\lambda
\end{cases}$$
$\implies X'' = X\lambda \Leftrightarrow k^2 = \lambda \Leftrightarrow \sqrt{ \lambda }$
Xét $\lambda > 0 \implies k^2 = k_{1} + k_{2}$
$$\begin{gather}
X(x) = A\sinh(\sqrt{ \lambda }x) + B\cosh(\sqrt{ \lambda }x) \\
X(0) = A\sinh(0) + B\cosh(0) = 0 \implies B = 0 \\
X(M) = A\sinh(M\sqrt{ \lambda }) = 0 \implies A = 0 \\
\implies X(x) = 0 >< 0 \implies \ \ \lambda > 0(\text{loại})
\end{gather}$$
Xét $\lambda = 0 \implies k_{1} = k_{2} = k$ 
$$\begin{gather}
X(x) = e^{kx}(Ax + B) = Ax + B
  \\
X(0) = A \cdot 0 + B = 0 \implies B = 0 \\
X(M) = A\cdot M = 0 \implies A = 0
 \\ \implies X(x) = 0 >< 0 \implies \ \ \lambda = 0(\text{loại})
\end{gather}$$
Xét $\lambda < 0 : k = \sqrt{ -\lambda }$
$$\begin{gather}
X(x) = (A\sin(\sqrt{ -\lambda } x) + B\cos(\sqrt{ -\lambda }x))e^{\alpha x}  \\
= A\sin(\sqrt{ -\lambda }x) + B\cos(\sqrt{ -\lambda }x) \\
X(0) = A\sin(0) + B\cos(0) = 0 \implies B = 0 \\
X(M) = A\sin(\sqrt{ -\lambda }M) = 0  \\
 \Leftrightarrow\begin{cases}
 A = 0  \\
\sqrt{ -\lambda }M = n\pi
\end{cases} \\
\implies \lambda = - \left( \frac{n\pi}{M} \right)^2
 \end{gather}$$
$$\begin{gather}
\frac{Y''}{Y} = -\lambda = \left( \frac{n\pi}{M} \right)^2 \Leftrightarrow k^2 = \left( \frac{n\pi}{M} \right)^2 \Leftrightarrow k = \pm \frac{n\pi}{M} \\
Y(y) = A\sinh\left( \frac{n\pi}{M}y \right) + B\cosh\left( \frac{n\pi}{M}y \right) \\
Y(0) = A\sinh(0) + B\cosh(0) = 0 \implies B = 0 \\
\implies Y(y) = A\sinh\left( \frac{n\pi}{M} y \right) \\
\implies u(x,y) = A_{1}\sin\left( \frac{n\pi}{M}x \right)  A_{2}\sinh\left( \frac{n\pi}{M}y \right) \\
= \sum ^\infty_{n = 1}C_{n}\sin\left( \frac{n\pi}{M}x \right)\sinh\left( \frac{n\pi}{M}y \right) \\
u(x, L) = \sum ^\infty_{n = 1}C_{n}\sin\left( \frac{n\pi}{M}x \right)\sinh\left( \frac{n\pi}{M}L \right) = 100  \\ 
= \sum ^\infty_{n = 1}B_{n}\sin\left( \frac{n\pi}{M}x \right)
\\
\int_{0}^MB_{n}\sin^2\left( \frac{n\pi}{M}x \right)\, dx = \int^M_{0} 100\cdot \sin\left( \frac{n\pi}{M}x \right) \, dx \\
\frac{B_{n}}{2}\left[ x - \frac{M\sin\left( \frac{2n\pi}{M}x \right)}{2\pi}|^M_{0} \right] = 100\left[ -\frac{M\cos\left( \frac{n\pi x}{M} \right)}{2\pi}|^M_{0}\right] \\
\frac{B_{n}}{2} M = 100\left[ - \frac{M\cos(n\pi )}{2\pi} + \frac{M}{2\pi} \right] \\
 \frac{B_{n}}{2}M =\frac{-100M\cos(n\pi) + 100M}{2\pi} = \frac{100M}{2\pi}(1 - (-1)^2) \\
\implies B_{n} = \frac{100}{\pi}(1 - (-1)^2) 
\end{gather}$$
### Ví dụ 2 
Cho $$\begin{gather}
 u_{xx} + 6u_{xy} + 5u_{yy} = 0 \\
\Delta = 3^2 - 5\cdot 1 = 0 (Hyperbol)
 \\
 \frac{dy}{dx} = \frac{3\pm4}{1} = 3\pm2  \\
\implies \begin{cases}
dy = 5dx \Leftrightarrow y = 5t + C \Leftrightarrow C = 5x -y  \\
dy = dx \Leftrightarrow y = x + C \Leftrightarrow C = x - y
\end{cases} \\
\end{gather}$$
Đặt $\xi = 5x - y, \eta = x - y$
$$\begin{gather}
\xi_{x} = 5, \xi_{xx} = \xi_{xy}= \xi_{yy} = 0, \xi_{y} = -1 \\
\eta_{x} = 1, \xi_{xx} = \xi_{xy}= \xi_{yy} = 0, \eta_{y} = -1
\end{gather}$$
$$\begin{gather}
u_{xx} = u_{\xi \xi}\xi^2_{x} + 2u_{\xi \eta}\xi_{x}\eta_{x} + u_{\eta \eta}\eta_{x}^2 + u_{\xi}\xi_{x x} + u_{\eta}\eta_{x x} \\
= u_{\xi \xi}\cdot5^2 + 2u_{\xi \eta}\cdot 5\cdot 1 + u_{\eta \eta}\cdot_{1}^2 + u_{\xi} \cdot 0 + u_{\eta}\cdot 0 \\
= 25u_{\xi \xi} + 10 u_{\xi \eta} + u_{\eta \eta} &(1)\\
u_{xy} = u_{\xi \xi}\xi_{x}\xi_{y} + u_{\eta \xi}(\xi_{x}\eta_{y} + \eta_{x}\xi_{y}) + u_{\eta \eta}\eta_{x}\eta_{y} + u_{\xi}\xi_{xy} + u_{\eta}\eta_{xy} \\
= u_{\xi \xi}\cdot 5 \cdot 1 + u_{\xi \eta}(5\cdot 1 + 1 \cdot 1) + u_{\eta \eta}\cdot1 \cdot 1 + u_{\xi} \cdot 0 + u_{\eta} \cdot 0 \\
= 5u_{\xi \xi} +6u_{\xi \eta} + u_{\eta \eta} & (2)\\
u_{yy} = u_{\xi \xi} \xi^2_{y} + 2u_{\xi \eta}\xi_{y}\eta_{y} + u_{\eta \eta}\eta^2_{y} + u_{\xi}\xi_{yy}+u_{\eta}\eta_{yy} \\
= 1^2 u_{\xi \xi} + 2u_{\xi \eta} \cdot 1 \cdot 1 + u_{\eta \eta}\cdot 1^2 + u_{\xi}\cdot 0 + u_{\eta} \cdot 0 \\
= 1u_{\xi \xi} + 2u_{\xi \eta} + u_{\eta \eta} & (3) \\
\end{gather}$$
Từ $(1), (2), (3)$ ta có : 
$$\begin{gather}
25u_{\xi \xi} + 10 u_{\xi \eta } + u_{\eta \eta} + 6\cdot (5u_{\xi \xi} + 6u_{\xi \eta} + u_{\eta \eta}) + 5\cdot (u_{\xi \xi} + 2 u_{\xi \eta} + u_{\eta \eta}) \\
= 25u_{\xi \xi} + 10 u_{\xi \eta}+u_{\eta \eta} + 30u_{\xi \xi} + 36u_{\xi \eta} + 6u_{\eta \eta} + 5u_{\xi \xi} + 10u_{\xi \eta} + 5u_{\eta \eta} \\
= 60u_{\xi \xi} + 56u_{\xi \eta} + 12u_{\eta \eta} = 0
\end{gather}$$
### Ví dụ : tìm nghiệm theo phương pháp D’Alembert
> [!NOTE] Đề bài
> $$\begin{gather}
u_{tt} = u_{x x} & -\infty \leq x \leq \infty
\end{gather}$$ 
> Điều kiện 
> $$\begin{gather} 
u(x, 0) = \sin(x) & -\infty \leq x \leq \infty \\
u_{t}(x, 0) = \cos(x) & -\infty \leq x \leq \infty \\
\end{gather}$$


$$\begin{gather}
C = 1 \\
u(x, 0) = \sin(x) = f(x) \\
u_{t}(x, 0) = \cos(x) = g(x) \\
\implies u(x, t) = \frac{1}{2}[\sin(x + ct) + \sin(x - ct)]+ \frac{1}{2C}\int^{x + ct}_{x - ct} \cos(\tau)\, d\tau \\
=\frac{1}{2}[\sin(x + t) + \sin(x - t)] + \frac{1}{2}[\sin(\tau)|^{x + t}_{x - t}] \\
= \frac{1}{2}[\sin(x + t) + \sin(x - t)] + \frac{1}{2}[\sin(x + t) - \sin(x - t)] \\
= \sin(x + t)
\end{gather}$$
### Ví dụ : Chuỗi fourier 
cho hàm $$\begin{gather}
f(x) & -\pi \leq x \leq \pi
\end{gather}$$
ta có : 
$$f(-x) = -x = - f(x) $$
Vậy ta có $f(x)$ là hàm lẻ
$$\begin{gather}
a_{0} = a_{n} = 0 \\
b_{n} = \frac{2}{L}\int^L_{0}f(x)\sin\left( \frac{n\pi}{L}x \right)\, dx
\end{gather}$$
Đặt 
$$
\begin{gather}
\begin{cases}
u = x \\
dv = \sin(nx)\, dx
\end{cases}\Leftrightarrow \begin{cases}
du = dx  \\
v = \frac{\cos(nx)}{n}
\end{cases}
\\
\implies x \cdot \frac{\cos(nx)}{n}|^\pi_{-\pi} - \int^\pi_{-\pi}\frac{\cos(nx)}{n}\, dx \\
\frac{\pi(\cos(\pi n) - \cos(-Ln))}{n} - \frac{\sin(nx)}{n^2}|^\pi_{-\pi} \\
\frac{2\pi\cos(\pi n)}{n} - \frac{2\sin(\pi n)}{n^2}
\end{gather}$$
