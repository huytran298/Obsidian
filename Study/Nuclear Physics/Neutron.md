## Định nghĩa và tính chất
### Định nghĩa
- Neutron là hạt [[Hạt hạ nguyên tử]], không mang điện tích, nó cùng với proton để tạo ra hạt nhân (cặp này gọi chung là Nucleon).
- Neutron có cấu tạo từ 3 quark (1 quark up, 2 quark down) được liên kết với nhau bởi tương tác mạnh.
- Neutron có khối lượng xấp xỉ $1.675\times 10^{-27}kg = 1.008665u$
- spin : 1/2.
- Thời gian sống khi tự do: $\approx 878 \pm 0.5 \, (s)$ 
### Phân loại 

| Loại      | Năng lượng $eV$   | TOF                   |
| --------- | ----------------- | --------------------- |
| Siêu lạnh | $< 0.00025$       | $8 \ m /s$            |
| Lạnh      | $0.00025 - 0.025$ | $8-2200 m / s$        |
| Nhiệt     | $\approx 0.025$   | $\approx 2200 m /s$   |
| Nhanh     | $> 100keV$        | $1.4\times 10^7 m /s$ |

### Phản ứng 
#### Tán xạ đàn hồi (Elastic Scattering)
Neutron đập vào hạt nhân rồi bị bật ra (tán xạ) mà **không kích thích hạt nhân đích**. chỉ bị đổi hướng và mất năng lượng do để lại động năng (không đủ để kích thích).
$$^1_{0}n + ^A_{Z}X \longrightarrow ^1_{0}n + ^A_{Z}X$$
##### Bảo toàn 

