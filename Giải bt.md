# Họ và tên : Trần Quốc Huy
# MSSV : 23230005
## Câu 1
### 1. Định nghĩa tập hợp thống kê (Ensemble)

Tập hợp thống kê là một tập các trạng thái vi mô (điểm pha) của hệ có chung một thuộc tính vĩ mô nào đó ở trạng thái cân bằng
### 2. Các loại tập hợp phổ biến

| Loại tập hợp  | Đặc điểm hệ     | Đại lượng bảo toàn | Hàm thế nhiệt động                          |
| ------------- | --------------- | ------------------ | ------------------------------------------- |
| Vi chính tắc  | Hệ kín (cô lập) | $N, V, E$          | Entropy $S = k_{B} \ln \Omega$              |
| Chính tắc     | Hệ đống         | $N, V,T$           | Năng lượng tự do $F = -k_{B}\ln Z$          |
| Chính tắc lớn | Hệ mở           | $\mu, V, T$        | Thế nhiệt động $\Omega_{pot} = -k_{B}\ln Z$ |
### 3. Sự khác nhau 
- Về trao đổi : Hệ vi chính tắc không trao đổi gì, hệ chính tắc trao đổi năng lượng (nhiệt) với bình nhiệt, hệ chính tắc trao đổi cả năng lượng và số hạt
- Về xác suất : Trong hệ vi chính tắc, mọi trạng thái vi mô có xác suất như nhau($1/\Omega$). Trong hệ chính tắc, xác suất tuân theo phân bố Boltzmann ($e^{-\beta E_{i}}$)
## Câu 2
### a) Đối với tập hợp chính tắc : 
1. Thiết lập hệ : Xét một hệ đóng $S$ tiếp xúc và trao đổi năng lượng với một bình nhiệt $R$ ở nhiệt độ $T$. Tổng năng lượng của hệ và bình nhiệt là bảo toàn : $E_{tot} = E_{R} + E_{i}$, trong đó $E_i$ là năng lượng của hệ $S$ ở trạng thái vi mô $i$.
2. Xác suất trạng thái : Xác suất $p_i$ để hệ $S$ ở trạng thái vi mô $i$ tỉ lệ thuận với số trạng thái vi mô của bình nhiệt $\Omega_{R}$ ứng với năng lượng còn lại $(E_{tot} - E_{i})$
$$p_i \propto \Omega_R(E_{tot} - E_i) = \exp\left[\frac{S_R(E_{tot} - E_i)}{k_B}\right]$$
3. hai triển Taylor: Vì hệ $S$ rất nhỏ so với bình nhiệt ($E_i \ll E_{tot}$), ta khai triển Taylor entropy $S_R$ quanh giá trị $E_{tot}$:
$$S_R(E_{tot} - E_i) \approx S_R(E_{tot}) - \left(\frac{\partial S_R}{\partial E}\right) E_i = S_R(E_{tot}) - \frac{E_i}{T}$$
4. Phân bố Boltzmann: Thay vào biểu thức xác suất và chuẩn hóa, ta được phân bố chính tắc7777:
    
    $$p_i = \frac{e^{-\beta E_i}}{Z} \text{ với } \beta = \frac{1}{k_B T}$$Trong đó $Z = \sum_i e^{-\beta E_i}$ là **tổng thống kê**9.
    
5. Liên hệ với năng lượng tự do Helmholtz ($F$): Từ định nghĩa entropy Gibbs $S = -k_B \sum p_i \ln p_i$10, thay $p_i$ vào ta có:    $$S = -k_B \sum p_i (-\beta E_i - \ln Z) = \frac{\langle E \rangle}{T} + k_B \ln Z = \frac{U}{T} + k_B \ln Z$$$$\Rightarrow TS = U + k_B T \ln Z \Rightarrow -k_B T \ln Z = U - TS$$Theo nhiệt động lực học, $F = U - TS$1111, từ đó suy ra biểu thức cần chứng minh:
    
    $$F = -k_B T \ln Z$$
    ### b) Đối với tập hợp chính tắc lớn
