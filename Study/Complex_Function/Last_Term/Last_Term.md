![[exam.pdf]]

# Bài giải 

### Câu 3
#### a)
Đặt $w = z - 1$. Ta có :
$$f(z) = \frac{1}{z - 3} = \frac{1}{(z - 1) - 2} = \frac{1}{w - 2} = - \frac{1}{2 - w} = -\frac{1}{2} \frac{1}{1 - \frac{w}{2}}$$
Ta có chuỗi hội tụ:
$$\frac{1}{1 - a} = \sum^\infty_{n = 0}a^n$$
Vì chuỗi trên hội tụ khi $|a| < 1 \implies |\frac{w}{2}| < 1 \implies |z-1|<2$, nên thõa mãn yêu cầu.
Ta có :
$$\frac{1}{1 - \frac{w}{2}} = \sum^\infty_{n = 0}\left( \frac{w}{2} \right)^n = \sum^\infty_{n = 0}\left( \frac{z - 1}{2} \right)^n$$
#### b)
Ta có : 
$$f(z) = \frac{1}{1 - z} = -\frac{1}{z}\cdot \frac{1}{1 - \frac{1}{z}}$$
Đặt $w = \frac{1}{z}$, do đang xét trong vành khăn $1 < |z| < \infty$ nên $|w| < 1$. Ta có :
$$\implies \frac{1}{1 - w}$$
Khai triển Taylor cho hàm $\frac{1}{1 - w}$ ta được :
$$\frac{1}{1 - w} = 1 + w + w^2 + \dots = 1 + \frac{1}{z} + \frac{1}{z^2} + \dots$$
### Câu 4
#### a)
$$L\{f(t)\} = F(s)= \int_{0}^{+\infty}f(t)e^{-st}\,dt = e^{-2t}\cosh 5t e^{-st}\, dt$$


$$= \frac{s + 2}{(s + 2)^2 - 5^2}$$
---
$$L\{f(t)\} = F(s) = \int_{0}^{+\infty} f(t)\,dt = \int_{0}^{+\infty} e^{3t}(3\sin 3t - 4\cos 2t + t^2)\,dt $$
đặt $g(t) = 3\sin 3t - 4\cos 2t + t^2 \implies f(t) = e^{3t}g(t)$ Ta có :
$$L\{f(t)\} = L\{e^{3t}g(t)\} = F(s - 3) = \int_{0}^{+\infty} 3\sin 3t - 4\cos 2t + t^2\,dt$$
$$\Leftrightarrow \int_{0}^{+\infty}3\sin 3t\, dt - \int_{0}^{+\infty} 4\cos 2t\, dt + \int_{0}^{+\infty} t^2 \,dt$$
$$F(s) = 3 \cdot \frac{3}{(s-3)^2 + 3^2} - 4\cdot \frac{s - 3}{(s - 3)^2 + 2^2} + \frac{2!}{(s - 3)^3}$$
#### b)
Ta có :
$$F(s) = \frac{1}{s^2 - 9} = \frac{1}{3} \frac{3}{s^2 - 9} \implies L^{-1}\{F(s)\} = \frac{1}{3} L^{-1}\{ \frac{3}{s^2 - 9}\}$$

Dựa vào phép biến đổi Laplace xuôi ta thấy :
$$f(t) = \sinh 3t \implies L\{f(t)\} = \frac{3}{s^2 - 9}$$
Vậy biến đổi Laplace ngược của hàm đã cho là :
$$\frac{1}{3} L^{-1}\left\{  \frac{3}{s^2 - 9} \right\} = \frac{1}{3}\cdot \sinh 3t$$
---
$$F(s) = \frac{s - 2}{s^2 -4s + 8} = \frac{s - 2}{s^2 - 2 \cdot 2s + 2^2 + 2} = \frac{s - 2}{(s - 2)^2 + 4}$$
Dựa vào phép biến đổi Laplace xuôi ta có :
$$f(t) = \cos 2t \implies L\{f(t)\} = \frac{s}{s^2 + 2^2}$$
Sử dụng tính chất dời theo $s$ , ta có :
$$L\{e^{2t}f(t)\} = \frac{s - 2}{(s - 2)^2 + 2^2}$$
Vậy biến đổi Laplace ngược của hàm đã cho là :
$$L^{-1}\{F(s)\} = e^{2t}\cos 2t$$
#### c)
$$L\{y(t)\} = Y(s)$$
$$L\{y'(t)\} = sY(s) - y(0) = sY(s)$$
$$L\{y''(t)\} = s^2Y(s) - sy(0) - y'(0) = s^2Y(s) - 5$$
$$L\{4e^{2t}\} = 4 \cdot \frac{1}{s - 2}$$
Lấy Laplace 2 vế ta có :
$$L\{y''\} - 3L\{y'\} + 2L\{y\} = L\{4e^{2t}\}$$
$$s^2Y(s) - 5 - 3sY(s) + 2Y(s) = \frac{4}{s - 2}$$
$$Y(s)(s^2 - 3s + 2) = \frac{4}{s - 2} + 5$$
$$Y(s) = \frac{4 + 5(s - 2)}{(s - 2)(s^2 - 3s + 2)} = \frac{-6 + 5s}{(s - 2)(s^2 - 3s + 2)}$$
$$Y(s) = \frac{-6 + 5s}{(s - 2)^2(s - 1)}$$
$$Y(s) = \frac{A}{s - 1} + \frac{B}{(s - 2)} + \frac{C}{(s - 2)^2}$$
$$\implies 5s - 6 = A(s - 2)^2 + B(s-2)(s-1) + C( s- 1)$$
$$5s - 6 = As^2 - 4As + 4A + Bs^2 - 3Bs + 2B + Cs - C$$
$$5s - 6 = s^2(A + B) + s(-4A - 3B + C) + 4A + 2B - C$$
$$Y(s) =  \frac{-1}{s - 1} + \frac{1}{s - 2} + \frac{4}{(s - 2)^2}$$
$$L^{-1}\{Y(s)\} = L^{-1}\left\{ -\frac{-1}{s - 1} \right\}  + L^{-1}\left\{ \frac{1}{s - 2} \right\} + L^{-1}\left\{ \frac{4}{(s - 2)^2} \right\} $$
$$y(t) = -e^{t} + e^{2t} + 4te^{2t}$$
---
