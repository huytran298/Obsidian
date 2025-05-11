## Hàm sóng Schrodinger (Phương trình Schrodinger)
### Hàm sóng của một hạt
$$i\hbar \frac{\partial\Psi}{\partial t} = -\frac{\hbar^2}{2m} \frac{\partial^2}{\partial x^2} + \mathbf{V}\Psi$$
### Xác suất
#### Giá trị kỳ vọng (trung bình)
$$\langle j \rangle = \frac{\sum jN(j)}{N} = \sum^\infty_{j = 0} jP(j)$$
#### Mật độ xác suất
$$P_{ab} = \int^a_{b} \rho(x) \,dx$$
Và các quy tắc suy luận cho các phân phối rời rạc được dịch theo cách rõ ràng:
$$\begin{gather}
1 = \int^{+\infty}_{-\infty}\rho(x)\, dx \\
\langle x\rangle  = \int^{+\infty}_{-\infty}x\rho(x)\, dx  \\
\langle f(x)\rangle  = \int^{+\infty}_{-\infty}f(x)\rho(x)\, dx  \\
\end{gather}$$


### Chuẩn hoá 
#### Khái niệm
Một hạt được định vị tại một điểm, nơi mà hàm sóng lan trong không gian (nó là hàm của $x$, cho mọi thời gian $t$). Để một vận được đại diện cho trạng thái của hạt thì phải dựa trên ***Giải thích thống kê*** của Born về hàm sóng. Born giải thích rằng $|\Psi(x,t)|^2$ cho *xác suất* của tìm hạt tại vị trí $x$, thời điểm $t$, hoặc có thể nói chính xác hơn là :
$$\int^b_{a}|\Psi(x,t)|^2 \, dx $$
Là xác suất tìm thấy hạt giữa $a$ và $b$, tại thời điểm $t$.

