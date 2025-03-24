## Câu 1
### a) 
Phương trình Schrodinger tổng quát cho hàm sóng $\Psi(x, t)$ là :
$$i \hbar \frac{\partial \Psi}{\partial t} = -\frac{\hbar^2}{2m} \frac{\partial^2\Psi}{\partial x^2} + V\Psi$$
### b)
Ý nghĩa hàm sóng theo cách diễn giải của Born là 
- $|\Psi(x,t)|^2$ cho ra xác suất tìm thấy của hạt tại điểm $x$ tại thời gian $t$. 
	Hay nói cách khác là 
	$$\int^a_{b}|\Psi(x,t)|^2 \, dx$$
	Là xác suất tìm thấy của thạt giữa điểm $a$ và $b$ tại thời gian $t$.
- Bình phương modulus là tích hai hàm sóng : 
$$\Psi*\Psi = |\Psi|^2$$
### c)
Điều kiện chuẩn hóa của hàm sóng :
$$\int _{-\infty}^{\infty} |\Psi(x,t)|^2 \, dx = 1$$
Theo ý nghĩa vật lý, không có điều kiện chuẩn hóa thì giải thích về mặt xác suất thống kê hay là modulus bình phương hàm sóng (theo cách diễn giải của Born) sẽ trở nên vô nghĩa.
### d)
Giá trị trung bình (giá trị kì vọng) là :
$$\frac{d\langle x\rangle}{dt} = -\frac{i\hbar}{m}\int\Psi* \frac{\partial \Psi}{\partial x} \, dx$$
Giá trị trung bình của động lượng là :
$$\langle p \rangle = m \frac{d\langle x\rangle}{dt} = -ih\int\Psi* \frac{\partial \Psi}{\partial x} \, dx$$
Giá trị trung bình của động năng là :
$$\langle T \rangle = - \frac{\hbar^2}{2m}\int\Psi* \frac{\partial^2\Psi}{\partial x^2} \,dx$$
## Câu 2
### a)
Phương trình Schrodinger không phụ thuộc thời gian cho hàm sóng $\Psi_{n}(x)$ là :
$$-\frac{\hbar^2}{2m} \frac{d^2\psi_{n}(x)}{dx^2} + V_{n}(x)\psi_{n}(x) = E_{n}\psi_{n}(x)$$
Mối quan hệ giữa $\Psi(x,t )$ và $\psi(x)$
$$\Psi(x,t) = \sum^\infty_{n = 1}c_{n}\psi_{n}(x)e^{-iE_{n}t/\hbar}$$
