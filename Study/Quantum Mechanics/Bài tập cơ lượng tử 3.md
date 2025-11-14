<center><h2>Họ và tên : Trần Quốc Huy</h2>

<h3>MSSV : 23230005</h3>
<h4>Bài tập về nhà - Cơ lượng tử</h4>
</center>

## Bài tập 1
### a)
$$\begin{gather}
\int |\Psi(\mathbf{r}, 0)|^2 \, d^3r = 1 \\
\Longleftrightarrow  \int |A\psi_{2,1,-1}(\mathbf{r}) + \frac{3}{\sqrt{ 12 }}\psi_{3,2,0}(\mathbf{r})|^2 \, d^3 r = 1 \\
\Longleftrightarrow |A|^2 + \left|\frac{3}{\sqrt{ 12}}\right|^2 = 1 \\
A = \pm \frac{1}{2}
\end{gather}$$

### b)
Các giá trị năng lượng : 
Với $n = 2$ : 
$$E_{2} = -\frac{13.6}{2^2} = -3.40 \, eV$$
$n = 3$ : 
$$E_{3} = -\frac{13.6}{3^2} = -1.51 \, eV$$
Xác suất thu năng lượng :
Với $n = 2$ : 
$$P(E_{2}) = |A|^2 = \frac{1}{4}$$
Với $n = 3$:
$$P(E_{3}) = \left|\frac{3}{\sqrt{12}}\right|^2 = \frac{3}{4}$$
Giá trị trung bình năng lượng thu được : 
$$\langle E \rangle = |c_{1}|^2E_{2} + |c_{2}|^2 E_{3} = \frac{1}{4} \cdot (-3.40) + \frac{3}{4} \cdot (-1.51) = -1.98 \, eV$$
### c)
Dựa trên hàm sóng đã cho ta thấy chỉ tồn tại lần lượt 2 số lượng tử quỹ đạo là $l = 1, l = 2$ 
Vậy xác suất thu được ở số lượng tử quỹ đạo $l = 0$ là :
$$P(l = 0) = 0$$
Xác suất thu được ở số lượng tử quỹ đạo $l = 1$ là : 
$$\begin{gather}
P(l = 1) = |c_{2,1,-1}|^2 = \frac{1}{4}
\end{gather}$$
### d)
Hàm sóng tại thời điểm $t$ bất kì là : 
$$\Psi(\mathbf{r}, t) = \frac{1}{2}\varphi_{2,1,-1}(\vec{r}) \cdot e^{iE_{2}t/\hbar} + \frac{3}{\sqrt{ 12 }}\varphi_{3,2,0}(\vec{r}) \cdot e^{iE_{3}t /\hbar }$$
### e)

