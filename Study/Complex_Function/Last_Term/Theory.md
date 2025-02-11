# Chương V
## Chuỗi hàm
### Chuỗi Taylor 
#### Taylor I

>*Nếu hàm $f(z)$ giải tích trên đĩa tròn $z : |z - z_0| \le R,$ với $R > 0$, thì chuỗi luỹ thừa :*
>$$\sum_{n = 0}^{\infty} \frac{f^{(n)}(z_0)}{n!} (z - z_0)^n = f(z_0) + f^{'}(z_0)(z-z_0) + f^{''}(z_0)\frac{(z - z_0)^2}{2!} + ...$$

>*Hội tụ về $f(z)$ trên đĩa tròn đó, có nghĩa là ta có.*
>$$f(z) =\sum_{n = 0}^{\infty} \frac{f^{(n)}(z_0)}{n!} (z - z_0)^n $$


#### Chuỗi Laurent I

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



