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