Giả sử neutron bay với năng lượng $E$ và bị tán xạ đàn hồi với hạt nhân đích đứng yên, sau đó hạt nhân bị giật lùi và hạt neutron bị bay ra 1 góc $\theta$
###### Động lượng
$$\overrightarrow{p_{n}} = \overrightarrow{p_{n}}' + \overrightarrow{p_{nu}}$$
Trong đó : 
- $\overrightarrow{p_{n}}$ : Vector động lượng của neutron trước khi phản ứng.
- $\overrightarrow{p_{n}'}$ : Vector động lượng của neutron sau phản ứng.
- $\overrightarrow{p_{nu}}$ : Vector động lượng của hạt nhân bị giật lùi.
Từ công thức trên ta có : 
$$p_{n}^2 = p'^2_{n} + p^2_{nu} + 2\cdot p_{n}' \cdot p_{nu} \cdot \cos(\theta)$$
#### Tán xạ không đàn hồi (Inelastic Scattering)
Giống tán xạ đàn hồi nhưng neutron **kích thích hạt nhân đích** rồi hạt nhân phát ra gamma để trở về trạng thái cơ bản.
$$^1_{0}n + ^A_{Z}X \longrightarrow ^1_{0}n + ^A_{Z}X + \gamma$$
#### Bắt neutron (Capture Neutron)
Khác với 2 phản ứng trên, Neutron bị hạt nhân đích hấp thụ hoàn toàn, tạo hạt nhân con và bị kích thích, sau đó hạt nhân con phát ra gamma để trở về trạng thái cơ bản.
$$^1_{0}n + ^A_{Z}X \longrightarrow ^{A + 1}_{Z}X + \gamma$$
##### Sản phẩm sau phản ứng
Sau khi xảy ra bắt neutron, hạt nhân con trở thành đồng vị của hạt nhân mẹ và lúc này hạt nhân con ***có thể*** trở nên không bền dẫn tới tiếp tục xảy ra phân rã. 
#### Tiết diện phản ứng Neutron (Cross Section)
Tiết diện neutron là xác suất xảy ra phản ứng của neutron với hạt nhân. Với mỗi phản ứng Neutron, xác suất xảy ra từng phản ứng là *tiết diện phản ứng neutron*. 

Kí hiệu : $\sigma(E)$.
Đơn vị : barn ($1\, b = 10^{-28}\, m^2$)
Trong đó :
- $E$ : Là động năng của Neutron.

Vì tiết diện phản ứng phụ thuộc theo từng loại phản ứng của Neutron, vậy nên tiết diện phản ứng tổng là tổng các tiết diện của các phản ứng Neutron, ta có : 
$$\sigma_{S} = \sigma_{el} + \sigma_{inel} + \sigma_{c}$$
Trong đó :
- $\sigma_s$ : Tiết diện phản ứng tổng.
- $\sigma_{el}$ : Tiết diện phản ứng tán xạ đàn hồi.
- $\sigma_{inel}$ : Tiết diện phản ứng tán xạ không đàn hồi.
- $\sigma_{c}$ : Tiết diện phản ứng bắt neutron.

Theo đó, tiết diện phản ứng Neutron phụ thuộc vào :
- Hạt nhân đích.
- Loại phản ứng.
- Năng lượng của hạt tới.

## Nguồn phát Neutron
### Nguồn phóng xạ
#### Phản ứng $(\alpha, n)$
Sử dụng nguồn phóng xạ phát alpha và gây gián tiếp tạo phản ứng $(\alpha, n)$.
$$\begin{gather}
^{241}Am \longrightarrow ^{237}Np + \alpha \\
\alpha + ^9Be \longrightarrow ^{12}C + n
\end{gather}$$
#### Tự phân hạch (Spontaneous fission - SF)
Chỉ xảy ra với nguyên tố siêu nặng *(Superheavy elements)* bị phân hạch thành 2 mảnh hạt nhân nhẹ hơn, khác với phân hạch cảm ứng *(Induced fission)*, hạt nhân đích không cần bị kích thích để gây phân rã, quá trình tự phân hạch này là quá trình phụ thuộc vào xác suất. 
$$^{238}U \longrightarrow ^{140}Xe + ^{96}Sr + 2 \ ^1n$$ 
### Nguồn gia tốc (Accelerator-based)
#### Phản ứng $D-D\ / \ D-T$
Dòng ion Deuterium (D) va chạm với Deuterium hoặc Tritium (T) ở nhiệt độ cao : 
$$\begin{gather}
^2H + ^2H \longrightarrow \ ^3He + n & (2.45 \ MeV)\\ 
^2H + ^3H \longrightarrow \ ^4He + n & (14.1 \ MeV)
\end{gather}$$
### Nguồn spallation 
Sử dụng proton gia tốc cao $(100s \ MeV - GeV)$ bắn vào nguyên tử nặng (W, Ta) phát ra neutron.
### Nhược điểm 
- Chi phí cao
- Công nghệ phức tạp

## Lò phản ứng hạt nhân 
***bài viết sẽ không nói chi tiết về lò phản ứng hạt nhân mà chỉ nói về vai trò của Neutron trong các phản ứng của lò***
### Nguồn phát Neutron
Về nguồn phát trong lò đa số các lò thương mại thường sử dụng phương pháp $(\alpha, n)$ với hỗn hợp $Am-Be$ hoặc sử dụng nguồn tự phân hạch như Cf-252 nhằm đảm bảo tạo phân hạch *“khởi xướng”* các vụ phân hạch đầu tiên, tạo chuỗi dây chuyền phân hạch. 
Với sử dụng nguồn gia tốc *(Accelerator-Driven System - ADS)* chỉ được dùng cho nghiên cứu, không thể duy trì phản ứng dây truyền.
### Chất làm chậm (Moderator)
Sau khi bắt đầu chuỗi dây chuyền phản ứng phân hạch, việc tạo ra neutron từ phân hạch đó hầu hết là neutron nhanh $(1-2\ MeV)$, việc để neutron này phản ứng tiếp với hạt nhân khác để gây phân hạch là khó vì tiết diện bắt neutron *(cross section)* của hạt nhân tiếp theo *(thường là U-235, Pu-239)* tương đối nhỏ. Nên việc sử dụng chất làm chậm khiến các neutron va chạm đàn hồi, mất dần năng lượng của neutron nhanh *(fast neutron)* xuống neutron nhiệt *(thermal neutron)* để tăng tiết diện.
#### Cơ chế giảm tốc
- Neutron va chạm đàn hồi với hạt nhân của chất làm chậm.
- Trong va chạm đàn hồi, một phần năng lượng của neutron được chuyển sang hạt nhân mục tiêu.
- Hạt nhân nhẹ *(Số khối A nhỏ)*, neutron càng mất nhiều năng lượng trong mỗi va chạm.
#### Các chất làm chậm
- Nước thường $(H_2O)$.
- Nước nặng $(D_{2}O)$.
- Graphit 
- Berylium

#### Chất làm chậm xuất hiện trong lò nhiệt *(Thermal reactor)* : 
- Lò nước áp suất *(PWR/BWR)* : Dùng nước thường $H_2O$ làm moderator và chất làm mát. 
- Lò nước nặng *(Canada Deuterium Uranium - CANDU)* : Dùng nước nặng để làm chậm, cho phép dùng U-235.
- Lò graphite (RBMK, Magnox): Dùng graphit, áp dụng ở Liên Xô cũ và Anh.


## Dò Neutron
Khác với các loại phóng xạ như [[Alpha|alpha]], beta, gamma $(\alpha, \ \beta, \ \gamma)$ , neutron hầu như chỉ tương tác với hạt nhân, hiếm khi tương tác với electron trên lớp vỏ nguyên tử *(xem bài chứng minh [[Bảo toàn năng lượng trong va chạm giữa Electron và Neutron|ở đây]])*. 
### Bộ đếm khí (Gas-filled Counter)
Dùng các khí có tiết diện bắt *(cross section)* neutron cao, tạo ra sản phẩm là các hạt tích điện. 
- He-3 Counter : 
$$^3He + \ ^1n \longrightarrow \ ^3He + \ ^1p $$
	- Triton và proton sinh ra gây ion hóa khí trong ống, dòng ion được khuếch đại (đếm xung)
- $BF_{3}$ Counter : 
$$^{10}B \ + \ ^1n \longrightarrow \ ^7Li + \ ^4\alpha + \ ^0\gamma$$
Ưu điểm : bộ đếm này là nhạy với neutron nhiệt.
### Phát hiện qua tán xạ đàn hồi (Elastic recoil detectors)
Phương pháp đo này chủ yếu được dùng đo neutron nhanh.
### Cơ chế
#### Tán xạ đàn hồi neutron - proton
- Neutron nhanh va chạm đàn hồi với hạt nhân hydro trong vật liệu có tỉ trọng H cao.
- Proton mang động năng của neutron.
#### Chuyển động và phát quang 
- Proton va chạm với scintillator, gây kích thích electron, tạo hiệu ứng quang - electron.
### Vật liệu Scintillator 

| Loại                                        | Ví dụ                     | Ưu điểm                                                                | Nhược điểm                         |
| ------------------------------------------- | ------------------------- | ---------------------------------------------------------------------- | ---------------------------------- |
| Scintillator hữu cơ rắn (plastic)           | EJ-200, Polyvinyltoluene  | Cứng, dễ gia công, bền cơ học                                          | Độ phân giải năng lượng trung bình |
| Scintillator hữu cơ lỏng (plastic)          | EJ-301 (trước là NE-213)  | Phân biệt neutron/γ tốt (PSD), độ phân giải hơi tốt                    | Độc hại, cần bình chịu hóa chất    |
| Tinh thể hữu cơ (stilbene)                  | Stilbene tổng hợp, C₁₄H₁₂ | Độ phân giải năng lượng và PSD tốt nhất                                | Giá cao, kích thước hạn chế        |
| Scintillator gốc ⁶Li (doped plastics, CLYC) | CLYC (Cs₂LiYCl₆:Ce)       | Khả năng phát hiện neutron nhiệt lẫn nhanh, giải phân $\gamma/\nu$ cao | Giá cao, phức tạp hóa học          |