1. **Thiết lập hệ:** Xét một hệ mở $S$ có thể trao đổi cả năng lượng và số hạt với bình nhiệt $R$ ở nhiệt độ $T$ và thế hóa học $\mu$.
    
2. Xác suất trạng thái lớn: Sử dụng lập luận tương tự như tập hợp chính tắc nhưng bổ sung thêm sự thay đổi số hạt $N$, xác suất hệ ở trạng thái vi mô $i$ có năng lượng $E_i$ và số hạt $N_i$ là:$$p_i = \frac{e^{-\beta(E_i - \mu N_i)}}{\mathcal{Z}}$$
3. Tổng thống kê lớn: Đại lượng chuẩn hóa $\mathcal{Z}$ được gọi là tổng thống kê lớn:
    $$\mathcal{Z} = \sum_i e^{-\beta(E_i - \mu N_i)}$$
4. Liên hệ với thế nhiệt động lớn ($\Omega_{pot}$): Sử dụng định nghĩa entropy và các quan hệ nhiệt động lực học cho hệ mở :    $$S = \frac{E - \Omega_{pot}}{T} \text{ (với } E \text{ là nội năng } U\text{)}$$
5. Từ cấu trúc toán học của $\mathcal{Z}$, ta có mối liên hệ trực tiếp với thế nhiệt động $\Omega_{pot}$ (còn gọi là thế Landau)20:
    
    $$\Omega_{pot} = -k_B T \ln \mathcal{Z}$$
Biểu thức này cũng tương đương với $F - \mu N$ trong các biến đổi nhiệt động.
## Câu 3
### a) Trong tập hợp vi chính tắc

1. **Hamiltonian:** Hệ có dạng $\mathcal{H} = \sum_{i=1}^N \sum_{j=1}^K \left( \frac{p_{ij}^2}{2m} + \frac{1}{2}m\omega^2 q_{ij}^2 \right)$.
2. Tổng số trạng thái vi mô $\Omega$: Sử dụng phép biến đổi chính tắc để chuyển vùng năng lượng thành hình cầu $2KN$ chiều có bán kính $R = \sqrt{2E/\omega}$. Thể tích hình cầu này trong không gian pha là $v(E) = \frac{\pi^{KN}}{(KN)!} R^{2KN}$.$$\Omega \approx \frac{v(E)}{h^{KN}} = \left( \frac{2 \pi E}{h \omega} \right)^{KN} \frac{1}{(KN)!}$$
3. Entropy: Sử dụng xấp xỉ Stirling $\ln(KN)! \approx KN \ln(KN) - KN$, ta có:$$S = k_B \ln \Omega = KN k_B \left[ 1 + \ln \left( \frac{E}{KN \hbar \omega} \right) \right] $$
### b) Trong tập hợp chính tắc

1. Tổng thống kê: Tổng thống kê của một dao động tử đơn lẻ trong 1 chiều là $Z_1 = \frac{k_B T}{\hbar \omega}$. Vì $N$ hạt là phân biệt và dao động trong $K$ chiều, tổng thống kê của toàn hệ là:$$Z = (Z_1)^{KN} = \left( \frac{k_B T}{\hbar \omega} \right)^{KN} $$
2. Nội năng trung bình $U$:$$U = -\frac{\partial \ln Z}{\partial \beta} = KN k_B T$$
3. Áp suất $p$: Vì tổng thống kê $Z$ không phụ thuộc vào thể tích $V$ của hệ:$$p = -\left( \frac{\partial F}{\partial V} \right)_{T,N} = 0$$
4. Entropy $S$:
    $$S = -\left( \frac{\partial F}{\partial T} \right)_{V,N} = KN k_B \left[ 1 + \ln \left( \frac{k_B T}{\hbar \omega} \right) \right] $$