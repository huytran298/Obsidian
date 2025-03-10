![[[2]-BT.gif]]
# Họ và tên : Trần Quốc Huy
# MSSV : 23230005
## Câu 1
Ta có hình vẽ từ 2 hàm $\sin(x - ct)$ và $\sin (x + ct)$ như sau :
![[waveform.png]]
Nhận xét : 
- tại $t = 0$ : đồ thị có dạng $\sin x$
- $sin (ct - x)$ : đồ thị có dạng sóng lan truyền về bên phải của đồ thị.
- $\sin(ct + x)$ : đồ thị có dạng sóng lan truyền về bên trái đồ thị. 
$\implies$ Sóng lan truyền theo 2 phía.
## Câu 2
Ta có hình vẽ phương trình sóng trên miền vô hạn như sau :
![[Pasted image 20250310234449.png]]
Nhận xét :
- từ $[-1, 0]$ : hàm $u(x, 0) = 1 + x$ 
- từ $[0, 1]$ : hàm $u(x, 0) = 1 - x$
- TH còn lại : $u(x, 0) = 0$

## Câu 3 

Tổng quát hóa ta có : 
$\frac{\partial^2 y}{\partial t^2} = 4 \frac{\partial^2y}{\partial x^2} \implies C^2 = 4 \implies C = 2$
$y(x, 0) = f(x) = \sin x$
$\frac{\partial y}{\partial x}(x, 0) = g(x) = 0$
Nghiệm duy nhất cho lời giải $D'Alembert$ là :
$$y(x, t)=\frac{1}{2}(f(x +ct) + f(x - ct)) + \frac{1}{2C}\int_{x - ct}^{x + ct}g(\tau)d\tau$$
$$y(x,t) = \frac{1}{2}(\sin(x + ct) + \sin(x - ct))+\frac{1}{4} (x + ct - x + ct)$$
$$y(x, t) = \frac{1}{2}(\sin (x + ct) + \sin(x - ct)) + \frac{1}{2}ct$$