### Điều kiện chuẩn hoá 
Gọi $|\Psi(x,t)|^2$ là hàm mật độ xác suất để tìm kiểm hạt tại điểm $x$, tại thời gian $t$. Ta có : 
$$\int^\infty_{-\infty}|\Psi(x,t)|^2 \, dx = 1$$
### Động lượng
Cho hạt trong trạng thái $\Psi$, giá trị kỳ vọng của giá trị $x$ là : 
$$\langle x \rangle = \int^{+\infty}_{-\infty}x|\Psi(x,t)|^2 \, dx$$
Nếu thay đổi theo thời gian, $\langle x \rangle$ sẽ thay đổi (bởi vì sự độc lập của $\Psi$), và chúng ta có vẻ hứng thú với tốc độ thay đổi của chúng. Ta có :
$$\langle x \rangle = \int \Psi^*(x)\Psi \, dx$$
Từ đó có rằng : 
$$\langle p \rangle = m \frac{d\langle x\rangle}{dt} = \int\Psi^* \left( \frac{\hbar}{i} \frac{\partial}{\partial x} \right)\frac{\partial\Psi}{\partial x}\, dx$$
### Nguyên lý bất định
Tưởng tượng rằng bạng đang giữ đuôi của một sợi dây rất dài, và bạn đang tạo sóng bằng cách vung dây lên và xuống đều tay. Nếu có ai hỏi bạn *”Chính xác nó là sóng gì ?”* bạn có thể nghĩ anh ấy hơi điên rỗ một chút : *Sóng không chính xác là ở đâu* - nó lan hơn chục mét hoặc có thể hơn nữa. Mặc khác nếu anh ấy hỏi *bước sóng bao nhiêu ?*, bạn có thể cho anh ấy một câu trả lời hợp lý rằng : *Nó có khoảng 6m*. Ngược lại, nếu bạn đánh sợi dây một lần theo hướng từ trên xuống. Lúc này, câu hỏi đầu tiên *(Chính xác thì sóng ở đâu ?)* là một câu hỏi hợp lý, và câu hỏi thứ hai là *(Bước sóng của nó là gì ?)* nghe có vẻ hơi điên rồ một chút - nó không phải là câu hỏi mơ hồ, *vậy thì làm sao bạn có thể gán bước sóng cho nó ?*. Dĩ nhiên rằng, bạn có thể vẽ các trường hợp trung gian, trong đó sóng được định vị *khá tốt* và bước sóng được định vị *khá rõ*. 
Nhưng có một sự đánh đổi không thể tránh khỏi ở đây : *vị trí của một sóng được định vị càng chính xác, thì bước sóng của nó càng kém chính xác.* Một định lý trong *tích phân Fourier*, làm cho tất cả các điều này trở nên nghiêm ngặt, nhưng tôi chỉ quan tâm tới *đối số định tính.*
Điều này, dĩ nhiên với *mọi* dạng sóng, và do đó nó đặc biệt với hàm sóng trong cơ học lượng tử. Bây giờ bước sóng của $\Psi$ liên quan tới *động lượng* của hạt bởi công thức **de Broglie** :
$$p = \frac{h}{\lambda} = \frac{2\pi \hbar}{\lambda}$$
Dù vậy, sự lan truyền trong *bước sóng* phù hợp với sự lan truyền của *động lương*, và sự tính toán mục đích chung của chúng ta cho biết rằng ***càng xác định chính xác vị trí của hạt thì càng ít chính xác về động lượng***. Do đó : 
$$\sigma_{x}\sigma_{p} \geq \frac{\hbar}{2}$$
Trong đó, $\sigma_{x}$ là độ lệch chuẩn của $x$, và $\sigma_{p}$ là độ lệch chuẩn của $p$. Đây là *nguyên lý bất định* nổi tiếng của Heisenberg. 
Và có thể hiểu nguyên lý bất định rằng đây là sự sai lệch của vật chất chứ không phải đến từ dụng cụ đo hay phép đo bất kỳ, hay còn hiểu là nếu dụng cụ đo là giống nhau thì các kết quả cho ra vẫn khác nhau. Bạn có thể (nếu muốn) xây dựng một trạng thái sao cho các phép đo vị trí lặp lại sẽ rất gần nhau, nhưng bạn sẽ phải nhận lại rằng : *các phép đo về động lượng của trạng thái này sẽ bị phân tán rất rộng.* Hoặc bạn có thể chuẩn bị trạng thái phép đo động lượng lặp lại, thì lúc này *phép đo về vị trí của hạt sẽ bị phân tán rất rộng.* Và dĩ nhiên rằng bạn sẽ cảm thấy ***Buồn chán*** vì bạn có thể tạo ra một trạng thái mà cả vị trí và động lượng đều không được xác định rõ ràng. Biểu thức của Heisenberg rõ ràng là bất đẳng thức, không có giới hạn về $\sigma_{x}, \sigma_{p}$. 
## Trạng thái đứng yên
### Định nghĩa 
Ở phần trên ta đã biết hàm Schrodinger phụ thuộc theo thời gian, câu hỏi được đặt ra lúc này là làm sao để *xác định nó ngay từ bước đầu tiên ?* Chúng ta cần giải phương trình Schordinger 
$$i\hbar \frac{\partial\Psi}{\partial t} = -\frac{\hbar^2}{2m}\frac{\partial^2\Psi}{\partial x^2} + \mathbf{V}\Psi$$
Giả sử đặt $\mathbf{V}$ *độc lập với thời gian $t$*. Trong trường hợp này phương trình Schrodinger có thể giải bằng phương pháp **Tách biến**. Lúc này ta tách hàm sóng thành :
$$\Psi(x,t) = \psi(x)\varphi(t)$$
Lúc này, 
$$\frac{\partial \Psi}{\partial t} = \psi  \frac{d\varphi}{dt} , \ \frac{\partial^2\Psi}{\partial x^2} = \frac{d^2\psi}{dx^2} \varphi$$
và phương trình Schrodinger là :
$$\begin{gather}
i\hbar \psi  \frac{d\varphi}{dt} = -\frac{\hbar}{2m} \frac{d^2\psi}{dx^2} \varphi + \mathbf{V}\psi \varphi \\
i\hbar \frac{1}{\varphi} \frac{d\varphi}{dt} = -\frac{\hbar}{2m} \frac{1}{\psi} \frac{d^2\psi}{dx^2} + \mathbf{V} 
\end{gather}$$
$$i\hbar \frac{1}{\varphi} \frac{d\varphi}{dt} = E$$
Từ đó :

$$\begin{gather}
  -\frac{\hbar^2}{2m} \frac{1}{\psi} \frac{d^2\psi}{dx^2} + \mathbf{V} = E 
\\
-\frac{\hbar^2}{2m} \frac{d^2\psi}{dx^2} + \mathbf{V\psi} = \mathbf{E} \psi
\end{gather}$$

