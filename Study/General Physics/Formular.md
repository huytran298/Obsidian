# Chương 4 : Lý thuyết cổ điển về vật lý nguyên tử
## Phổ nguyên tử của chất khí
> $$\frac{1}{\lambda} = R_{H}\left(\frac{1}{m^2} - \frac{1}{n^2}\right)(m< n)$$
> Trong đó : 
> - $R_{H} = 0.11nm^{-1}$ (hằng số Rydberg)
#### Dãy Lyman
> $$\frac{1}{\lambda} = R_{H}\left(\frac{1}{1^2} - \frac{1}{n^2}\right)(n = 3, 4, 5, \dots)$$
#### Dãy Paschen
> $$\frac{1}{\lambda} = R_{H}\left(\frac{1}{m^2} - \frac{1}{n^2}\right)(n = 4, 5, 6,\dots)$$
#### Dãy brackett
> $$\frac{1}{\lambda} = R_{H}\left(\frac{1}{4^2} - \frac{1}{n^2}\right)(n = 5, 6, 7,\dots)$$
## Mẫu lượng tử của nguyên tử (Mẫu nguyên tử Bohr)
### Phát xạ và hấp thụ photon
> $$E_{n2} - E_{n1} = hf$$
### Bán kính quỹ đạo của $e^-$ được xác định qua moment động lượng 
>$$L = m_{e}vr = n \hbar (n = 1, 2, \dots)$$
## Nguyên tử Hydro
### Năng lượng trong nguyên tử Hydro (năng lượng bán kính dừng)

>$$E_{n} = \frac{ke^2}{2a_{0}} \frac{1}{n^2} = \frac{13.6}{n^2}(eV)$$
### Năng lượng photon hấp thụ / phát xạ trong quá trình electron dịch chuyển giữa quỹ đạo $n$ và $m$.
>$$E_{\gamma} = E_{n} - E_{m} = \frac{ke^2}{2a_{0}}\left[ \frac{1}{m^2} - \frac{1}{n^2} \right]$$

# Chương 5 : Lý thuyết lượng tử của nguyên tử Hydro
## Các hàm sóng xuyên tâm và hàm cầu của nguyên tử Hydro
### Hydrogen atom radial wave functions 

| $n$ | $\ell$ | $R_{n \ell}(r)$                                                                                                              |
| --- | ------ | ---------------------------------------------------------------------------------------------------------------------------- |
| $1$ | $0$    | $$\frac{2}{(a_{0})^{3/2}}e^{-r/a_{0}}$$                                                                                      |
| $2$ | $0$    | $$\frac{\left( 2 - \frac{r}{a_{0}} \right)e^{-r/2a_{0}}}{(2a_{0}^{3/2})}$$                                                   |
| $2$ | $1$    | $$\frac{\frac{r}{a_{0}}e^{-r/2a_{0}}}{\sqrt{3}(2a_{0})^{3/2}}$$                                                              |
| $3$ | $0$    | $$\frac{1}{(a_{0})^{3/2}} \frac{2}{81\sqrt{3 }}\left( 27 - 18 \frac{r}{a_{0}} + 2 \frac{r^2}{a_{0}^2} \right)e^{-r/2a_{0}}$$ |
| $3$ | $1$    | $$\frac{1}{(a_{0})^{3/2}} \frac{4}{81\sqrt{6}}\left( 6 - \frac{r}{a_{0}} \right) \frac{r}{a_{0}} e^{-r/3a_{0}}$$             |
| $3$ | $2$    | $$\frac{1}{(a_{0})^{3/2}} \frac{4}{81\sqrt{30}} \frac{r^2}{a_{0}^2}e^{-r/3a_{0}}$$                                           |

### Normalized spherical harmonics $Y(\theta, \phi)$

| $ell$ | $m_\ell$ |                                  $Y_{\ell m_{\ell}}$                                   |
| ----- | -------- | :------------------------------------------------------------------------------------: |
| $0$   | $0$      |                              $$\frac{1}{2\sqrt{ \pi }}$$                               |
| $1$   | $0$      |                    $$\frac{1}{2}\sqrt{ \frac{3}{\pi} }\cos \theta$$                    |
| $1$   | $\pm 1$  |   $$\mp \frac{1}{2}\sqrt{ \frac{15}{2\pi} }\sin \theta \cos \theta e^{\pm i\theta}$$   |
| $2$   | $0$      |                 $$\frac{1}{4}\sqrt{\frac{5}{\pi}}(3\cos^2\theta - 1)$$                 |
| $2$   | $\pm 1$  |  $$\mp \frac{1}{2} \sqrt{ \frac{15}{2\pi} }\sin \theta \cos \theta e^{\pm i\theta}$$   |
| $2$   | $\pm2$   |         $$\frac{1}{4}\sqrt{ \frac{7}{\pi} }(5\cos^2\theta-3\cos \theta)$$<br>          |
| $3$   | $0$      |        $$\frac{1}{4}\sqrt{ \frac{7}{\pi} }(5 \cos^3\theta - 3\cos \theta)$$<br>        |
| $3$   | $\pm1$   | $$\mp \frac{1}{8}\sqrt{ \frac{21}{\pi} }\sin \theta(5\cos^2\theta-1)e^{\pm 2i\theta}$$ |
| $3$   | $\pm 2$  | $$\frac{1}{4}\sqrt{ \frac{105}{2\pi} }\sin^2\theta \cos \theta e^{\pm 2i\theta}$$<br>  |
| $3$   | $\pm 3$  |      $$\mp \frac{1}{8}\sqrt{ \frac{35}{\pi} }\sin^3\theta e^{\pm 3i\theta}$$<br>       |
