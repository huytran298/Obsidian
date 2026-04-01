# Trần Quốc Huy
# MSSV : 23230005
## Câu 1
### Đẳng tích : ($\frac{P}{T} = const$)
- Công thức nội năng đối với khí lý tưởng : 
$$U = \frac{m}{\mu} \frac{iN_{A}k_{B}}{2}T$$
Vì $N_{A}k_{B} = R$ 
$$\implies U = \frac{m}{\mu} \frac{iR}{2}T = n C_{v}T$$
Vì nội năng chỉ phụ thuộc vào nhiệt độ, nên biến thiên nội năng của đẳng tích chỉ còn sự thay đổi của nhiệt độ. Từ đó độ biến thiên nội năng của một khối khí thay đổi từ $T_{1}$ đến $T_{2}$ là :
$$\Delta U_{12} = nC_{v}T_{1} - nC_{v}T_{2} = nC_{v}\Delta T$$
- Công của hệ : 
Công của khí lý tưởng là công mà khối khí đó thực hiện khi dãn nở hoặc bị nén được tính theo công thức :
$$A = \int^{V_{2}}_{V_{1}} PdV$$
vì là quá trình đẳng tích $V_{1} = V_{2}$ là :
- Nhiệt lượng của hệ :
Từ nguyên lý I nhiệt động lực học :
$$\begin{gather}
\Delta U_{12} = A_{12} + Q_{12} \\
Q_{12} = -A_{12} + \Delta U_{12}
\end{gather}$$
Vì đẳng tích nên công của hệ $A_{12} = 0$. Từ đó :
$$Q_{12} = \Delta U_{12}$$

$$A = 0$$
- Entropy trong quá trình đẳng tích :
$$\Delta S = \int^{T_{2}}_{T_{1}} \frac{dQ}{T} \implies \Delta S = \int^{T_{2}}_{T_{1}} \frac{nC_{v}}{T} dT= nC_{v}\ln\left( \frac{T_{2}}{T_{1}} \right)$$
### Đẳng áp : ($\frac{V}{T} = const$)
- Công thức biến thiên nội năng : 
$$\Delta U= nC_{v}\Delta T$$
- Công của hệ : 
Từ định nghĩa của công ta có công thức :
$$A = \int^{V_{2}}_{V_{1}} PdV$$
Vì quá trình là đẳng áp nên $P_{1}=P_{2} = P =const$:
$$A = \int^{V_{2}}_{V_{1}} PdV = P(V_{2} - V_{1})$$