#### Trạng thái đứng yên 
Mặc dù hàm sóng 
$$\Psi(x,t) = \psi(x)e^{-iEt/h}$$
Phụ thuộc vào thời gian, mật độ xác suất của hàm sóng
$$|\Psi(x,t)|^2 = \Psi^*\Psi = \psi^*e^{+iEt/\hbar} \psi e^{-iEt/\hbar} = |\psi(x)|^2$$
Lại không phụ thuộc vào thời gian. Điều này cũng diễn ra trong các tính toán của các giá trị kỳ vọng của các biến động 
$$\langle Q(x,p)\rangle = \int \psi^* Q\left(  x, \frac{h}{i}  \frac{d}{dx} \right) \psi \, dx$$
Mọi giá trị kỳ vọng đều là hằng số trong *thời gian*. Chúng ta lúc này có thể bỏ phần $\varphi(t)$ và sử dụng $\psi$ thay vì $\Psi$. Lúc này, $\langle x \rangle$ là hằng số, do đó $\langle p \rangle = 0$. Không có gì diễn ra trong *trạng thái đứng yên*.
#### Hamiltonian và năng lượng $\mathbf{E}$
Trong cơ học cổ điển, tổng các năng lượng (động năng và thế năng) được gọi là **Hamitonian** :
$$H(x, p) = \frac{p^2}{2m} + \mathbf{V}(x)$$
##### Toán tử Hamitonian
$$\hat{H} = \frac{\hbar^2}{2m} \frac{\partial^2}{\partial x^2} + \mathbf{V}(x)$$
Do đó, hàm Schrodinger độc lập thời gian  có thể viết là 
$$\hat{H}\psi = E\psi$$
và giá trị của vọng của tổng năng lượng là 
$$\langle H \rangle = \int \psi^* \hat{H}\psi\, dx = E \int|\psi|^2\,dx = E \int|\Psi|^2 \,dx = E$$
### Tổ hợp tuyến tính
Miền có vô hạn các hàm sóng $(\psi_{1}(x), \psi_{2}(x), \psi_{3}(x), \dots)$, với mỗi giá trị liên quan tới hằng số $(E_{1}, E_{2}, E_{3}, \dots)$ do đó mỗi hàm sóng với mỗi **năng lượng cho phép** là 
$$\Psi_{1}(x,t) = \psi_{1}(x)e^{-iE_{1}t/\hbar}, \ \Psi_{2}(x,t) = \psi_{2}(x)e^{-iE_{2}t/\hbar}, \ \dots$$
Vậy lúc này hàm Schrodinger độc lập theo thời gian có tính chất rằng với bất kỳ tổ hợp tuyến tính của hàm là hàm đó. Mỗi khi tìm thấy mỗi trạng thái riêng biệt chúng ta có thể thiếp lập nhiều hàm với nhau với dạng 
$$\Psi(x,t ) = \sum^\infty_{n = 1} c_{n}\psi_{n}(x)e^{-iE_{n}t/\hbar}$$
Nó cũng diễn ra với mỗi trạng thái độc lập với thời gian, phương trình Schrodinger có thể viết dưới dạng này - nó đơn thuần chỉ là đi tìm hằng số sao cho phù hợp với điều kiện của bài toán.
$$\Psi(x, 0) = \sum^\infty_{n = 1}c_{n}\psi_{n}(x)$$
## Giếng thế vô hạn 1 chiều 
### Định nghĩa
Giả sử 
$$\mathbf{V}(x) = \begin{cases}
0 & \mathbf{if } \ 0 \leq x \leq a \\
\infty & \mathbf{otherwise} \ 
\end{cases}$$
Một hạt trong vùng thế năng này hoàn toàn tự do, ngoài trừ 2 điểm kết thúc ($x = 0$ và $x = a$). Nơi một lực vô hạn ngăn cản nó trốn thoát. 
Bên ngoài giếng, $\psi(x) = 0$ (xác suất tìm hạt ở đây bằng không), bên trong giếng nơi mà $\mathbf{V}(x) = 0$, hàm Schrodinger độc lập theo thời gian là 
$$-\frac{\hbar^2}{2m} \frac{d^2\psi}{dx^2} = E\psi$$
hoặc 
$$- \frac{\hbar^2}{2m} \frac{d^2\psi}{dx^2} = -k^2\psi$$
khi đó $$k = \frac{\sqrt{ 2mE }}{\hbar}$$
Lúc này hàm là phương trình giao động tử điều hoà cổ điển
$$\psi(x) = A\sin(kx) + B\cos(kx)$$
$A, B$ là hằng số của điều kiện biên của bài toán. Tiếp tục với bài toán 
$$\psi(0) = \psi(a) = 0$$
Lúc này ta có 
$$\begin{gather}
\psi(0) = A\sin(k\cdot 0) + B \cos(k \cdot 0) = 0 \\
\psi(0) = B = 0 \\
\psi(a) = A\sin(k \cdot a) = 0
\end{gather}$$
Khi này nếu $A = 0$ là nghiệm tầm thường, còn nếu $sin(k\cdot a) = 0$ điều này có nghĩa 
$$k \cdot a = 0, \ \pm \pi, \ \pm 2\pi , \dots$$
Nhưng nếu $k = 0$ điều này cho thấy $\psi(x) = 0$ Vậy do đó 
$$\begin{gather}
k_{n} = \frac{n\pi}{a}  & n = 1,2,3,\dots
\end{gather}$$
Kỳ lạ, điều kiện biên tại $x = a$ không xác định hằng số $A$, mà đúng hơn là hằng số $k$, và do đó giá trị có thể của $E$ là 
$$\begin{gather}
k = \frac{\sqrt{ 2mE }}{\hbar}  \\
\implies k_{n} = \frac{\sqrt{ 2mE_{n} }}{\hbar} \Leftrightarrow E_{n} = \frac{\hbar^2 k_{n}^2}{2m} = \frac{n^2 \pi^2 \hbar^2}{ma}
\end{gather}$$
Trái ngược hoàn toàn với trường hợp cổ điển, một hạt lượng tử trong giếng bình phương vô hạn không thể chỉ có bất kỳ năng lượng cũ nào - nó phải có một trong những giá trị đặc biệt **cho phép**. Để tìm $A$ ta chuẩn hoá $\psi$
$$\int^a_{0} |A|^2\sin^2(kx)\, dx = |A|^2 \cdot\frac{a}{2} = 1$$
Vì vậy
$$\begin{gather}
|A|^2 = \frac{2}{a} \implies A = \sqrt{ \frac{2}{a} }
\end{gather}$$
Do đó bên trong giếng, hàm sóng lúc này 
$$\psi_{n} = \sqrt{ \frac{2}{a} }\sin\left( \frac{n\pi}{a}x \right)$$
Trong đó, $\psi_{1}$ là mang năng lượng nhỏ nhất, gọi là ***trạng thái cơ bản***, mặt khác năng lượng tăng theo bình phương $n$ ($n^2$) gọi là ***trạng thái kích thích***.
Hàm $\psi_{n}(x)$ có một vài bản chất quan trọng và thú vị. 
- Hàm xen kẽ **chẵn** và **lẻ**, để cân bằng tại trung tâm của giếng, $\psi_{1}$ là chẵn, $\psi_{2}$ là lẻ, $\psi_{3}$ là chẵn, và cứ thế tiếp tục.
- Khi bạn tăng năng lượng, mỗi trạng thái liên tiếp có thêm một nút nữa (không giao nhau): $\psi_0$ không có (điểm cuối không được tính), $\psi_{2}$ có một, $\psi_{3}$ có hai, và cứ thế tiếp diễn.
- Nó có tính **trực giao** qua lại, có nghĩa là $$\int \psi_{m}^*\psi_{n} \, dx = \begin{cases}
0  & m\neq n \\
\delta_{mn}  & m = n
\end{cases}$$
	Trong đó $\delta_{mn}$ (còn được gọi là **Kronecker delta**) được định nghĩa là 
	$$\delta_{mn} = \begin{cases}
	0  &  m \neq n \\
	1  &  m = n
	\end{cases}$$
	chúng ta gọi đây là tính **trực giao** của hàm sóng $\psi$.
