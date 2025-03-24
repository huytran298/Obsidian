# Họ và tên : Trần Quốc Huy
# MSSV : 23230005
Ta có phương trình :
$$U_{x x} + 6U_{xy} + 5U_{yy} = 0$$
$$\implies A = 1, B = 3, C = 5 \implies \Delta = B^2 - AC = 3^2 - 1\cdot 5 = 4 > 0$$
$$\Delta > 0 \implies \frac{dy}{dx} = \frac{3 \pm \sqrt{4 }}{1} $$
$$\begin{cases}
\frac{dy}{dx} = 5 \Leftrightarrow dy = 5dx \implies y = 5x + C \Leftrightarrow C = 5x - y \\
\frac{dy}{dx} = 1 \Leftrightarrow dy = dx \implies y = x + C \Leftrightarrow C = x - y \\
\end{cases}$$

Đặt : 
$$\xi = C = 5x - y, \eta = C = x - y$$
$$\begin{cases}
\xi_{x} = 5, \xi_{xx} = \xi_{xy} = \xi_{yy} = 0, \xi_{y} = -1  \\
\eta_{x} = 1, \eta_{xx} = \eta_{xy} = \eta_{yy} = 0, \eta_{y} = -1
\end{cases}$$

$$U_{xx} = U_{\xi \xi} 5^2 + 2  U_{\xi \eta}  5  1 + U_{\eta \eta}  1^2 + U_{\xi} 0+ U_{\eta}0$$
$$\Leftrightarrow U_{xx} = 25 U_{\xi \xi} + 10  U_{\xi \eta} + U_{\eta \eta}$$
$$U_{xy} = U_{\xi \xi}(-1) 5 + U_{\xi \eta}(5 (-1) + (-1)  1) + U_{\eta \eta} 1 (-1) + U_{\xi}  0 + U_{\eta} 0$$
$$\Leftrightarrow U_{xy} = -5U_{\xi \xi}  -6U_{\xi \eta}-U_{\eta \eta} $$
$$U_{yy} = U_{\xi \xi}(-1)^2 + 2U_{\xi \eta}(-1)(-1) + U_{\eta \eta}(-1)^2 + U_{\xi}0+U_{\eta}0$$
$$\Leftrightarrow U_{yy} = U_{\xi \xi} + 2U_{\xi \eta} + U_{\eta \eta}$$
Thay vào phương trình ta có :
$$25U_{\xi \xi} + 10U_{\xi \eta} + U_{\eta \eta} + 6(-5U_{\xi \xi} - 6U_{\xi \eta} -U_{\eta \eta}) + 5(U_{\xi \xi} + 2U_{\xi \eta} + U_{\eta \eta}) =0$$
$$25U_{\xi \xi} + 10U_{\xi \eta} + U_{\eta \eta} -30U_{\xi \xi} - 36U_{\xi \eta} -6U_{\eta \eta} + 5U_{\xi \xi} + 10U_{\xi \eta} + 5U_{\eta \eta} =0$$
$$\implies -16U_{\xi \eta} = 0 \Leftrightarrow U_{\xi \eta} = 0$$
Giả sử :
$$U(x, y) = F(\xi) + G(\eta) = F(5x - y) + G(x-y)$$
$$\implies U(0, y) = F(-y) + G(-y) = y^2$$
$$\implies U_{x}(0, y) = 5F'(-y) + G'(-y) = 0 \implies C(Y) = 5F(-y) + G(-y)$$
Lập hệ phương trình ta có :
$$\begin{cases}
F(-y) + G(-y) = y^2  \\
5F(-y) + G(-y) = C
\end{cases}$$
$$\Leftrightarrow -4F(-y) = y^2 - C \implies F(-y) = \frac{C}{4} - \frac{y^2}{4}$$
$$G(-y) = y^2 - F(-y) = y^2 - \frac{C}{4} + \frac{y^2}{4} = -\frac{C}{4} + \frac{5y^2}{4}$$
Vì $U(x,y) = F(5x-y) + G(x-y)$ 
$$F(5x-y) + G(x-y) = \frac{C}{4} - \frac{(y - 5x)^2}{4} - \frac{C}{4} + \frac{5(y - x)^2}{4}$$
$$\Leftrightarrow U(x, y) = y^2 - 5x$$