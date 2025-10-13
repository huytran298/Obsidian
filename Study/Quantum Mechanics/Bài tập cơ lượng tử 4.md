<center><h2>Họ và tên : Trần Quốc Huy</h2>

<h3>MSSV : 23230005</h3>
<h4>Bài tập về nhà - Cơ lượng tử</h4>
</center>

## Bài 1
### a)
Ta có :
$$\begin{gather}
\langle \chi |\chi\rangle = \chi^* \ \chi = |A|^2\ (|(3-2i)|^2 + |(1 + 3i)|^2)  = 1 \\
 |A|^2(13 + 10) = 1 \\
A = \frac{1}{\sqrt{ 23 }}
\end{gather}$$
### b)
Ta có : 
$$\begin{gather}
\langle +z | \chi\rangle = (\begin{matrix}
1 & 0
\end{matrix}) \cdot \frac{1}{\sqrt{ 23 }}\left(\begin{matrix}
3 - 2i \\
1 + 3i
\end{matrix}\right) = \frac{1}{\sqrt{ 23 }}\left(3 - 2i\right) \\
\implies P\left( \frac{\hbar}{2} \right) = |\langle +z | \chi\rangle |^2 = \left|\frac{3 - 2i}{\sqrt{ 23 }} \right|^2 = \frac{13}{23} \\
\langle -z | \chi\rangle = (\begin{matrix}
0 & 1
\end{matrix}) \cdot \frac{1}{\sqrt{ 23 }}\left(\begin{matrix}
3 - 2i \\
1 + 3i
\end{matrix}\right) = \frac{1}{\sqrt{ 23 }}\left(1 + 3i\right) \\
\implies P\left( \frac{\hbar}{2} \right) = |\langle +z | \chi\rangle |^2 = \left|\frac{1 + 3i}{\sqrt{ 23 }} \right|^2 = \frac{10}{23} \\
\langle S_{z}\rangle = \frac{\hbar}{2}P\left( \frac{\hbar}{2} \right) + \left( -\frac{\hbar}{2} \right)P\left( -\frac{\hbar}{2} \right)  \\
= \frac{\hbar}{2} \cdot \frac{13}{23} - \frac{\hbar}{2} \cdot \frac{10}{23} = \frac{3\hbar}{46}
\end{gather}$$
### c)
$$\begin{gather}
\langle +x | \chi\rangle = \frac{1}{\sqrt{ 2 }}\left(\begin{matrix}
1 & 1
\end{matrix}\right) \cdot \frac{1}{\sqrt{ 23 }}
\left(\begin{matrix}
3 - 2i \\
1 + 3i
\end{matrix}\right)
= \frac{1}{\sqrt{ 46 }}(4 + i) \\
\implies P\left( \frac{\hbar}{2} \right) = |\langle+x|\chi\rangle|^2 = \left|\frac{(4+i)}{\sqrt{ 46 }}\right|^2 = \frac{17}{46} \\
P\left( -\frac{\hbar}{2} \right) = 1- P\left( \frac{\hbar}{2} \right) = 1 - \frac{17}{46} = \frac{29}{46}  \\ \langle S_{x} \rangle = \frac{\hbar}{2} \frac{17}{46} + \left( -\frac{\hbar}{2} \right)\left( \frac{29}{46} \right) = -\frac{3\hbar}{23}
\\
\langle +y|\chi\rangle = \frac{1}{\sqrt{ 2 }}(\begin{matrix}
1 & -i
\end{matrix}) \cdot \frac{1}{\sqrt{ 23 }}\left(\begin{matrix}
3 - 2i \\
1 + 3i
\end{matrix}\right) = \frac{6-3i}{\sqrt{ 46 }} \\
\implies P\left( \frac{\hbar}{2} \right) = |\langle +y|\chi\rangle|^2 = \left| \frac{6-3i}{\sqrt{ 46 }}\right|^2 = \frac{45}{46} \\
\implies P\left( -\frac{\hbar}{2} \right) = 1 - P\left( \frac{\hbar}{2} \right) = 1 - \frac{45}{46} = \frac{1}{46} \\
\langle S_{y} \rangle = \frac{\hbar}{2} \cdot \frac{45}{46} + \left( -\frac{\hbar}{2} \right)\cdot \frac{1}{46} = \frac{11\hbar}{23}
\end{gather} 
$$
### d)
Ta có : 
$$\begin{gather}
H = -\gamma \mathbf{S}\cdot \mathbf{B}
\end{gather}$$
Trong đó : 
$$\mathbf{B} = B_{0}\hat{z}$$
$$\implies H = -\gamma B_{0}S_{z} = -\frac{\gamma B_{0}\hbar}{2}\left(\begin{matrix}
1  & 0 \\
0  & -1
\end{matrix}\right)$$

Từ đó trạng thái riêng của $H$ là các trạng thái riêng của $S_{z}$ :
$$\begin{cases}
E_{+} = -\frac{\gamma B_{0}\hbar}{2} \\
E_{-} = \frac{\gamma B_{0}\hbar}{2}
\end{cases}$$
Trạng thái spin ta có :
$$\begin{gather}
i\hbar \frac{\partial}{\partial t}\chi = H\chi \\
\chi(t) = e^{-iEt/\hbar}\chi(0)
\end{gather}$$
Mà :
$$\chi(0) = \sum c_{i}|E_{i}\rangle$$
$$\implies \chi(t) = \sum c_{i}e^{-iE_{i}t/\hbar}|E_{i}\rangle$$
$$\implies \chi (t) = \frac{1}{\sqrt{ 23 }}\left(\begin{matrix}
(3 - 2i)e^{-iE_{+}t/\hbar} \\
(1 + 3i)e^{-iE_{-}t/\hbar}
\end{matrix}\right)$$
