***BÀI VIẾT CHỨNG MINH VỀ TƯƠNG TÁC CỦA NEUTRON VÀ ELECTRON TRÊN PHƯƠNG DIỆN TỐI ƯU NHẤT VỀ MẶT NĂNG LƯỢNG***

*Bài toán*

---
Giả sử neutron di chuyển với khối lượng được xác định là $m_n = 939.57 \ (MeV/c^2)$ va chạm với electron đứng yên có khối lượng là $m_{e} = 0.511 (MeV/c^2)$. Chỉ xét va chạm thẳng, đàn hồi.

---
## Bài giải : 
#### Trước va chạm
Động năng của neutron : 
$$E_{n} = \frac{1}{2}m_{n}v_{n}^2$$
Vì electron đứng yên : 
$$E_{e} = 0$$
#### Sau va chạm : 
Giả sử :
Neutron bị va chạm và di chuyển với vận tốc $v_{n}’$.
Electon sau va chạm bị bật ra với vận tốc $v_{e}'$.

Xét bảo toàn động lượng : 
$$\begin{gather} 
m_{n}v_{n} = m_{n}v_{n}' + m_{e}v_{e}' \\
v'_{n} = \frac{m_{n}v_{n} - m_{e}v_{e}'}{m_{n}} & (*)
\end{gather}$$
Đồng thời cũng có bảo toàn năng lượng :
$$\begin{gather}
\frac{1}{2}m_{n}v_{n}^2 = \frac{1}{2}m_{n}v_{n}'^2 + \frac{1}{2}m_{e}v_{e}'^2 \\
m_{n}v_{n}^2 = m_{n}v_{n}'^2 + m_{e}v_{e}'^2 
\end{gather}$$
Thay $(*)$ vào phương trình ta có :
$$\begin{gather}
m_{n}v_{n}^2 = m_{n}\left( \frac{m_{n}v_{n} - m_{e}v_{e}'}{m_{n}} \right)^2 + m_{e}v_{e}'^2 \\
m_{n}v_{n}^2 =  \frac{\left(m_{n}v_{n} - m_{e}v_{e}'\right)^2}{m_{n}}  + m_{e}v_{e}'^2 \\
m_{n}v_{n}^2 =  \frac{(m_{n}v_{n})^2 -2\cdot m_{n}m_{e} \cdot v_{n}v_{e}' + (m_{e}v_{e}')^2}{m_{n}} + m_{e}v_{e}'^2 \\
m_{n}v_{n}^2 = m_{n}v_{n}^2 - 2 \cdot m_{e} \cdot v_{n}v_{e}' + \frac{(m_{e}v_{e}')^2}{m_{n}} + m_e v_{e}'^2 \\
2 \cdot m_{e} \cdot v_{e}'v_{n} = \frac{(m_{e}v_{e}')^2}{m_{n}} + m_e v_{e}'^2 \\
 2  \cdot v_{n} = v'_{e}\cdot \left( \frac{m_{e}}{m_{n}} +1 \right)  \\
v_{e}' = \frac{2 \cdot v_{n}}{\left( \frac{m_{e}}{m_{n}} + 1 \right)} =  \left( \frac{2\cdot v_{n} m_{n}}{m_{e} + m_{n}} \right)& (**)
\end{gather}$$
Xét năng lượng của electron sau va chạm 
$$\begin{gather}
E_{e} = \frac{1}{2} m_{e}v_{e}'^2 = \frac{1}{2}m_{e} \frac{4\cdot (v_{n} m_{n})^2}{(m_{e} + m_{n})^2}  \\
= \underbrace{\frac{1}{2}m_{n}v_{n}^2}_{E_{n}}\cdot  \frac{4 \cdot m_{e}m_{n}}{(m_{e} + m_{n})^2} = \frac{4 \cdot m_{e}m_{n}}{(m_{e} + m_{n})^2}E_{n}
\end{gather}$$
Thay các dữ kiện đã có : 
$$\begin{gather}
E_{e} = \frac{4 \cdot 0.511 \cdot 939.57}{(0.511 + 939.57)^2} \cdot E_{n} = 2.173\times 10^{-3} \cdot E_{n}
\end{gather}$$
Lúc này xét : 
- Neutron nhiệt $(E_{n} \approx 0.025 \ eV)$ : $E_{e} = 5.43\times 10^{-5} \ (eV)$ 
- Neutron nhanh $(E_{n} \approx 1MeV)$ : $E_{e} = 2 \ (KeV)$

---
## Kết luận 
Cho thấy rằng, chỉ có neutron nhanh mới có khả năng bức electron ra khỏi lớp vỏ nguyên tử. Tuy nhiên, bài chứng minh trên chỉ nói về mặt tối ưu về năng lượng, tức là tán xạ mà ở đó góc tán xạ $\theta = \pi$ *(năng lượng truyền hoàn toàn vào electron)*. Trên thực tế xác suất để neutron va chạm electron là rất thấp nên cũng có thể nói việc tương tác giữa 2 hạt này là hiếm và gần như không có. 



