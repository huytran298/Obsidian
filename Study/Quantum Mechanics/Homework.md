<center><h2>Họ và tên : Trần Quốc Huy</h2>

<h3>MSSV : 23230005</h3>
<h4>Bài tập về nhà - Cơ lượng tử</h4>
</center>




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
$$\Psi^*\Psi = |\Psi|^2$$
### c)
Điều kiện chuẩn hóa của hàm sóng :
$$\int _{-\infty}^{\infty} |\Psi(x,t)|^2 \, dx = 1$$
Theo ý nghĩa vật lý, không có điều kiện chuẩn hóa thì giải thích về mặt xác suất thống kê hay là modulus bình phương hàm sóng (theo cách diễn giải của Born) sẽ trở nên vô nghĩa.
### d)
Giá trị trung bình (giá trị kì vọng) là :
$$\frac{d\langle x\rangle}{dt} = -\frac{i\hbar}{m}\int\Psi^* \frac{\partial \Psi}{\partial x} \, dx$$
Giá trị trung bình của động lượng là :
$$\langle p \rangle = m \frac{d\langle x\rangle}{dt} = -ih\int\Psi^* \frac{\partial \Psi}{\partial x} \, dx$$
Giá trị trung bình của động năng là :
$$\langle T \rangle = - \frac{\hbar^2}{2m}\int\Psi^* \frac{\partial^2\Psi}{\partial x^2} \,dx$$
## Câu 2
### a)
Phương trình Schrodinger không phụ thuộc thời gian cho hàm sóng $\Psi_{n}(x)$ là :
$$-\frac{\hbar^2}{2m} \frac{d^2\psi_{n}(x)}{dx^2} + V_{n}(x)\psi_{n}(x) = E_{n}\psi_{n}(x)$$
Mối quan hệ giữa $\Psi(x,t )$ và $\psi(x)$
$$\Psi(x,t) = \sum^\infty_{n = 1}c_{n}\psi_{n}(x)e^{-iE_{n}t/\hbar}$$
### b)
Ý nghĩa toán tử Hamilton là tổng năng lượng (bao gồm động năng và thế năng) của hệ.
Ý nghĩa đại lượng E là giá trị trung bình (giá trị kỳ vọng) của Hamilton.
### c)
Giả sử E có thành phần số phức 
$$E = E_o + i \Gamma$$
Lúc này hàm sóng Schrodinger theo thời gian là :
$$\Psi(x,t) = \psi(x)e^{-iEt/\hbar}  =\psi(x)e^{-i(E_o + i\Gamma)t/\hbar} = \psi(x)e^{-iE_{o}t/\hbar}e^{\Gamma t/\hbar}  $$
Điều kiện chuẩn hóa của hàm sóng :
$$1= \int^\infty_{-\infty}|\Psi(x,t)|^2 \, dx = \int^\infty_{-\infty}\Psi(x,t)^*\Psi(x,t) \, dx$$
$$\Leftrightarrow\int^\infty_{-\infty} (\psi(x)^*e^{iE_{o}t/\hbar}e^{\Gamma t/\hbar})(\psi(x)e^{-iE_{o}t/\hbar}e^{\Gamma t/\hbar})\, dx = 1$$
$$\Leftrightarrow\int^\infty_{-\infty} \psi(x)^*e^{2\Gamma t/\hbar}\, dx = 1$$
$$\Leftrightarrow e^{2\Gamma t/\hbar}\int^\infty_{-\infty} |\psi(x)|^2\, dx = 1$$
Vì $\int^\infty_{-\infty} |\psi(x)|^2\, dx = 1$ nên :
$$e^{2\Gamma t/\hbar} = 1 \implies \frac{2\Gamma t}{\hbar} = 0 \tag 1$$
Vì để đảm bảo cho điều kiện chuẩn hóa luôn đúng thì $e^{2\Gamma t/\hbar}$ không phụ thuộc vào thời gian. Vậy nên để thỏa mãn cho $(1)$ đúng thì $\Gamma = 0$ 
Vậy nên $E = E_o + i\Gamma = E_o$. Vậy $E$ luôn là số thực.
### d)
Ta có :
$$\langle Q(x, p)\rangle = \int \Psi^* Q\left( x, \frac{\hbar}{i} \frac{\partial}{\partial x} \right) \Psi \, dx \tag 2$$

