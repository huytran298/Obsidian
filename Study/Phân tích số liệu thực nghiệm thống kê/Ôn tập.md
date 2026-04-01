## Trung bình 
Giả sử 1 bộ dữ liệu có $N$ giá trị lần lượt : 
$$x_{1},x_{2},x_{3}, \dots,x_{n}$$
Khi đó :
Trung bình hay trung bình thực nghiệm (experiment mean) là :
$$\overline{x_{e}} = \frac{\sum^N_{i=1} x_{i}}{N}$$
## Phương sai mẫu
Để xác định phương sai mẫu trước hết phải xác định phần dư (residual) của dữ liệu, khi đó phần dư của giá trị $x_i$  tại $i$ là : 
$$d_{i} = x_{i} - \overline{x_{e}}$$
Khi đó : 
$$\sum^N_{i = 1} d_{i} = 0$$
Nếu xác định, kỳ vọng (true mean) là $\overline{x}$ của dữ liệu ta có, độ lệch là :
$$\epsilon_{i} = x_{i} -\overline{x}$$
Từ đó ta có phương sai mẫu :
$$s^2 = \overline{\epsilon^2} = \frac{1}{N}\sum^N_{i = 1}(x_{i} - \overline{x})^2$$
Nhưng trong thực tế, xác định kỳ vọng của 1 tập dữ liệu là vô cùng khó vì khi đó phải có vô hạn dữ liệu, từ đó ta có thể thay thế kỳ vọng thành trung bình, công thức phương sai mẫu lúc này thành :
$$s^2 = \frac{1}{N}\sum^N_{i = 1}(x_{i} - \overline{x_{e}})^2$$
Đối với dữ liệu lớn $(N\ge30)$ ta có phương sai mẫu :
$$s^2 = \frac{1}{N-1}\sum^N_{i = 1}(x_{i} - \overline{x})^2$$
## Mô hình thống kê (Statistical Models)
### Phân phối nhị thức (Binomial Distribution)
Nếu có $N$ lần thử với mỗi lần thử có xác suất đúng là $p$, thì xác suất đúng với $x$ lần là : 
$$P(x) = C^x_{n} p^x(1-p)^{n-x}$$
#### Chuẩn hoá 
Phân phối được chuẩn hoá như sau : 
$$\sum^N_{i=0}P(x) = 1$$
#### Trung bình, kỳ vọng
Trung bình/kỳ vọng của phân phối được định nghĩa như sau : 
$$\overline{x} = \sum^N_{x}xP(x) = pN$$
#### Độ lệch chuẩn 
Độ lệch chuẩn được định nghĩa là thang đo sự tán xạ của trung bình dự đoán : 
$$\sigma^2 = \sum^N_{x}(x - \overline{x})^2P(x) = np(1-p) = \overline{x}(1-p)$$
### Phân phối Poisson
Khác với phân phối nhị thức là tính xác suất với số lần thử là cố định, thì phân phối nhị thức chỉ biết trung bình ($\lambda$) số lần, đồng thời với xác suất từng lần thành công là cực kì nhỏ và là hằng số, ta định nghĩa xác suất là : $$P(x) = \frac{\lambda^x e^{-\lambda}}{x!}$$
#### Trung bình và độ lệch chuẩn 
giống với phân phối nhị thức, tuy nhiên vì xác suất thành công là cực nhỏ nên $(1-p)$ tiến tới $1$, ta có độ lệch chuẩn :
$$\sigma^2=\overline{x}=np$$
### Phân phối chuẩn
Khi phân phối poisson có trung bình là rất lớn (hơn 25 hoặc 30) thì phân phối poisson trở thành phân phối gaussian.
$$P(x) = \frac{1}{\sqrt{ 2\pi\overline{x} }}\exp\left( - \frac{(x-\overline{x})^2}{2\overline{x}} \right)$$
#### Trung bình, độ lệch chuẩn
Cũng giống như poisson, trung bình là  :
$$\overline{x} = np$$Với độ lệch chuẩn thì : 
$$\sigma=\sqrt{ \overline{x} }$$
## Truyền sai số 
Nếu $x,y,z, \dots$ lần lượt là số đếm hoặc là đại lượng được xác định với biết được $\sigma_{x},\sigma_{y},\sigma_{z},\dots$  khi đó biết được độ lệch chuẩn của đại lượng $u$ từ các đại lượng được nêu trên ta có : 
$$\sigma^2_{u} = \left( \frac{\partial u}{\partial x} \right)^2 \sigma_{x}^2 + \left( \frac{\partial u}{\partial y} \right) \sigma^2_{y} + \left( \frac{\partial u}{\partial z} \right)^2 \sigma_{z
}^2  + \dots \tag{1} \label{ErrProg}$$

Trong đó, $u=u(x,y,z, \dots)$, từ đó phương trình nêu trên gọi là *công thức truyền sai số*. Từ đó có các trường hợp như sau : 
#### Trường hợp 1 : tổng của các số đếm.
nếu ta có : 
$$u = x + y \text{ or } u = x-y$$
khi đó : 
$$\frac{\partial u}{\partial x} = 1 \text{ or } \frac{\partial u}{\partial y} = \pm1$$
Áp dụng công thức $\eqref{ErrProg}$, ta có : 
$$\sigma^2_{u} = 1\cdot\sigma^2_{x} + 1\cdot\sigma^2_{y}$$
$$\sigma_{u} = \sqrt{ (\sigma_{x})^2 +(\sigma_{y})^2}$$
#### Trường hợp 2 : Nhân hoặc chia với 1 hằng số .
Nếu ta có : $$u = Ax$$
khi đó : 
$$\frac{\partial u}{\partial x} = A$$
Áp dụng công thức $\eqref{ErrProg}$, ta có : 
$$\sigma^2_{u} = A^2\sigma^2_{x}$$
$$\sigma_{u} = A\sigma_{x}$$
Đối với phép chia ta có : 
$$u = x / B$$
khi đó : $$\frac{\partial u}{\partial x} = \frac{1}{B}$$Áp dụng công thức $\eqref{ErrProg}$, ta có : 
$$\begin{gather}
\sigma^2_{u} = \frac{\sigma^2_{x}}{B^2} \\
\sigma_{u} = \frac{\sigma^2_{x}}{B}
\end{gather}$$



