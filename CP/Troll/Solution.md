gọi $maxRect[i][j]$ là tổng hình vuông $k\times k$ lớn nhất khi duyệt từ $(1, 1) \to (i,j)$.

sử dụng kỹ thuật cửa sổ trượt :
gọi $(i, j) : (1, 1) \to (n -k, n - k)$
với mỗi $(i, j)$ gọi $sum$ là tổng từ $(i, j) \to (i + k, j + k)$
cập nhật $maxRect[i][j]$ :
$$maxRect[i][j] = 
\begin{cases}
  max(sum, maxRect[i][j - k], maxRect[i - k, n - k]) & \text{if : } i > k \\
max(sum, maxRect[i][j - k]) & \text{if : } i \leq k \\
max(sum, maxRect[n - k][j]) & \text{if : } j \leq k \\
sum & \text{if : } j \leq k \cup i \leq k
\end{cases}$$
Gọi $ans$ là đáp án bài :
$$ans = max(ans, sum + maxRect[i][j - k])$$