| Thành phần trạng thái                                              | Giá trị $L^2$                    | Giá trị $L_z$         |
| ------------------------------------------------------------------ | -------------------------------- | --------------------- |
| $\frac{1}{2}\varphi_{2,1,-1}(\mathbf{r})e^{iE_{2}t/\hbar}$         | $L^2 = 1(1 + 1)\hbar = 2\hbar^2$ | $L_{z} = -1\hbar$     |
| $\frac{\sqrt{ 3 }}{2}\varphi_{3,2,0}(\mathbf{r})e^{iE_{3}t/\hbar}$ | $L^2 = 2(2 + 1)\hbar = 6\hbar^2$ | $L_{z} = 0\hbar  = 0$ |
Giá trị trung bình của $L^2$ : 
$$\langle L^2 \rangle = \frac{1}{4}(2\hbar^2) + \frac{3}{4}(6\hbar^2) = 5\hbar^2$$
Giá trị trung bình của $L_{z}$:
$$\langle L _{z}\rangle = \frac{1}{4}(-1\hbar) + \frac{3}{4}(0) = -\frac{\hbar}{4}$$
### f)
Giá trị kỳ vọng động năng là 
$$\begin{gather}
\langle T \rangle = \int \Psi^* \hat{T}\Psi \, d^3r = \frac{1}{4}\langle T\rangle_{2} + \frac{9}{12}\langle T\rangle_{3} = \frac{1}{4}(-E_{2}) + \frac{9}{12}(-E_{3})
\end{gather}$$
Giá trị kỳ vọng thế năng là 
$$\langle V \rangle = \int \Psi^* \, \hat{V} \,\Psi \, d^3r = \frac{1}{4}\langle V\rangle_{2} + \frac{3}{4} \langle V\rangle_{3} = \frac{1}{2}E_{2} + \frac{3}{2}E_{3}$$
## Bài 2
Hàm sóng Schrodinger ở trạng thái cơ bản là :
$$\psi_{100}(r, \theta, \varphi) = \frac{1}{\sqrt{ \pi a^3_{0} }}e^{-r/a_{0}}e^{iE_{1}t/\hbar}$$
### a)
$$\begin{gather}
\langle r \rangle = \int \Psi_{100}^* r \Psi_{100} \, d^3 r  \\
= \int_{0}^\pi \int_{0}^{2\pi} \int_{0}^\infty \left(\frac{1}{\sqrt{ \pi a^3_{0} }}e^{-r/a_{0}}e^{iE_{1}t/\hbar}\right)^*r\left(\frac{1}{\sqrt{ \pi a^3_{0} }}e^{-r/a_{0}}e^{iE_{1}t/\hbar}\right) \, (r^2 \, \sin \theta\, dr\, d \phi\, d\theta) \\
= \left.\frac{1}{\pi a_{0}^3}(2)(2\pi)\int_{0}^\infty \frac{\partial^3}{\partial u ^3}(-e^{-ur})\right|_{u = 2/a_{0}}dr  \\
= -\frac{4}{a_{0}^3}\left( -\frac{6a_{0}^4}{16} \right) = \frac{3}{2}a_{0}
\end{gather}$$
$$\begin{gather}
\langle r^2 \rangle = \int \Psi_{100}^* r ^2\Psi_{100} \, d^3 r  \\
= \int_{0}^\pi \int_{0}^{2\pi} \int_{0}^\infty \left(\frac{1}{\sqrt{ \pi a^3_{0} }}e^{-r/a_{0}}e^{iE_{1}t/\hbar}\right)^*r^2\left(\frac{1}{\sqrt{ \pi a^3_{0} }}e^{-r/a_{0}}e^{iE_{1}t/\hbar}\right) \, (r^2 \, \sin \theta\, dr\, d \phi\, d\theta) \\
= \left.\frac{1}{\pi a_{0}^3}(2)(2\pi)\int_{0}^\infty \frac{\partial^4}{\partial u ^4}(-e^{-ur})\right|_{u = 2/a_{0}}dr  \\
= \frac{4}{a_{0}^3}\left( \frac{24a_{0}^5}{32} \right) = 3a_{0}^2
\end{gather}$$
### b)
Xác suất tìm thấy electron trong hạt nhân biết bán kính proton là $b$
$$P(r \leq b) = \int_{0}^b |\psi_{100}(r)|^2 4\pi r^2\, dr = \frac{4}{a^3_{0}}\int^b_{0} r^2 e^{2r/a_{0}} \, dr$$
$$\implies P(r\leq b) = 1 - \left( 1 + 2 \frac{b}{a_{0}} + 2\left( \frac{b}{a_{0}} \right)^2 \right)e^{-2b / a_{0}}$$
### c)
Khi $b = 10^{-15}m$ và $a_{0} = 0.5\times 10^{-15} m$ xác suất là :
$$P(r \leq 10^{-15}) = 1 - \left( 1 + 2 \frac{10^{-15}}{0.5 \times 10^{-15}} + 2\left(\frac{10^{-15}}{0.5 \times 10^{-15}}\right)^2 \right)e^{-2 \cdot 10^{-15}/(0.5 \cdot 10^{-15})} = 0.7618 $$
## Bài 3
Với trạng thái kích thích thứ 3 thì $n = 4$ :

Với $l = 0$
$$\varphi_{400}$$
Với $l = 1$
$$\varphi_{410}, \varphi_{41-1}, \varphi_{411}$$
Với $l =2$
$$\varphi_{420}, \varphi_{42-1},\varphi_{421},\varphi_{42-2}, \varphi_{422}$$
Với $l = 3$
$$\varphi_{430}, \varphi_{43-1}, \varphi_{431},\varphi_{43-2}, \varphi_{432},\varphi_{43-3}, \varphi_{433}$$
Với $l = 4$
$$\varphi_{440}, \varphi_{44-1}, \varphi_{441}, \varphi_{44-2}, \varphi_{442}, \varphi_{44-3}, \varphi_{443}, \varphi_{44-4},\varphi_{444}$$