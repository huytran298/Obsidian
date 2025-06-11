<center><h2>Họ và tên : Trần Quốc Huy</h2>

<h3>MSSV : 23230005</h3>
<h4>Bài tập về nhà - Các phương pháp toán lý</h4>
</center>

Ta có phương trình nhiệt dừng trên tọa độ 2 chiều như sau :
$$\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2u}{\partial y^2} = 0$$
Điều kiện biên :
- $u(x, M) = 100^{\circ}$
-  $u(0, y) = u(x, 0) = u(L, y) = 0$
Giả sử :

$$u(x, y) = X(x)Y(y) \ (X(x)\neq 0)$$
$$\implies \frac{\partial^2}{\partial x^2}(XY) +\frac{\partial^2}{\partial y^2}(XY)  = YX'' + XY''  = \frac{X''}{X} + \frac{Y''}{Y} = 0$$
Đặt :
$$\begin{cases}
\frac{X''}{X} = \lambda \\
\frac{Y''}{Y} = -\lambda
\end{cases}$$
$$\implies X'' = \lambda X \implies k^2 = \lambda$$
Với $\lambda > 0, k_{1} = -k_{2} = k$
$$X(x) = A_{1} \sinh(\sqrt{ \lambda }x) + B_{1}\cosh(\sqrt{ \lambda }x)$$
$$\implies X(0) = A_{1}\sinh(0) + B_{1}\cosh(0) \implies B = 0$$
$$X(L) = A_{1}\sinh(\sqrt{ \lambda }L) = 0 \implies A = 0$$
$$X(x,y) = 0 >< 0 \implies \lambda>0 (\text{loại})$$
Với $\lambda = 0, k = k_{12} = 0$
$$X(x) = (A_{1}x + B_{1})e^{0\cdot x} = A_{1}x + B_{1}$$
$$X(0) = A_{1}\cdot 0 + B_{1} = 0 \implies B_{1} = 0$$
$$X(L) = A_{1}\cdot L = 0 \implies A_{1} = 0$$
$$X(x,y) = 0 >< 0 \implies \lambda>0 (\text{loại})$$
Với $\lambda < 0, k^2 = -1 \cdot \lambda \implies k = i\sqrt{ \lambda }$
$$X(x) = (A_{1} \sin \beta x + B_{1}\cos \beta x)e^{0\cdot x} = A_{1} \sin \sqrt{ \lambda } x + B_{1}\cos \sqrt{ \lambda } x$$
$$X(0) = A_{1}\sin 0 + B_{1}\cos 0 \implies B_{1} = 0$$
$$X(L) = A_{1}\sin L\sqrt{ \lambda } = 0$$
$$\begin{cases}
A_{1} = 0 \implies X(x,y) = 0 >< 0 \implies \lambda>0 (\text{loại})\\
\sin L\sqrt{ \lambda } = 0 \implies L\sqrt{ \lambda } = n\pi \Leftrightarrow \lambda = \left( \frac{n\pi}{L} \right)^2
\end{cases}$$
$$\implies X(x) = A_{1}\sin\left( \frac{n\pi x}{L} \right)$$
$$\implies Y'' = -\left( \frac{n\pi}{L} \right)^2Y$$
$$\implies k = \pm \frac{n\pi}{L}$$
$$Y(y) = A_{2}\sinh\left( \frac{n\pi y}{L} \right) + B_{2}\cosh\left( \frac{n\pi y}{L} \right)$$
$$Y(M) = A_{2}\sinh\left( \frac{n\pi y}{L} \right) + B_{2}\cosh\left( \frac{n\pi y}{L} \right) = 100$$$$Y(0) = A_{2}\sinh\ 0 + B_{2}\cosh\ 0 = 0 \implies B_{2} = 0$$
$$\implies Y(y) = A_{2}\sinh \frac{n\pi y}{L}$$
Từ $u(x, y) = X(x)Y(y)$ ta có :

$$u(x, y) = A_{1}\sin\left( \frac{n\pi x}{L} \right)A_{2}\sinh \left(\frac{n\pi y}{L}\right)$$
Xây dựng chuỗi Fourier ta có : 
$$\sum^\infty_{n = 1}  A_{1}\sin\left( \frac{n\pi x}{L} \right)A_{2}\sinh \left(\frac{n\pi y}{L}\right)$$
