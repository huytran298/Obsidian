## Bài 1 
### 1.
$$\begin{gather}
P_{2}(x) = \frac{2\cdot 1 + 1}{1 + 1}xP_{1}(x) - \frac{1}{1 + 1}P_{0}(x)  = \frac{3}{2}x^2-\frac{1}{2} \\
P_{3}(x) = \frac{2\cdot 2 + 1}{2 + 1} x\cdot P_{2}(x) - \frac{2}{2 + 1}P_{1}(x) = \frac{5}{3}\left( \frac{3x^3-x}{2}\right) - \frac{2}{3}x \\
P_{4}(x) = \frac{2\cdot 3 + 1}{3 + 1}x\cdot P_{3}(x) - \frac{3}{3 + 1}P_{2}(x)  \\
= \frac{7}{4}\left( \frac{5}{3}\left( \frac{3x^4-x}{2} - \frac{2}{3}x^2 \right) \right) - \frac{3}{4}\left(\frac{3}{2}x^2-\frac{1}{2}\right)
\end{gather}$$
### 2.
- $P_{0}(x) =1 \implies P_{0}(\cos \varphi) = 1$
- $P_{1}(x) = x \implies P_{1}(\cos \varphi) = \cos \varphi$
- $$\begin{gather}
P_{2}(x) = \frac{1}{2}(3x^2 - 1) = P_{2}(\cos \varphi) = \frac{1}{2}(3\cos^2(\varphi) - 1)  \\
=\frac{1}{2}\left( 3\cdot \frac{1 + \cos(2\varphi)}{2} - 1 \right) = \frac{1}{4}(3\cos(2\varphi) + 1)
\end{gather}$$
- $$\begin{gather}
P_{3}(\cos\varphi)
      =\tfrac12\!\bigl(5\cos^{3}\varphi-3\cos\varphi\bigr)\\
      =\tfrac12\!\left[
         5\left(\frac{\cos 3\varphi+3\cos\varphi}{4}\right)-3\cos\varphi
        \right]\\
      =\frac18\left(5\cos 3\varphi+3\cos\varphi\right)
\end{gather}$$
## Bài 2
### 1.
$$\begin{gather}

\int_{0}^{\pi}\cos^{2n+1}\theta\,d\theta
 \\
   =\int_{1}^{-1}\frac{u^{2n+1}}{\sqrt{1-u^{2}}}\,(-du)
 \\
   =\int_{-1}^{1}\frac{u^{2n+1}}{\sqrt{1-u^{2}}}\,du
   =0 \\
\implies\frac{1}{\pi}\int_{0}^{\pi}\cos^{2n+1}\theta\,d\theta=0
\end{gather}$$
### 2.
#### a)
$$\begin{gather}
\int_{0}^\pi \cos^{2n}(\theta) \, d\theta = \int_{\pi/2}^{\pi} \cos^{2n}(\theta) \, d\theta  +\int_{0}^{\pi/2} \cos^{2n}(\theta) \, d\theta =2\int_{0}^{\pi/2} \cos^{2n}(\theta) \, d\theta 
\end{gather}$$
Đặt $u = \pi - \theta \implies du = -d\theta$
Khi đó tích phân $\displaystyle \int^\pi_{\pi/2} \cos^{2n}(\theta)\, d\theta$ ta có : 
$$\begin{gather}
\int^0_{\pi/2}\cos^{2n}(\pi - u)\, (-du) =\int^{\pi /2}_{0}\cos^{2n}(u)\, du
\end{gather}$$
Vậy ta có : 
$$\begin{gather}
\int_{0}^{\pi / 2} \cos^{2n}(\theta) \, d\theta  +\int_{0}^{\pi/2} \cos^{2n}(\theta) \, d\theta =2\int_{0}^{\pi/2} \cos^{2n}(\theta) \, d\theta & (dpcm)
\end{gather}$$
#### b)
Ta có hàm beta : 
$$\begin{gather}
B(x, y) = \int_{0}^1t^{x - 1}(1 - t)^{y - 1} dt \\
= 2\int^{\pi/2}_{0}\cos^{2x - 1}(\theta) \sin^{2y - 1}(\theta)\, d\theta = \frac{2\Gamma(x)\Gamma(y)}{2\Gamma(x + y)}
\end{gather}$$
Theo đề bài ta có : 
$$\begin{cases}
2x-1 = 2n \\
2y - 1 = 0
\end{cases} \implies 
\begin{cases}
x = \frac{2n+1}{2} \\
y = \frac{1}{2}
\end{cases}$$
Từ đó ta có : 
$$B\left( n + \frac{1}{2}, \frac{1}{2} \right) = \frac{\Gamma\left( n + \frac{1}{2} \right)\Gamma\left( \frac{1}{2} \right)}{2\cdot\Gamma(n + 1)} = \frac{\left( \frac{(2n)! \sqrt{ \pi }}{4^n n!} \right)}{2n!} = \frac{(2n)! \sqrt{ n }}{2^{2n}(n!)^2}$$

