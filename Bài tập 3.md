## Bài 1
### a)
$$\begin{gather}
e^{2xt - t^2} = \sum^\infty_{n = 0} H_{n}(x) \frac{t^n}{n!} \\
e^{-t} = \sum^\infty_{n = 0} H_{n}(0) \frac{t^n}{n!} = \sum^\infty_{k = 0} (-1)^{k}\frac{t^{2k}}{k!}
\end{gather}$$
Biểu thức cho thấy $t$ phải cùng luỹ thừa nên $n = 2k$ :
$$\begin{gather}
\frac{H_{2k}(0)}{(2k)!} = (-1)^k\frac{1}{k!} \implies H_{2n} = (-1)^n \frac{(2n)!}{n!}
\end{gather}$$
### b)
Như câu trên, nếu $2n + 1$ biểu thức ở trên sẽ là :
$$e^{-t} = \sum^\infty_{n = 0} H_{2n + 1}(0) \frac{t^{2n + 1}}{(2n + 1)!} = \sum^\infty_{k = 0} (-1)^{k}\frac{t^{2k}}{k!}$$
Sẽ không tồn tại luỹ thừa $t^{2n + 1} = t^2k \, \forall n \geq 0$
Vì vậy, 
$$H_{2n + 1}(0) = 0$$
### c)
Ta có : 
$$H_{2n}'(0) = 2(2n)H_{2n-1}(0)$$
Lại có :
$$\begin{gather}
H_{2n - 1}(0) = 0 \implies H_{2n}'(0) = 0
\end{gather}$$
### d)
$$\begin{gather}
H'_{2n + 1}(0) = 2(2n + 1)H_{2n}(0)  \\
= 2(2n + 1)(-1)^n \frac{(2n)!}{n!} \\
= \frac{(2n + 1)(2n + 2)}{(n + 1)} \frac{(2n)!}{n!}(-1)^n \\
= \frac{(2n + 2)!}{(n + 1)!}(-1^n)
\end{gather}$$
## Bài 2

## Bài 4
### a)
Ta có :
$$\begin{gather}
(1 - t)^{-1} e^{-xt/(1 - t)} = \sum^\infty_{n = 0}L_{n}(x)t^n \\
\implies (1-t)^{-1}e^{-0\cdot t/(1 - t)} = \sum^\infty_{n = 0}L_{n}(0)t^n \\
(1- t)^{-1} = \sum^\infty_{n = 0}L_{n}(0)t^n
\end{gather}$$
Vì 
$$\sum^\infty_{n = 0} t^n= (1- t)^{-1} \implies L_{n}(0) = 1$$
### b)
Ta có :
$$\begin{gather}
xL''_{n}(x) + (1 - x)L'_{n}(x) + nL_{n}(x) = 0 \\
\implies 0 \cdot L''_{n}(0) + (1 - 0)L'_{n}(0) + nL_{n}(0) = 0 \\
L'_{n}(0) + n = 0 \implies L'_{n}(0) = -n
\end{gather}$$
### c)
Ta có : 
$$xL''_{n}(x) + (1 - x)L'_{n}(x) + nL_{n}(x) = 0 $$
Đạo hàm 2 vế : 
$$\begin{gather}
L''_{n}(x) + xL^{(3)}_{n}(x) + L''_{n}(x)(1 - x) - L'_{n}(x) + nL'_{n}(x) = 0 \\
\implies  
L''_{n}(0) + 0 \cdot L^{(3)}_{n}(0) + L''_{n}(0)(1 - 0) - L'_{n}(0) + nL'_{n}(0) = 0 \\
2L''_{n}(0) + n - n^2 = 0 \implies L''_{n}(0) = \frac{n(n - 1)}{2}
\end{gather}$$
## Bài 5
### 11.

### 12.
$$\begin{gather}
L_{k}(t) = \sum^k_{q = 0} \frac{(-1)^q C^k_{q}}{q!} t^q \\
L_{n}(x - t) = \sum^n_{p = 0} \frac{(-1)^p C^n_{p}}{p!} (x - t)^p
\end{gather}$$
