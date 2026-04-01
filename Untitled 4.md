# Họ và tên : Trần Quốc Huy
# MSSV : 23230005
## Câu 1: Khí lý tưởng lượng tử trong tập hợp chính tắc lớn

### a) Thiết lập Tổng thống kê lớn ($\Xi$) và Entropy ($S$)

Trong tập hợp chính tắc lớn, tổng thống kê lớn được xác định bởi công thức1:

$$\Xi = \sum_{N} \sum_{\{n_k\}} e^{-\beta(E - \mu N)} = \prod_k \Xi_k$$

Với $\beta = 1/(k_B T)$, $\mu$ là thế hóa học, và $\Xi_k$ là tổng thống kê của trạng thái năng lượng $\epsilon_k$.

1. Thống kê Fermi-Dirac (FD): 

- Số hạt trong mỗi trạng thái $n_k$ chỉ có thể là $0$ hoặc $1$ (nguyên lý loại trừ Pauli).
    
- $\Xi_k^{FD} = \sum_{n_k=0}^{1} e^{-\beta(\epsilon_k - \mu)n_k} = 1 + e^{-\beta(\epsilon_k - \mu)}$.
    
- $\ln \Xi_{FD} = \sum_k \ln(1 + e^{-\beta(\epsilon_k - \mu)})$.
    

2. Thống kê Bose-Einstein (BE): 

- Số hạt $n_k$ có thể nhận giá trị bất kỳ từ $0, 1, 2, \dots, \infty$.
    
- $\Xi_k^{BE} = \sum_{n_k=0}^{\infty} (e^{-\beta(\epsilon_k - \mu)})^n = \frac{1}{1 - e^{-\beta(\epsilon_k - \mu)}}$ (với điều kiện $\mu < \epsilon_k$).
    
- $\ln \Xi_{BE} = -\sum_k \ln(1 - e^{-\beta(\epsilon_k - \mu)})$.
    

Biểu thức Entropy ($S$): 

Sử dụng công thức $S = \frac{U - \Omega - \mu N}{T}$ hoặc từ vi phân thế nhiệt động $\Omega = -k_B T \ln \Xi$:

- **FD:** $S = -k_B \sum_k [\bar{n}_k \ln \bar{n}_k + (1 - \bar{n}_k) \ln (1 - \bar{n}_k)]$.
    
- **BE:** $S = -k_B \sum_k [\bar{n}_k \ln \bar{n}_k - (1 + \bar{n}_k) \ln (1 + \bar{n}_k)]$.
    

**Giải thích sự giống và khác nhau:** 

- **Giống nhau:** Cả hai đều phụ thuộc vào nhiệt độ, mức năng lượng và thế hóa học. Ở giới hạn nhiệt độ cao và mật độ thấp, cả hai đều tiến về thống kê cổ điển Maxwell-Boltzmann.
    
- **Khác nhau:** Biểu thức FD có dấu cộng (ngăn cản việc chiếm giữ trạng thái), trong khi BE có dấu trừ (khuyến khích việc chiếm giữ trạng thái).
    
- **Nguyên nhân căn bản:** Do **tính chất đối xứng của hàm sóng** và **Spin** của hạt. Fermion có spin bán nguyên, hàm sóng phản đối xứng; Boson có spin nguyên, hàm sóng đối xứng.
    

---

### b) Số hạt trung bình $\bar{n}_k$

Số hạt trung bình được tính bằng công thức: $\bar{n}_k = -\frac{1}{\beta} \frac{\partial (\ln \Xi_k)}{\partial \epsilon_k}$.

- **Fermi-Dirac:** $\bar{n}_k = \frac{1}{e^{\beta(\epsilon_k - \mu)} + 1}$
    
- **Bose-Einstein:** $\bar{n}_k = \frac{1}{e^{\beta(\epsilon_k - \mu)} - 1}$
    

---

### c) Xác suất $P\{n_k\}$ theo số hạt trung bình $\bar{n}_k$

Xác suất để một trạng thái $k$ có $n_k$ hạt là $P(n_k) = \frac{1}{\Xi_k} e^{-\beta(\epsilon_k - \mu)n_k}$.

