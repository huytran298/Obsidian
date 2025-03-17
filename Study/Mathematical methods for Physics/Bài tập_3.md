## Câu 1
Phương trình Laplace trong toạ độ $(x, y)$ là :
$$\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0$$
Chuyển đổi hệ toạ độ $(r, \theta)$ ta có :
$$x = r \cos \theta, y = r \sin \theta$$
$$\frac{\partial u}{\partial x} = \frac{\partial u}{\partial r} \frac{\partial r}{\partial x} + \frac{\partial u}{\partial \theta} \frac{\partial \theta}{\partial x}$$
$$\frac{\partial u}{\partial y} = \frac{\partial u}{\partial r} \frac{\partial r}{\partial y} + \frac{\partial u}{\partial \theta} \frac{\partial \theta}{\partial y}$$
Mà 
$$\frac{\partial r}{\partial x} = \cos \theta,\frac{\partial r}{\partial y} = \sin \theta $$
$$\frac{\partial \theta}{\partial x} = \left( -\frac{\sin \theta}{r} \right), \frac{\partial \theta}{\partial y} = \left( \frac{\cos \theta}{r} \right)$$
$$\begin{equation}
\frac{\partial^2 u}{\partial x^2} = \frac{\cos^2\theta \partial^2 u}{\partial r^2} - 2 \frac{\sin \theta \cos \theta}{r}  \frac{\partial^2 u}{\partial r \partial \theta} + \frac{\sin^2\theta}{r}\frac{\partial u}{\partial r} + \frac{\sin^2\theta}{r^2}\frac{\partial^2u}{\partial \theta^2}
\end{equation}$$

$$\begin{equation}
\frac{\partial^2u}{\partial y^2} = \sin^2\theta \cdot \frac{\partial^2u}{\partial r^2} + 2\cdot \frac{\sin \theta \cos \theta}{r}\cdot \frac{\partial^2u}{\partial r \partial \theta} + \frac{\cos^2\theta}{r}\cdot \frac{\partial u}{\partial r} + \frac{\cos^2\theta}{r^2} \cdot \frac{\partial^2u}{\partial \theta^2}
\end{equation}$$