- Chúng có dạng **hoàn chỉnh**, có nghĩa với hàm *khác*, $f(x)$ có thể được viết dưới dạng $$f(x) = \sum^\infty_{n = 1} c_{n}\psi_{n}(x) = \sqrt{ \frac{2}{a} }\sum^\infty_{n = 1} c_{n}\cdot\sin\left( \frac{n\pi}{a} x \right)$$
### Trạng thái đứng yên của giếng thế vô hạn
$$\Psi(x,t) = \sqrt{ \frac{2}{a} }\sin\left( \frac{n\pi}{a}x \right)e^{-i (n^2 \pi^2 \hbar \cdot t)/ 2ma}$$
$$\Psi_{n}(x, t) = \sum^\infty_{n = 1}c_{n} \cdot\sqrt{ \frac{2}{a} }\sin\left( \frac{n\pi}{a}x \right)e^{-i (n^2 \pi^2 \hbar \cdot t)/ 2ma}$$
### Chuẩn hoá
Nói một cách khác, $c_{n}$ cho bạn biết *”một lượng của $\psi_n$ chứa trong $\Psi$”* . Do đó $|c_{n}|^2$ cho bạn biết *”xác suất một phép đo năng lượng trong miền giá trị $E_n$”* “cho phép” năng lượng, do đó tổng của chúng là 
$$\sum^\infty_{n = 1}|c_{n}|^2 = 1$$
Hơn thế nữa, giá trị kỳ vọng của năng lượng phải là 
$$\langle H \rangle = \sum^\infty_{n = 1} |c_{n}|^2E_{n}$$
