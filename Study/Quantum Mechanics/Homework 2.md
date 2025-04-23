<center><h2>Họ và tên : Trần Quốc Huy</h2>

<h3>MSSV : 23230005</h3>
<h4>Bài tập về nhà - Cơ lượng tử</h4>
</center>
## Bài 1
### a)
Từ điều kiện chuẩn hoá và trực giao hàm sóng ta có 
$$\int^\infty_{-\infty} |\psi(x)|^2 \, dx = \left| \frac{1}{\sqrt{ 6 }}\right|^2 + \left| \frac{-i}{\sqrt{ 6 }}\right|^2 + |A|^2 = 1$$
- $\left| \frac{1}{\sqrt{ 6 }}\right|^2 = \frac{1}{6}$
- $\left| \frac{-i}{\sqrt{ 6 }}\right|^2 = \frac{1}{6}$
Thay vào phương trình ta có 
$$\frac{1}{6} + \frac{1}{6} +|A|^2 = 1 \Leftrightarrow |A|^2 = \frac{2}{3} \implies A = \sqrt{ \frac{2}{3} }$$
### b)
Ta có hàm Schrodinger phụ thuộc theo thời gian là 
$$\begin{gather}
\Psi(x,t) = \sum^\infty_{n = 1}c_{n} \psi(x)e^{iE_{n}t/\hbar}  \\
= \frac{1}{\sqrt{ 6 }}\psi_{1}(x)e^{iE_{1}t/\hbar} -\frac{i}{\sqrt{ 6 }}\psi_{2}(x)e^{-iE_{2}t/\hbar} + \sqrt{ \frac{2}{3}}\psi_{3}(x)e^{iE_{3}t/\hbar}
\end{gather}$$
$$\begin{gather}
|\Psi(x, t)|^2 = (c_{1}\psi_{1}e^{iE_{1}t/\hbar}+c_{2}\psi_{2}e^{iE_{2}t/\hbar} + c_{3}\psi_{3}e^{iE_{3}t/\hbar}) \\
(c_{1}\psi_{1}^*e^{-iE_{1}t/\hbar}+c_{2}\psi_{2}^*e^{-iE_{2}t/\hbar} + c_{3}\psi_{3}^*e^{-iE_{3}t/\hbar})  
 \\ 
 =c_{1}^2|\psi_{1}|^2+c_{2}^2|\psi_{2}|^2 +c_{3}^2|\psi_{3}|^2 + \sum_{n \neq m}2c_{n}c_{m}^*\psi_{n}
\psi_{m}^*\cos\left( \frac{E_{n}-E_{m}}{\hbar}t \right) \\
=\frac{1}{6}|\psi_{1}|^2 + \frac{1}{6}|\psi_{2}|^2+\frac{2}{3}|\psi_{3}|^2 + \frac{2}{3}\psi_{1}\psi_{3}\cos\left( \frac{E_{1} - E_{3}}{\hbar}t \right) \end{gather}$$

### c)
Biểu thức giá trị kì vọng :
$$\begin{gather}
\langle x \rangle = \int_{-\infty}^\infty x|\psi_{n}|^2\,dx \\ \\
\end{gather}$$
Vì hạt xét trong giếng thế nên ta có :
$$\begin{gather}
\psi_{n} = \sqrt{\frac{2}{b} }\sin\left( \frac{n\pi x}{b} \right)
\end{gather}$$
Từ đó ta có :
$$\begin{gather}
\langle x \rangle = \int_{0}^b\psi^*(x)(x)\psi(x)\, dx \\
= \int_{0}^b\left[ \sqrt{ \frac{2}{b} } \sin\left( \frac{n\pi x}{b} \right)\right](x)\left[ \sqrt{ \frac{2}{b} }\sin\left( \frac{n\pi x}{b} \right) \right]\, dx \\
=\frac{2}{b}\int_{0}^bx\sin^2\left( \frac{n\pi x}{b} \right)\, dx =\frac{2}{b}\int_{0}^b \frac{x}{2}\left( 1 - \cos\left( \frac{2\pi xn}{b} \right) \right)\, dx\\
=\frac{1}{b}\left[ \int_{0}^b x \,dx - \int_{0}^b x\cos\left( \frac{2n\pi x}{b} \right)\, dx\right] \\
=\frac{1}{b}\left[ \frac{b^2}{2} - \frac{xb\sin\left( \frac{2n\pi x}{b} \right)}{2n\pi}|^b_{0} - \int_{0}^b \frac{b\sin\left( \frac{2\pi n x}{b} \right)}{2\pi n}\,dx\right] \\
=\frac{1}{b}\left[ \frac{b^2}{2} - \frac{b^2\sin\left( 2n\pi \right)}{2n\pi } + \frac{b^2\cos\left( \frac{2n\pi x}{b} \right)}{4n^2\pi^2}|^b_{0}\right] \\
= \frac{1}{b}\left[ \frac{b^2}{2} - \frac{b^2\sin\left( 2\pi n \right)}{2\pi n}+ \left(\frac{b^2\cos(2n\pi)}{4n^2\pi^2}-\frac{b^2}{4n^2\pi^2}\right) \right] \\
=\frac{b}{2}-\frac{b}{2\pi n}\cdot(0) + \left[ \frac{b}{4\pi^2n^2}(1 - 1) \right] \\
= \frac{b}{2}
\end{gather}$$
Vậy giá trị kì vọng của vị trí là $\langle x \rangle = \frac{b}{2}$
Vì giá trị kì vọng không phụ thuộc theo thời gian nên 
$$\langle p \rangle = \frac{d\langle x\rangle}{dt}=0$$
### d)
Các mức năng lượng của hạt trong giếng thế trong điều kiện biên $x = b$ là 
$$E_{n} = \frac{n^2\pi^2\hbar^2}{2mb^2}$$
Vì có 3 mức trạng thái nên các mức năng lượng lần lượt là 
- $E_{1} = \frac{\pi^2\hbar^2}{2mb^2}$
- $E_{2} = \frac{4\pi^2\hbar^2}{2mb^2}$
- $E_{3} = \frac{9\pi^2\hbar^2}{2mb^2}$
Xác suất đo năng lượng là 
$$P(E_{n}) = |c_{n}|^2$$
Xác suất từng mức năng lượng là 
- $P(E_{1}) = \frac{1}{6}$
- $P(E_{2}) = \frac{1}{6}$
- $P(E_{3}) = \frac{2}{3}$
Năng lượng trung bình của hệ 
$$\begin{gather}
\langle E \rangle = \sum^3_{n=1} P(E_{n})\cdot E_{n}  \\
=\frac{1}{6} \frac{\pi^2\hbar^2}{2mb^2} + \frac{1}{6} \frac{2\pi^2\hbar^2}{mb^2} + \frac{2}{3} \frac{9\pi^2\hbar^2}{2mb^2} \\
= \frac{41\pi^2\hbar^2}{12mb^2}
\end{gather}$$
## Bài 2
### a)