Mật độ xác suất hàm sóng Schrodinger:
$$|\Psi(x,t)|^2 = \Psi(x, t)^*\Psi(x,t) = \psi(x)^*e^{iEt/\hbar} \psi(x) e^{-iEt/\hbar} = |\psi(x)|^2 $$
Vì mật độ xác suất hàm sóng không phụ thuộc thời gian nên lúc này $(2)$ sẽ trở thành :
$$\langle Q(x,p)\rangle = \int \psi(x)^*Q\left( x, \frac{\hbar}{i} \frac{d}{dx} \right)\psi(x)\, dx$$
Lúc này các giá trị trung bình (kì vọng) của đại lượng của toán tử $\hat{Q}(\hat{x}, \hat{p})$ không phụ thuộc thời gian.
## Câu 3
### a)
Bình phương modulus của các hệ số lần lượt là :
- $|2i|^2 = 4$
- $|1| = 1$
- $|-\sqrt{3 }|^2 = 3$
- $|-i|^2 = 1$
Điều kiện chuẩn hóa là :
$$|A|^2 \cdot 9 = 1 \implies A = \frac{1}{3}$$
### b)
hàm Schrodinger sau khi chuẩn hóa :
$$\Psi(x, 0) = \frac{1}{3}[2i\phi_{1} + \phi_{2} - \sqrt{ 3 }\phi_{3} - i\phi_{4}] = i\frac{2}{3}\phi_{1} + \frac{1}{3}\phi_{2} - \frac{\sqrt{ 3 }}{3}\phi_{3} - i\frac{1}{3}\phi_{4}$$
Năng lượng của hệ :
$$E_n = \frac{\epsilon}{n^2}$$
Năng lượng có thể có :
- $E_{1} = \epsilon$
- $E_{2} = \frac{1}{4}\epsilon$
- $E_{3} = \frac{1}{9}\epsilon$
- $E_{4} = \frac{1}{16}\epsilon$
Xác suất đo năng lượng :
- Đối với $P(E_{1})$
$$P(E_{1}) = |i \frac{2}{3}|^2 = \frac{4}{9}$$
- Đối với $P(E_{2})$
$$P(E_{2}) = |\frac{1}{3}|^2 = \frac{1}{9}$$
- Đối với $P(E_{3})$
$$P(E_{3}) = |-\frac{\sqrt{ 3 }}{3}|^2 = \frac{3}{9}$$
- Đối với $P(E_{4})$
$$P(E_{4}) = |-i\frac{1}{3}|^2 = \frac{1}{9}$$
### c)
Giá trị trung bình của năng lượng là 
$$\langle E\rangle = \sum^4_{j = 1}E_{j}P(E_{j}) $$
$$= \epsilon \cdot \frac{4}{9} + \frac{\epsilon}{4} \cdot \frac{1}{9} + \frac{\epsilon}{9} \cdot \frac{3}{9} + \frac{\epsilon}{16} \cdot \frac{1}{9} = \epsilon\left( \frac{4}{9} + \frac{1}{9}\cdot \frac{1}{4} + \frac{1}{9} \cdot \frac{1}{3} + \frac{1}{16}\cdot \frac{1}{9} \right)$$
$$\langle E\rangle = \frac{223}{432}\epsilon$$
### d)
Ta có hàm sóng Schrodinger phụ thuộc theo thời gian :
$$\Psi(x, t) = \sum_{n = 1}^\infty c_{n}\phi_{n}(x)e^{-iE_nt/\hbar}$$
Từ các mức năng lượng đã tìm ở phần trên ta có :
- $n = 1 \implies c_{1} = i \frac{2}{3}, E_{1} = \epsilon$
- $n = 2 \implies c_{2} = \frac{1}{3}, E_{2} = \frac{\epsilon}{4}$
-  $n = 3 \implies c_{3} = -\frac{\sqrt{ 3 }}{3} \implies E_{3}=\frac{\epsilon}{9}$
- $n = 4 \implies c_{4} = -i \frac{1}{3}, E_{4} = \frac{\epsilon}{16}$
Từ đó có hàm sóng Schrodinger tổng quát là :
$$\Psi(x,t) = i \frac{2}{3}\phi_{1}(x)e^{-i\epsilon t/\hbar} + \frac{1}{3}\phi_{2}(x)e^{-i\epsilon t/4\hbar} -\frac{\sqrt{ 3 }}{3}\phi_{3}(x)e^{-i\epsilon t/9\hbar} -i \frac{1}{3}\phi_{4}(x)e^{-i\epsilon t/16\hbar}$$