- Nhiệt của hệ : 
Nguyên lý I nhiệt động lực học : 
$$Q_{12} = \Delta U + A = nC_{v}\Delta T + P(V_{2} - V_{1})$$
Từ phương trình trạng thái khí lý tưởng :
Tại trạng thái 1 và 2: 
$$\begin{cases}
PV_{1} = nRT_{1} \\
PV_{2} = nRT_{2}
\end{cases} 
\implies PV_{2} - PV_{1} = nR(T_{2}-T_{1}) = P(V_{2}-V_{1})$$
Thay $A=P(V_{2}-V_{1})$ và $\Delta T = T_{2}-T_{1}$ :
$$nR\Delta T = A$$
Thay vào biểu thức nhiệt lượng : 
$$Q_{12} = nC_{v}\Delta T + nR\Delta T = n\Delta T (C_{v}+R) = nC_{p}\Delta T$$
- Entropy trong quá trình đẳng áp : 
$$\Delta S = \int^{T_{2}}_{T_{1}} \frac{dQ}{T} \implies \Delta S = \int^{T_{2}}_{T_{1}} \frac{nC_{p}}{T}dT = nC_{p}\ln\left( \frac{T_{2}}{T_{1}} \right)$$
### Đẳng nhiệt : ($PV = const$)
- Độ biến thiên nội năng : 
$$\Delta U = nC_{v}\Delta T$$
Vì quá trình là đẳng nhiệt nên : 
$$\Delta U = 0$$
- Công mà hệ nhận vào 
$$\begin{gather}
A = \int^{V_{2}}_{V_{1}} PdV = \frac{nRT}{V}dV
\end{gather}$$
vì quá trình là đẳng nhiệt nên : 
$$\begin{gather}
A =  nRT\int^{V_{2}}_{V_{1}} \frac{1}{V}dV = nRT \ln\left( \frac{V_{2}}{V_{1}} \right)
\end{gather}$$
- Nhiệt lượng của hệ : 
$$Q = \Delta U - A = 0 - A=-nRT\ln\left( \frac{V_{2}}{V_{1}} \right)$$
- Entropy trong quá trình đẳng nhiệt :
$$\begin{gather}
\Delta S = \int \frac{dQ}{T} = \frac{1}{T}\int dQ = \frac{Q}{T} \\
\Delta S = \frac{nRT\ln\left( \frac{V_{2}}{V_{1}} \right)}{T} = nR\ln\left( \frac{V_{2}}{V_{1}} \right)
\end{gather}$$
### Đoạn nhiệt : ($PV^\gamma = const$)
- Công thức biến thiên nội năng : 
$$\Delta U= nC_{v}\Delta T$$
- Quá trình đoạn nhiệt không trao đổi nhiệt với bên ngoài nên nhiệt lượng là : 
$$Q = 0$$
- Công của hệ : 
$$\Delta U = Q + A = 0 + A = A$$
$$A = nC_{v}\Delta T$$
- Vì nhiệt lượng bằng không nên entropy cũng bằng không : 
$$\Delta S = \int \frac{dQ}{T} = 0$$
## Câu 2
- $C_{v} = \frac{dU}{dT} =\frac{d}{dT}(\alpha V^3T^{2/3}) = \frac{2}{3}\alpha V^3T^{-1/3}$
-  $S = -2\alpha V^3T^{-1/3}$
- $F = 3\alpha V^3T^{2/3}$
- $P = -9\alpha V^2T^{2/3}$
- $\Phi = -6\alpha V^3T^{2/3}$
- $W = -8\alpha V^3T^{2/3}$
### Câu 3
#### Nội năng : 
- **Hóa học (Nhiệt hóa học):** Tính nhiệt lượng của một phản ứng xảy ra trong **bình kín, thể tích không đổi** (gọi là "bomb calorimeter"). Trong điều kiện này ($V$=const, $W=0$), toàn bộ nhiệt tỏa ra hoặc thu vào chính là độ biến thiên nội năng ($\Delta U = Q_V$).

- **Kỹ thuật (Động cơ đốt trong):** Phân tích chu trình Otto (động cơ xăng). Quá trình cháy diễn ra rất nhanh được coi là quá trình **đẳng tích** (piston gần như đứng yên). Nhiệt lượng do xăng cháy cung cấp làm tăng nội năng của khí ($\Delta U=Q_V=nC_v\Delta T$), từ đó tăng áp suất đột ngột.
    
- **Vật lý (Khí lý tưởng):** Trong quá trình **giãn nở đoạn nhiệt** (hệ cách nhiệt, $Q=0$), ví dụ như khí nén phun ra khỏi bình. $\Delta U = -W$. Khí thực hiện công ($W>0$) để đẩy môi trường, nên nội năng của nó phải giảm ($\Delta U < 0$), dẫn đến khí bị **lạnh đi** rõ rệt.
#### Thế Helmholtz F
- **Vật lý (Vật lý thống kê):** $F$ là cầu nối cơ bản giữa thế giới vi mô và vĩ mô. Nó liên hệ trực tiếp với hàm tổng trạng thái $Z$ ($F = -kT \ln Z$), cho phép tính toán mọi đại lượng nhiệt động (như $U, S, P$) từ các mức năng lượng của hệ.
    
- **Hóa học (Hóa rắn/lỏng):** Dự đoán chiều phản ứng trong một bình kín ( $V$ = const) được giữ ở nhiệt độ không đổi. Ví dụ, xác định xem một chất rắn có tự phân hủy ở nhiệt độ $T$ trong bình kín hay không.
    
