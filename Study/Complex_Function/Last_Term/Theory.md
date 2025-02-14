# Chương V
## Chuỗi hàm
### Chuỗi Taylor 
#### Taylor I
##### Định lý

>*Nếu hàm $f(z)$ giải tích trên đĩa tròn $z : |z - z_0| \le R,$ với $R > 0$, thì chuỗi luỹ thừa :*
>$$\sum_{n = 0}^{\infty} \frac{f^{(n)}(z_0)}{n!} (z - z_0)^n = f(z_0) + f^{'}(z_0)(z-z_0) + f^{''}(z_0)\frac{(z - z_0)^2}{2!} + ...$$

>*Hội tụ về $f(z)$ trên đĩa tròn đó, có nghĩa là ta có.*
>$$f(z) =\sum_{n = 0}^{\infty} \frac{f^{(n)}(z_0)}{n!} (z - z_0)^n $$


#### Chuỗi Laurent I
##### Định nghĩa
> *Khai triển Laurent của một hàm $f(z)$ tại điểm $z_0$ có dạng :*
> $$f(z) = \sum_{n = 0}^{\infty} a_n (z - z_0)^n = a_0 + a_1(z - z_0) + a_2(z - z_0)^2 + ... + \frac{a_{-1}}{z - z_0}+ \frac{a_{-2}}{(z - z_0)^2}$$
> Phần ứng với $n \ge 0$ được gọi là **phần giải tích** của chuỗi Laurent : 
> $$I =  \sum_{n = 0}^{\infty} a_n (z - z_0)^n$$
#### Chuỗi Laurent II

> Phần còn lại, ứng với $n < 0$, sẽ không giải tích tại $z_0$, được gọi là **phần chính** của chuỗi Laurent : 
>$$J = \frac{a_{-1}}{z - z_0} + \frac{a_{-2}}{(z - z_0)^2} + ... $$
>Dĩ nhiên rằng 
>$$I + J =  \sum_{n = -\infty}^{\infty} a_n (z - z_0)^n$$
#### Chuỗi Laurent III
> Cho hàm $f(z)$ giải tích trên hình vành khăn $r < |z - z_0| < R$, với $R > r$. Khi đó tồn tại chuỗi Laurent duy nhất.
> $$f(z) =  \sum_{n = -\infty}^{\infty} a_n (z - z_0)^n$$
> Sao cho $f(z)$ hội tụ trên hình vành khăn đó.
#### Ví dụ 
**Tìm khai triển Laurent ở lân cận điểm $0$ trên hình vành khăn $1 < |z| < \infty$ của hàm***
$$f(z) = \frac{1}{1 - z}$$
Ta viết : 
$$\frac{1}{1 - z} = \frac{-1}{z}\cdot \frac{1}{1 - \frac{1}{z}}$$
Đặt 
$$\sigma = \frac{1}{z}$$
Do ta đang xét $z$ trong miền hình vành khăn, $1 < |z| < \infty$, nên $|\sigma|<1$
Khai triển Taylor cho hàm $\frac{1}{1-z}$ lân cận điểm $0$ ta được :
$$\frac{1}{1 - \sigma} = 1 + \sigma + sigma^2 + ...$$
$$= 1 + \frac{1}{z} + \frac{1}{z^2} + ...$$
$$\Rightarrow \frac{1}{z - 1} = -\frac{1}{z}\cdot \left(1 + \frac{1}{z} + \frac{1} {z^2} + ...\right) = -\frac{1}{z} - \frac{1}{z^2}- \frac{1}{z^3} - ...$$
Đó là khai triển Laurent ở lân cận điểm $0$ trên hình vành khăn $1<|z|<\infty$ của hàm $f(z) = \frac{1}{1 - z}$.

## Thặng số
### Phân loại điểm dị thường
#### Phân loại điểm dị thường cô lập

##### Định nghĩa
>*Điểm $z_0$ gọi là **điểm dị thường cô lập** của hàm $f$ nếu hàm $f$ không xác định tại $z_0$, nhưng xác định và giải tích trong hình vành khăn $0 < |z - z_0| < R$ với $R > 0$*

Và tùy theo phần chính của chuỗi Laurent, ta phân loại điểm dị thường cô lập thành : 
1. Cực bậc $n$ ($n$ hữu hạn).
2. Điểm dị thường cốt yếu ($n$ vô hạn).
#### Cực bậc $n$

Xét chuỗi Laurent của hàm $f(z)$: 
$$f(z) = \sum^{\infty}_{n = -\infty} a_{n}(z-z_{0})^n = a_{0} + a_{1}(z - z_{0}) + a_{2}(z - z_{0})^2 +...+\frac{a_{-1}}{z - z_{0}} + \frac{a_{-2}}{(z - z_{0})^2}+\dots$$

Nếu phần chính của chuỗi Laurent có tới hệ số $a_{-n}\neq 0$, và 
$$a_{-(n + 1)} = _{-(n + 2)} = \dots = a_{-\infty} = 0$$
Thì $z_{0}$ được gọi là **cực bậc n** của hàm $f(z)$.

Khi đó ta có thể viết $f(z)$ dưới dạng 
$$f(z) = \frac{1}{(z - z_{0})^n}\left(a_{-n} + a_{-(n - 1)}(z - z_{0})+\dots\right)$$
$$= \frac{g(z)}{(z - z_{0})^n}$$
Với $g(z) = [a_{-n} + a_{-(n + 1)(z - z_{0})+\dots}]$ giải tích tại $z = z_{0}$ 
#### Cực bậc $n = 1$

##### Trường hợp $n = 1$:
>$$f(z) = \frac{g(z)}{z - z_{0}}$$
>khi đó $z_{0}$ được gọi là ***cực đơn***.
#### Điểm dị thường cốt yếu

khi $n \to \infty$, nghĩa là phần chính của chuỗi Laurent có vô số số hạng, thì $z_{0}$ được gọi là ***điểm dị thường cốt yếu***.
**Ví dụ**. Hàm 
$$f(z) = e^{\frac{1}{z}}$$
có điểm dị thường cốt yếu tại $z = 0$ vì 
$$e^{1/z} = \sum^{\infty}{n = 0} = \frac{1}{n!}\left(\frac{1}{z}\right)^n$$
### Thặng số (Residue)
#### Định nghĩa

> **Thặng số**(hay giá trị thặng dư) của $f(z)$ tại điểm dị thường cô lập $z=a$ được kí hiểu và định nghĩa như sau :
> $$Res[f(z); z = a]= Res_{z = a}f(z) = \frac{1}{2\pi i}\oint_{C}f(z)\,dz$$
> Với $C$ là chu tuyến vất kỳ bao quanh $a$ và nằm trong miền lân cận của $a$ mà $f(z)$ giải tích.

#### Công thức tính thặng số
##### Định lý
>Nếu hàm $f$ có khai triển Laurent trong lân cận của điểm $a$ là
>$$f(z) = \sum^{\infty}_{n = -\infty} = a_{n}(z - a)^n$$
>thì thặng số của $f$ tại $a$ sẽ là : 
>$$Res_{z = a}f(z)= a_{-1}$$
##### Trường hợp 1 : $z = a$ là cực đơn
>Trường hợp này $f(z)$ có dạng
>$$f(z) = \frac{a_{-1}}{z - a} + a_{0} + a_{1}(z - a)+\dots$$
>Thặng số được tính bởi công thức : 
>$$Res_{z = a}f(z) = a_{-1} = \lim_{ z \to a }(z - a)f(z)$$

***Ví dụ***
Tính thặng số tại $z=1$ của hàm :
$$f(z) = \frac{z^2}{z^2 - 1}$$
Ta viết :
$$f(z) = \frac{z^2}{(z - 1)(z + 1)} = \frac{\frac{z^2}{(z + 1)}}{z - 1}$$
Ta thấy $z = 1$ là cực đơn. Vậy ta có :
$$Res_{z = 1}f(z) = a_{-1} = \lim_{z \to 1}f(z)(z - 1) = \frac{1^2}{1 + 1} = \frac{1}{2}$$
##### Trường hợp 2 : $z = a$ là cực bậc $n$
>Thặng số được tính bởi công thức :
>$$Res_{z = a}f(z)= \frac{1}{(n - 1)!}\lim_{ z \to a} \frac{d^{n - 1}}{dz^{n - 1}} [(z - a)^nf(z)]$$

***Ví dụ***
Tính thặng số tại điểm $z = 2$ của hàm 
$$f(z) = \frac{1}{(z - 2)^2(z - 3)}$$
Ta thấy $z = 2$ là cực bậc 2($n = 2$). Do đó ta áp dụng công thức :
$$Res_{z=2}f(z) = \frac{1}{(2 - 1)!}\lim_{ z \to 2 } \frac{d}{dz}[(z - 2)^2f(z)] = \lim_{ z \to 2} \frac{d}{dz}\left(\frac{1}{z-3}\right)=-1$$
##### Trường hợp 3: $f(z) = \frac{h(z)}{g(z)}$, trong đó $h(a) \neq 0, g(a) = 0$ và $g'(a)\neq 0$
>Thặng số được tính bởi công thức :
>$$Res_{z = a}f(z) = \frac{h(a)}{g'(a)}$$

***Ví dụ***
Tính thặng số tại điểm $z = \frac{\pi}{2}$ của hàm :
$$f(z) = \frac{\sin^2z}{\cos z}$$
Đặt $h(z) = \sin^2, g(z) = \cos z$. Hàm $f(z)$ có dạng :
$$f(z) = \frac{h(z)}{g(z)}$$
Với :
$$h\left( \frac{\pi}{2}\right)= 1 \neq 0, g\left( \frac{\pi}{2} \right) = 0, g'\left( \frac{\pi}{2} \right)-1\neq 0$$
$$\implies Res_{z = \frac{\pi}{2}}f(z) = \frac{h\left( \frac{\pi}{2} \right)}{g'\left( \frac{\pi}{2} \right)} = -1$$

#### Định lý thặng số
##### Phát biểu định lý
> Cho hàm $f(z)$ giải tích trong và trên chu tuyến $C$ ngoại trừ tại một số hữu hạn các điểm dị thường cô lập $z_{k}$ không nằm trên $C$.
> $$\oint_{C} f(z)\, dz = 2\pi i\sum_{k} Res_{z = z_{k}} f(z)$$
