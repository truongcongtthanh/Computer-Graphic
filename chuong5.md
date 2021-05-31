# Chương 5: Vector
### 1. Định nghĩa
![](https://i.imgur.com/QTu1buh.png)
- Đại lương vector là đại lượng có hướng đặc trưng bởi 2 thứ
    - Hướng
    - Độ lớn
### 2. Phép toán vector
- ![](https://i.imgur.com/7yMG1kZ.png)
- AB=(Bx-Ax,By-Ay)
- ![](https://i.imgur.com/B3WQ4FB.png)
- phép cộng vector
- ![](https://i.imgur.com/JVsxKQ8.png)
- Độ lớn vector và vector đơn vị
- ![](https://i.imgur.com/6QeRLgV.png)
- Tích vô hướng -> trả về giá trị vô hướng

### 3. Ứng dụng
![](https://i.imgur.com/AplVTID.png)
- tính góc giữa 2 vector (cos(a,b)=Ua dot (tích vô hướng) Ub)
- ![](https://i.imgur.com/A5iGQgJ.png)
- Xác định có vẽ mặt khuất hay không
    - xác định pháp tuyến các mặt
    - góc giữa pháp tuyển và camera <= 0 -> mặt nhìn thấy
    - >0 không nhìn thấy
- ![](https://i.imgur.com/MAlNHKw.png)
- vector vuông góc (perp)
![](https://i.imgur.com/y90o1X9.png)
- cho vector v, c -> tìm CH
- AH = K.v
- CH = M.v(perp)
- => c = AH + CH = K.v + M.v (tìm K,M)
- ![](https://i.imgur.com/I1BcbiM.png)

![](https://i.imgur.com/GQbDJSU.png)
- Cách 2: Dùng tích vô hướng
![](https://i.imgur.com/zQaB5ys.png)
- tính góc phản xạ

### 4.Tích có hướng giữa 2 vector -> trả về 1 vector
![](https://i.imgur.com/LwbmrHR.png)
- chỉ dùng cho 3 chiều
- |axb| = |a||b|sin(a,b)
- hướng axb -> quy tắc nắm tay phải

### 5. Biểu diễn hình
![](https://i.imgur.com/dpvzIS5.png)
- tham số hoá đường thẳng AB theo t[0,1]
    - t = 0 -> Điểm A
    - t = 1 -> điểm B
    - 0< t <1 -> các điểm giữa A và B
- ![](https://i.imgur.com/mGQIVuW.png)
- tham số hoá elipse
- ![](https://i.imgur.com/iF1gqpX.png)
- vẽ đường cong
- ![](https://i.imgur.com/k7VzHTO.png)
- superelipse
- ![](https://i.imgur.com/80uTkZ3.png)
- superhyperbo
![](https://i.imgur.com/eHEiRgu.png)
- 3 chiều
### 6. Biểu diễn đường thẳng
![](https://i.imgur.com/7byCGHw.png)
![](https://i.imgur.com/d1vVfQX.png)
- biểu diễn tham số cho đường thẳng
- ![](https://i.imgur.com/zawY6Dc.png)
- biểu diễn = vector

### 7. Biểu diễn mặt phẳng
- ![](https://i.imgur.com/53zZpU1.png)
![](https://i.imgur.com/LMdtKGq.png)
- tìm giao điểm giữa 2 đoạn thẳng 
- khác 0: t và u thuộc [0,1] thì 2 đoạn thẳng cắt nhau
- bằng =0: song song nhau hoặc trùng nhau
- ![](https://i.imgur.com/43oKIRM.png)
- L(t): đường trung trực của AB
- ![](https://i.imgur.com/krvXHsX.png)
- vẽ đường tròn ngoại tiếp tam giác
### 8. Biểu diễn vector
![](https://i.imgur.com/qTWDvVQ.png)
- Biểu diễn vector (2,1,0)
- Biểu diễn điểm (2,1,1)
- ![](https://i.imgur.com/UoZIPeL.png)
- Mối tương quan giữa 2 hệ trục toạ độ
- ![](https://i.imgur.com/y5s8mgS.png)
- cho 2 hệ trục u, v. Biểu diễn u theo v 
- ![](https://i.imgur.com/zBbm2Mc.png)

#### Ví dụ:
![](https://i.imgur.com/ELDbcnX.png)
- Cho 2 hệ trục v (hệ 1), u (hệ 2).
- w được biểu diễn ở hệ 1 là (1,1). Chuyển w sang hệ 2 
- Nghĩa là toạ độ vector w trong u là = [1/3;1/2] của v
- ![](https://i.imgur.com/pPqzFQQ.png)
### 9. Biểu diễn điểm giữa 2 trục toạ độ
![](https://i.imgur.com/hDynbF1.png)