## Bài 3 
### 1.
$$\int_{-1}^1xP_{n}(x)\, dx = \int^1_{-1} P_{1}(x)P_{n}(x)\, dx = \begin{cases}
0  & n \neq 1 \\
\frac{2}{3}  & n = 1 \\
\end{cases}$$

### 2.
$$\begin{gather}
I_{n} = \int_{-1}^1xP_{n}(x)P_{n-1}(x) \, dx \\
= \int^1_{-1}\frac{nP_{n-1}(x)+ (n + 1)P_{n + 1}(x)}{2n + 1}P_{n - 1}(x) \, dx  \\
= \frac{n}{2n + 1}\int_{-1}^1P_{n - 1}^2(x)\, dx + \frac{n + 1}{2n + 1}\int^1_{-1}P_{n + 1}(x)P_{n - 1}(x) \, dx \\
= \frac{n}{2n + 1} \frac{2}{2n - 1} = \frac{2n}{(4n^2 - 1)}
\end{gather}$$
### 3.
$$\begin{gather}
\int_{-1}^1 P_{n}(x)P'_{n + 1}(x)\, dx
\end{gather}$$
Đặt 
$$\begin{gather}
u = P_{n}(x) \implies du = P'_{n}(x)\, dx \\
dv = P_{n + 1}'(x) dx \implies v = P_{n + 1}(x)
\end{gather}$$
$$\begin{gather}
P_{n}(x)P_{n + 1}(x)|^1_{-1} - \int^1_{-1}P_{n + 1}(x)P'_{n}(x) \, dx \\
2 - \int_{-1}^1P_{n + 1}(x) \frac{nP_{n - 1}(x) - xP_{n}(x)}{1 - x^2} \, dx = 2 & (dpcm) 
\end{gather}$$
### 5.
Đặt 
$$\begin{gather}
u = (1-x^2)P'_{n}(x)  \\
\implies du =-2xP'_{n}(x) + P''_{n}(x)(1 - x^2)dx \\
dv = P'_{k}(x)dx \implies v = P_{k}(x) \\
\end{gather}$$
Sử dụng tích phân từng phần 
$$\begin{gather}
(1-x^2)P_{n}'(x)P_{k}(x)|^1_{-1} - \int^1_{-1}P_{k}'(x)-2xP'_{n}(x) + P''_{n}(x)(1 - x^2)\,dx \\
= \int^1_{-1}(2xP'_{n}(x) - P''_{n}(x)(1 - x^2))P_{k}(x)\, dx
\end{gather}$$
Lại có phương trình vi phân của Legendre :
$$\begin{gather}
\frac{d}{dx}[(1-x^2)P_{n}'(x)] + n(n + 1)P_{n}(x) = 0  \\
\implies -2xP'_{n}(x) + P''_{n}(x)(1 - x^2) + n(n + 1)P_{n}(x) = 0 \\
\Leftrightarrow 2xP'_{n}(x) - P''_{n}(x)(1 - x^2) = n(n + 1)P_{n}(x) 
\end{gather}$$
Thay vào tích phân ta có :
$$\begin{gather}
\int^1_{-1}n(n+1)P_{n}(x)P_{k}(x)\, dx = n(n + 1)\int^1_{-1}P_{n}(x)P_{k}(x)\, dx = 0  & (k \neq n)\\
\end{gather}$$
## Bài 4