Điều kiện chuẩn hoá hàm sóng là :
$$\begin{gather}
\int^\infty_{-\infty}|\Psi(x,0)|^2 \, dx = \int_{-\infty}^\infty\Psi(x, 0)^*\Psi(x, 0) \,dx \\
 = \int^\infty_{-\infty}A[i\psi_{0} + 3\psi_{1}]A[-i\psi_{0}^*+3\psi_{1}^*]\,dx  \\
=A^2\left[-i^2\int^\infty_{-\infty}\psi_{0}\psi_{0}^*\, dx +\int^\infty_{-\infty}3i\psi_{0}\psi_{1}^*\, dx \right. \\
\left.
-\int^\infty_{-\infty}3i\psi_{1}\psi_{0}^* \, dx
+9\int^\infty_{-\infty}\psi_{1}\psi_{1}^*\,dx\right]  \\
=A^2[1 + 0 - 0 + 9]  \\

= |A^2|(1 + 9) = 1 \\
|A|^2 = \frac{1}{10} = \frac{\sqrt{ 10 }}{10}
\end{gather}$$
$$\implies \Psi(x,t) = \frac{\sqrt{ 10 }}{10}[i\psi_{0}(x) + 3\psi_{1}(x)]$$
### b)
Vì $\psi_{0}(x), \psi_{1}(x)$ lần lượt là hàm chẵn và lẻ. Nên khi tính $\langle x \rangle$ trên toàn miền, sẽ đối xứng. 
$$\implies \langle x\rangle = \int \Psi^* x\Psi \, dx = 0$$
Từ đó cũng suy ra :
$$\langle p \rangle = \frac{d\langle x\rangle}{dt} = 0$$
Thế năng của hàm Schrodinger :
$$V(x) = \frac{1}{2}m\omega^2x^2 $$
Giá trị trung bình thế năng :
$$\langle V \rangle = \frac{1}{2}m\omega^2\langle x^2 \rangle$$
$$\begin{gather}
\langle x^2\rangle = \int^\infty_{-\infty}\psi^*\cdot(x^2)\psi \,dx \\
=\frac{1}{10}\int^\infty_{-\infty}\left( \frac{\hbar}{2m\omega}(a_{+}+a_{-})^2 \right)[i\psi_{0} + 3\psi_{1}][-i\psi_{0}^*+3\psi_{1}^*]\, dx \\
=\frac{\hbar}{20m\omega}\int^\infty_{-\infty}(a^2_{+}+2a_{+}a_{-}+a^2_{-})(-i\psi_{0}+3\psi_{1})(-i\psi_{0}^*+3\psi_{1}^*) \,dx \\ 
= \frac{\hbar}{20m\omega}(1 + 3\cdot 9) = \frac{7\hbar}{5m\omega}
 \\ 
\implies \langle V\rangle = \frac{1}{2}m\omega^2 \frac{7\hbar}{5m\omega}=\frac{7\hbar \omega}{10}
\end{gather}$$
### c)
Điểm quay đầu cổ điển của hạt khi :
$$V(x) = E_{n} \Leftrightarrow \frac{1}{2}m\omega^2x^2 = \left( n + \frac{1}{2} \right)\hbar \omega$$
$$\implies x^2 = \frac{2\left( n + \frac{1}{2} \right)\hbar \omega}{m\omega^2} = \frac{(2n + 1)\hbar}{m\omega} \Leftrightarrow x = \pm\sqrt{ \frac{(2n+1)\hbar}{m\omega} }$$
Vì đang xét $\psi_{1}$ nên:
$$x_{1} = \pm \sqrt{ \frac{(2 + 1)\hbar}{m\omega} }=\pm \sqrt{ \frac{3\hbar}{m\omega}}$$

