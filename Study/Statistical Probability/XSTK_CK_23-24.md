## Câu 1
### a)

$$\widehat{p}_A = \frac{10}{200} = \frac{1}{20} = 0.05$$
$$\gamma = 1 - \alpha = 95\% \implies \alpha = 5\% \implies z_{1 - \frac{\alpha}{2}} =z_{0.975} =1.959$$
$$\epsilon = \sqrt{ \frac{\hat{p}(1 - \hat{p})}{n} } = \sqrt{ \frac{0.05 \cdot 0.95}{200}} = 0.0154$$
Khoảng tin cậy :
$$(p - \epsilon, p + \epsilon) = (0.05 - 0.154, 0.05 + 0.154) = (0.0345, 0.0654)$$
### b)
$$\overline{x_{A}} = \frac{\sum x_{i}}{n} = \frac{245.9}{10} = 24.59$$
$$s_{A}^2 = \frac{\sum (x_{i} - \overline{x})^2}{n - 1} = 0.8365 \implies s_{A} = 0.9146$$
$$\gamma = 1 - \alpha = 95\% \implies \alpha = 5\% \implies z_{1 - \frac{\alpha}{2}} =z_{0.975} =1.959$$
$$\epsilon = z_{1 - \frac{\alpha}{2}}\cdot \frac{s_{A}}{\sqrt{ n }} = 1.959 \cdot \frac{0.9146}{\sqrt{ 10 }} = 0.5665$$
$$(\overline{x} - \epsilon,\overline{x} + \epsilon) = (24.59 - 0.5665, 24.59 + 0.5665) = (24.023, 25.156)$$
Để sai số ước lượng bé hơn $0.2$ thì :
$$\epsilon < 0.2 \Leftrightarrow 1.959\cdot $$

### c)
$$A \sim N(\mu_{A}, \sigma^2_{A})$$
$$B \sim N(\mu_{B}, \sigma^2_{B})$$
$$\overline{x_{B}} = 25.0(cm), s_{B} = 0.85$$
$$\sigma_{A} = \sigma_{B} = 0.9$$
Bài toán kiểm định :
$$\begin{cases}
H_{0} : \mu_{A} = \mu_{B} \\
H_{a} : \mu_{A} \neq \mu_{B}
\end{cases}$$
Thống kê kiểm định :
$$S = \frac{(n - 1)S_{A}^2 + (m - 1)S_{B}^2}{n + m - 2} = \frac{9 \cdot 0.836 + 189 \cdot 0.722}{190 + 10 - 2} = 0.727$$
$$Z = \frac{\overline{x_{A}} + \overline{x_{B}}}{\sqrt{ S\left( \frac{1}{n} + \frac{1}{m} \right) }} = \frac{24.59 - 25}{\sqrt{ 0.727 \cdot \left( \frac{1}{10} + \frac{1}{190} \right) }}= -1.481$$
Miền bác bỏ $H_0$
$$|Z| > Z_{1 - \frac{\alpha}{2}} = Z_{1 - \frac{0.01}{2}} = 2.575$$
$$\implies 1.481 > 2.575$$
$\implies$ không bác bỏ $H_0$
## Câu 2
### a)
Gọi A là hiệu quả loại thuốc diệt côn trùng loại 1.
Gọi B là hiệu quả loại thuốc diệt côn trùng loại 2.
$$\widehat{p_{A}} = \frac{117}{132} = 0.8863$$
Bài toán kiểm định 
$$\begin{cases}
 H_{0} : \hat{p} = 90\% \\
H_{a} : \hat{p} > 90\%
\end{cases}$$
Thống kê kiểm định : 

$$Z = \frac{(0.8863 - 0.9)\sqrt{132}}{\sqrt{ 0.9( 1 - 0.9)}} = -0.524$$
$p$-giá trị : 
$$1 - \Phi(Z) = 1 - \Phi(-0.524) = 0.7$$
$\implies$ ko bác bỏ $H_0$
### b)
Bài toán kiểm định 
$$\begin{cases}
H_{0} : p_{A} = p_{B} \\
H_{a} : p_{A} \neq p_{B}
\end{cases}$$
$$\hat{p_{B}} = \frac{112}{132} = 0.848$$
$$\hat{p} = \frac{117 + 112}{132 + 132} = 0.867$$
Thống kê kiểm định :
$$Z = \frac{0.886 - 0.848}{\sqrt{ 0.867 (1 - 0.867) (1/n)+1/m}} = 0.1119$$
Miền bác bỏ $H_0$ :
$$|Z| > Z_{1 - \frac{\alpha}{2}} = Z_{1 - \frac{0.01}{2}} = 2.575$$
$$\implies 0.1119 > 2.575$$
$\implies$ Không bác bỏ 
## Câu 3
### a)
$$S_{XX} =\sum x_{i}^2 - \frac{\left( \sum x_{i} \right)^2}{n} =   106024 - \frac{1352^2}{18} = 4473.7$$
$$S_{XY} = \sum x_{i}y_{i} - \frac{\sum x_{i}\sum y_{i}}{n} = 34853.976 - \frac{1352 \cdot 444.848}{18} = 1440.948$$
$$\beta_{1} = \frac{S_{XY}}{S_{XX}} = \frac{1440.948}{4473.7} = 0.322$$
$$\beta_{0} = \overline{y} - \beta_{1}\overline{x} = \frac{444.848}{18} - 0.322\cdot \frac{1352}{18} = 0.528$$
Phương trình hồi quy tuyến tính :
$$\hat{y} = 0.528 + 0.322 \cdot x$$
### b)
$$\hat{y} = 0.528 + 0.332 \cdot 68 = 23.104$$
độ tăng huyết áp trung bình là $23.104$.
### c)

> [!NOTE] Title
> $$R = \beta \cdot \frac{S_{xy}}{S_{yy}}$$

$$S_{YY} = \sum y_{i}^2 - \frac{\left( \sum y_{i} \right)^2}{n} = 11460.641 - \frac{444.848^2}{18} = 466.766$$
$$r_{xy}^2 = \frac{S_{XY}^2}{S_{XX} \cdot S_{YY}} = \frac{1440.948^2}{4473.7 \cdot 466.766} = 0.9943$$
$$R^2 = r_{xy}^2 = 0.9943$$
mối liên hệ giữa tiếng ồn và độ tăng huyết áp tương quan càng mạnh vì gần về 1.
## Câu 4
### a)

$$P(X < 12) = 0.1 \implies P(X < -1.28) = 0.1$$
$$\frac{12 - 14}{\sqrt{ \sigma}} = -1.28 \implies \sigma = \frac{12-14}{-1.28}= 1.5625$$
### b)
$$X \sim B(15, 0.1)$$
$$P(X < 2) = \sum^1_{k= 0} C_{n}^kp^k(1 - p)^{n - k} = 0.54$$
### c)
$$P(X < 9) = P\left( X < \frac{9 - 0.5 + np}{\sqrt{npq}} \right)  $$
