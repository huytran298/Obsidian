
---
Giả sử ban đầu photon có năng lượng $E_\gamma$ và động lượng $p_\gamma = \frac{h}{\lambda}$
va chạm với electron có năng lượng $E_{e} = m_{e}c^2$ và động lượng $p_{e} = 0$ và photon bị mất 1 phần năng lượng và bị tán xạ 1 góc $\theta$ hợp với phương photon trước va chạm. 

---
Sau va chạm ta có bảo toàn động lượng : 
$$\begin{gather}
\vec{p}_{\gamma} = \vec{p}'_{\gamma} + \vec{p}'_{e} \\
\vec{p}'_{e} = \vec{p}'_{\gamma} - \vec{p}_{\gamma} \\
p_{e}'^2 = p'^2_{\gamma} + p^2_{\gamma} + 2p'_{\gamma}p_{\gamma}\cos(\pi-\theta) \\
p_{e}'^2 = p'^2_{\gamma} + p^2_{\gamma} - 2p'_{\gamma}p_{\gamma}\cos(\theta)  \\
p'^2_{e}c^2 = p'^2_{\gamma}c^2 + p^2_{\gamma} c^2 - 2c^2p'_{\gamma}p_{\gamma}\cos(\theta) \\
\end{gather}$$
Lại có :
$$\begin{gather}
p_{\gamma}^2 = \left( \frac{E_{\gamma}}{c^2}\cdot c \right)^2 = \frac{E_{\gamma}^2}{c^2} \implies p^2_{\gamma}c^2 = E^2_\gamma &(*)\\
p_{\gamma}p'_{\gamma}c^2 = \frac{E_{\gamma}}{c} \frac{E'_{\gamma}}{c} c^2 = E_{\gamma}E'_{\gamma} & (**)
\end{gather}$$
Từ $(*), (* *)$ có :
$$\begin{gather}
p'^2_{e}c^2 = E'^2_{\gamma} + E_{\gamma}^2 - 2E_{\gamma}E'_{\gamma}\cos (\theta) \\
=  E'^2_{\gamma} + E_{\gamma}^2 -2E_{\gamma}E'_{\gamma}\cos (\theta) + 2E_{\gamma}E'_{\gamma} - 2E_{\gamma}E'_{\gamma}  \\
= (E'_{\gamma} - E_{\gamma})^2 + 2E_{\gamma}E'_{\gamma}(1 - \cos \theta)
\end{gather}$$
Lại có : 
$$\begin{gather} 
E_{e}'^2 = E_{e} + E_{\gamma} - E_{\gamma}'
 \\
E_{e}'^2 = (p'_{e}c)^2 + E_{e}^2  \\
\implies (p'_{e}c)^2 = (E_{e} + h\nu - h\nu' )^2 - E_{e}^2
\end{gather}$$
Ta có : 
$$\begin{gather}
(E_{e} + h\nu - h\nu' )^2 - E_{e}^2 = E'^2_{\gamma} + E_{\gamma}^2 - 2E_{\gamma}E'_{\gamma}\cos (\theta) \\
E_{e}^2 + 2E_{e}(E_{\gamma} - E_{\gamma}') + (E_{\gamma} - E_{\gamma}')^2 - E_{e}^2  = E'^2_{\gamma} + E_{\gamma}^2 - 2E_{\gamma}E'_{\gamma}\cos (\theta) \\
(E_{\gamma}-E'_{\gamma}) = \frac{E_{\gamma}E'_{\gamma}(1 - \cos \theta)}{E_{e}} \\
h\nu - h\nu' = \frac{h^2\nu \nu'(1-\cos \theta)}{m_{e}c^2} \\
\nu - \nu' =  \frac{h\nu \nu'(1-\cos \theta)}{m_{e}c^2}  \\
c \left( \frac{\lambda-\lambda'}{\lambda \lambda'} \right) = \frac{c^2}{\lambda \lambda'} \frac{h}{m_{e}c^2}(1-\cos \theta) \\
\lambda - \lambda' = \frac{h}{m_{e}c}(1-\cos \theta)
\end{gather}$$
Công thức trên còn được gọi là ***Dịch chuyển bước sóng Compton***
Từ công thức trên tiếp tục suy ra được : 
$$\begin{gather}
E_{\gamma} = E'_{\gamma}\left( 1 + \frac{E_{\gamma}(1-\cos \theta)}{m_{e}c^2} \right) \\
E'_{\gamma} = \frac{E_{\gamma}}{1 + \frac{E_{\gamma}}{m_{e}c^2}(1-\cos \theta)} \\
\end{gather}$$