Từ $(1), (2)$ ta có:
$$\frac{\partial^2u}{\partial r^2} + \frac{1}{r} \frac{\partial u}{\partial r} + \frac{1}{r^2} \frac{\partial^2u}{\partial \theta^2} = 0$$
## Câu 2
### Phương trình (1)
$$u_{y} = \frac{\partial u}{\partial y} = \frac{\partial u}{\partial \xi} \frac{\partial \xi}{\partial y} + \frac{\partial u}{\partial \eta} \frac{\partial \eta}{\partial y} = u_{\xi}\xi_{y} + u_{\eta}\eta_{y}$$
### Phương trình (2)
Ta có :
$$u_{x} = u_{\xi}\cdot\xi_{x} + u_{\eta}\cdot\eta_{x} $$
$$\implies u_{xy} = \frac{\partial}{\partial y}(u_{x}) = \frac{\partial}{\partial y}(u_{\xi}\cdot\xi_{x} + u_{\eta}\cdot\eta_{x}) = \frac{\partial}{\partial y}(u_{\xi}\cdot\xi_{x}) + \frac{\partial}{\partial y}(u_{\eta}\cdot\eta_{x})$$
$$= \left( \frac{\partial u_{\xi}}{\partial y}\cdot\xi_{x} + u_{\xi}\cdot\xi_{xy} \right) + \left( \frac{\partial u_{\eta}}{\partial y}\cdot\eta_{x} + u_{\eta}\cdot\eta_{xy} \right)$$
$$\begin{equation}
\frac{\partial u_{\xi}}{\partial y} = \frac{\partial u_{\xi}}{\partial \xi}\frac{\partial \xi}{\partial y} + \frac{\partial u_{\xi}}{\partial \eta} \frac{\partial \eta}{\partial y} =  u_{\xi \xi}\cdot \xi_{y}+u_{\xi \eta}\cdot\eta_{y} \tag{1}
\end{equation}$$
$$\begin{equation}
\frac{\partial u_{\eta}}{\partial y} = \frac{\partial u_{\eta}}{\partial \xi}\frac{\partial \xi}{\partial y} + \frac{\partial u_{\eta}}{\partial \eta} \frac{\partial \eta}{\partial y} =  u_{\eta \xi}\cdot \xi_{y}+u_{\eta \eta}\cdot\eta_{y} \tag{2}
\end{equation}$$
Từ $(1),(2)$ ta có:
$$=(u_{\xi \xi}\cdot \xi_{y}+u_{\xi \eta}\eta_{y})\cdot\xi_{x}+u_{\xi}\cdot\xi_{xy} + (u_{\eta \xi}\cdot \xi_{y}+u_{\eta \eta}\cdot\eta_{y} )\eta_{x} + u_{\eta}\cdot\eta_{xy}$$
$$=u_{\xi \xi}\cdot\xi_{x}\cdot \xi_{y} + u_{\xi \eta}\cdot\eta_{y}\cdot\xi_{x} + u_{\xi}\cdot \xi_{xy} + u_{\xi \eta}\cdot \xi_{y}\eta_{x} + u_{\eta \eta} \cdot \eta_{x} \cdot \eta_{y} + u_{\eta}\cdot \eta_{xy}$$
$$=u_{\xi \xi}\cdot\xi_{x}\cdot \xi_{y} + u_{\xi \eta}(\xi_{x}\eta_{y} + \xi_{y}\eta_{x})+ u_{\xi}\cdot \xi_{xy}  + u_{\eta \eta} \cdot \eta_{x} \cdot \eta_{y} + u_{\eta}\cdot \eta_{xy}$$
### Phương trình (3)
$$u_{y} = u_{\xi}\cdot\xi_{y} + u_{\eta}\cdot\eta_{y} $$
$$\implies u_{yy} = \frac{\partial}{\partial y}(u_{y}) = \frac{\partial}{\partial y}(u_{\xi}\cdot\xi_{y} + u_{\eta}\cdot\eta_{y}) = \frac{\partial}{\partial y}(u_{\xi}\cdot\xi_{y}) + \frac{\partial}{\partial y}(u_{\eta}\cdot\eta_{y})$$
$$= \left( \frac{\partial u_{\xi}}{\partial y}\cdot\xi_{x} + u_{\xi}\cdot\xi_{yy} \right) + \left( \frac{\partial u_{\eta}}{\partial y}\cdot\eta_{x} + u_{\eta}\cdot\eta_{yy} \right)$$
$$\begin{equation}
\frac{\partial u_{\xi}}{\partial y} = \frac{\partial u_{\xi}}{\partial \xi}\frac{\partial \xi}{\partial y} + \frac{\partial u_{\xi}}{\partial \eta} \frac{\partial \eta}{\partial y} =  u_{\xi \xi}\cdot \xi_{y}+u_{\xi \eta}\cdot\eta_{y} \tag{1}
\end{equation}$$
$$\begin{equation}
\frac{\partial u_{\eta}}{\partial y} = \frac{\partial u_{\eta}}{\partial \xi}\frac{\partial \xi}{\partial y} + \frac{\partial u_{\eta}}{\partial \eta} \frac{\partial \eta}{\partial y} =  u_{\eta \xi}\cdot \xi_{y}+u_{\eta \eta}\cdot\eta_{y} \tag{2}
\end{equation}$$
Từ $(1),(2)$ ta có:
$$=(u_{\xi \xi}\cdot \xi_{y}+u_{\xi \eta}\eta_{y})\cdot\xi_{y}+u_{\xi}\cdot\xi_{yy} + (u_{\eta \xi}\cdot \xi_{y}+u_{\eta \eta}\cdot\eta_{y} )\eta_{y} + u_{\eta}\cdot\eta_{yy}$$
$$=\xi^2_{y}\cdot u_{\xi \xi} + u_{\xi \eta}\cdot\eta_{y}\cdot\xi_{y} + u_{\xi}\cdot\xi_{yy} + u_{\xi \eta}\cdot\xi_{y}\cdot\eta_{y} + u_{\eta \eta}\eta^2_{y} + u_{\eta}\cdot \eta_{yy}$$
$$=\xi^2_{y}\cdot u_{\xi \xi} + 2\cdot u_{\xi \eta}\cdot\eta_{y}\cdot\xi_{y} + u_{\xi}\cdot\xi_{yy} + u_{\eta \eta}\eta^2_{y} + u_{\eta}\cdot \eta_{yy}$$