- **Với FD:**
    
    - $P(0) = 1 - \bar{n}_k$
        
    - $P(1) = \bar{n}_k$
        
- Với BE:
    
    $P(n_k) = \frac{1}{1+\bar{n}_k} \left( \frac{\bar{n}_k}{1+\bar{n}_k} \right)^{n_k}$ (Đây là phân bố hình học).
    

---

## Câu 2: Phân loại hạt và Ngưng tụ Bose-Einstein

**Bảng phân loại hạt:** 

|**Loại hạt**|**Thống kê**|**Lý do (Spin / Cấu tạo)**|
|---|---|---|
|**Higgs**|Bose-Einstein|Spin 0 (nguyên)|
|**Positron**|Fermi-Dirac|Spin 1/2 (bán nguyên)|
|**Neutrino**|Fermi-Dirac|Spin 1/2 (bán nguyên)|
|**Neutron**|Fermi-Dirac|Spin 1/2 (bán nguyên)|
|**Gluon**|Bose-Einstein|Spin 1 (nguyên)|
|**Pion**|Bose-Einstein|Spin 0 (nguyên)|
|**Quark**|Fermi-Dirac|Spin 1/2 (bán nguyên)|
|**Alpha ($\alpha$)**|Bose-Einstein|2p + 2n (tổng số nucleon chẵn, spin nguyên)|
|**Deuteron**|Bose-Einstein|1p + 1n (tổng số nucleon chẵn, spin nguyên)|
|**$^{13}C$ (hạt nhân)**|Fermi-Dirac|13 nucleon (số khối lẻ, spin bán nguyên)|
|**$^6Li$ (hạt nhân)**|Bose-Einstein|6 nucleon (số khối chẵn, spin nguyên)|

Ngưng tụ Bose-Einstein (BEC): 

Hiện tượng này có thể xảy ra với các hệ hạt tuân theo thống kê Bose-Einstein khi ở nhiệt độ rất thấp. Trong danh sách trên, các hệ như hạt Alpha, Deuteron, Pion, Higgs, Gluon và hạt nhân $^6Li$ (hoặc nguyên tử boson) có thể tham gia vào quá trình ngưng tụ này.

---

## Câu 3: Dẫn ra công thức cường độ bức xạ Planck

Xét khí photon (Boson) với $\mu = 0$:

1. Số hạt trung bình ở tần số $\nu$:
    
    $\bar{n}(\nu) = \frac{1}{e^{h\nu/(k_B T)} - 1}$ 11
    
2. Mật độ trạng thái trong hốc V:
    
    Số trạng thái trong khoảng tần số từ $\nu$ đến $\nu + d\nu$ là:
    
    $g(\nu)d\nu = 2 \times \frac{4\pi \nu^2 V}{c^3} d\nu = \frac{8\pi \nu^2 V}{c^3} d\nu$ (số 2 đại diện cho 2 trạng thái chuẩn trực của ánh sáng).
    
3. Mật độ năng lượng phổ $u(\nu, T)$:
    
    $u_{energy}(\nu, T) d\nu = \frac{1}{V} \bar{n}(\nu) \cdot h\nu \cdot g(\nu) d\nu = \frac{8\pi h \nu^3}{c^3} \frac{1}{e^{h\nu/k_B T} - 1} d\nu$
    
1. Cường độ bức xạ (Spectral Radiance) $u(\nu)$: 
    
    Mối liên hệ giữa cường độ bức xạ phát ra từ một bề mặt và mật độ năng lượng trong hốc là $u(\nu) = \frac{c}{4\pi} u_{energy}(\nu, T)$.
    
    $$u(\nu) = \frac{c}{4\pi} \cdot \frac{8\pi h \nu^3}{c^3} \frac{1}{e^{h\nu/(k_B T)} - 1} = \frac{2h\nu^3}{c^2} \frac{1}{e^{h\nu/(k_B T)} - 1}$$
    
    Đây chính là định luật Planck cần chứng minh.