- **Kỹ thuật (Khoa học vật liệu):** Mô hình hóa sự chuyển pha trong vật liệu rắn. Ví dụ, khi làm nguội thép ( $T$ thay đổi, nhưng $V$ gần như không đổi), thế $F$ được dùng để xác định cấu trúc tinh thể (pha) nào (ví dụ: Austenite hay Martensite) là bền vững nhất (có $F$ thấp nhất).
#### Thế Gibbs
- **Hóa học (Cân bằng hóa học):** $\Delta G$ quyết định một phản ứng có tự xảy ra hay không. Tại trạng thái cân bằng, $\Delta G = 0$. Nó liên hệ trực tiếp với hằng số cân bằng $K_{eq}$ qua công thức $\Delta G^\circ = -RT \ln K_{eq}$.
- **Kỹ thuật (Điện hóa):** $\Delta G$ của phản ứng oxy hóa-khử trong pin liên quan trực tiếp đến sức điện động (điện áp $E$) của pin: $\Delta G = -nFE$. Pin chỉ hoạt động (tự phát) khi $\Delta G < 0$, tương ứng $E > 0$.
- **Khoa học vật liệu / Địa chất:** Dùng để vẽ **giản đồ pha** (Phase Diagram). Bằng cách so sánh thế Gibbs của các pha khác nhau (rắn, lỏng, khí, các cấu trúc tinh thể), người ta xác định được pha nào là bền vững nhất (có $G$ thấp nhất) ở một nhiệt độ $T$ và áp suất $P$ cho trước.
#### Thế Grand
1. **Vật lý (Vật lý thống kê):** Dùng trong **tập hợp Grand Canonical** (Tập hợp vĩ chính tắc) để mô tả các hệ trao đổi cả năng lượng và hạt. Rất quan trọng trong cơ học lượng tử thống kê (ví dụ: mô tả khí electron trong kim loại, khí Bose-Einstein ngưng tụ).
2. **Hóa học (Hóa lý):** Mô tả các hiện tượng **hấp phụ** (adsorption), nơi các phân tử khí (môi trường) bám vào một bề mặt vật rắn (hệ). Số lượng phân tử $N$ trên bề mặt thay đổi liên tục cho đến khi đạt cân bằng ($\Omega$ cực tiểu).
3. **Kỹ thuật (Bán dẫn):** Mô hình hóa mật độ các hạt tải điện (electron và lỗ trống) trong một vật liệu bán dẫn. Số lượng hạt $N$ này thay đổi tùy thuộc vào điện áp đặt vào (hiệu ứng trường) hoặc nồng độ tạp chất. Thế Grand được dùng để tính toán các đặc tính điện của vật liệu.
#### Entanpi
- **Hóa học (Toàn bộ Nhiệt hóa học):** Đây là ứng dụng chính. Hầu hết các phản ứng trong phòng thí nghiệm (cốc, ống nghiệm) hoặc tự nhiên đều xảy ra ở áp suất khí quyển ( $P$ = const). Nhiệt lượng tỏa ra (làm nóng cốc) hay thu vào (làm lạnh cốc) chính là $ \Delta H$ của phản ứng.

- **Kỹ thuật (Kỹ thuật hóa học/Năng lượng):** Tính toán năng lượng cho các thiết bị như lò hơi, tháp chưng cất, bộ trao đổi nhiệt. Ví dụ, "Nhiệt hóa hơi" ($\Delta H_{\text{vap}}$) là lượng năng lượng (nhiệt) cần cung cấp để làm bay hơi 1 mol lỏng ở áp suất không đổi.

- **Vật lý (Dòng chảy):** Rất quan trọng trong các hệ thống dòng chảy hở như tua-bin hơi, động cơ phản lực, ống phun. Trong một tua-bin đoạn nhiệt, công kỹ thuật sinh ra bằng đúng độ giảm Entanpi của dòng hơi ($W_{kt} = -\Delta H$).