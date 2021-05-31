# Đồ hoạ máy tính
# Chương 1:  Định nghĩa
![](https://i.imgur.com/gI21Rm6.png)
- Đồ hoạ máy tính: tạo ra hình ảnh
- Xử lý ảnh: chỉnh sửa ảnh, nâng cao chất lượng ảnh

![](https://i.imgur.com/UnuOo4u.png)
- Ứng dụng: game, phim, xử lý ảnh, tự động hoá, thiết kế, mô phỏng

![](https://i.imgur.com/S9DYwMp.png)
- Dựa trên 4 yếu tố cơ bản:
    - đường gấp khúc
    - văn bản
    - vùng tô
    - ảnh ma trận điểm
### 1.Đường gấp khúc: 

- là các **ĐOẠN THẲNG** được nối với nhau
- drawdot(x,y): vẽ điểm
- drawline(x1,y1,x2,y2): vẽ đoạn thẳng
- drawPolyline(poly): vẽ đường gấp khúc
- ![](https://i.imgur.com/TohnELM.png)
- thiết lập thuộc tính đường gấp khúc:
    - setDash(dash7)
- ![](https://i.imgur.com/dllLfeL.png)
- thiết lập hiển thị chuỗi văn bản:
    - drawString(x,y,string)
- ![](https://i.imgur.com/TlUJ2pb.png)
- Thiết lập vùng tô: fillPolygon(poly, parttern);
- ![](https://i.imgur.com/x7DPKkC.png)
- vùng tô để mô phỏng các mặt khác nhau của vật 
- ![](https://i.imgur.com/E0owTEm.png)
- Ma trận ảnh (ảnh raster): hiển thị ảnh dưới dạng Pixel
- ![](https://i.imgur.com/Cz6doh1.png)
- thiết bị hiển thị đồ hoạ:
    - vector: tạo hình ảnh từ những đoạn thẳng
        - Ưu: nhanh
        - nhược: không tô màu được
    -![](https://i.imgur.com/8uthjmn.png)
    - Thiết bị raster: tạo ảnh từ ma trận điểm
### 2. Thiết bị raster
![](https://i.imgur.com/eA7469L.png)
- Hình ảnh được vẽ trong bộ đệm frame và được hiển thị ra màn hình 
    - Bộ đệm frame: nằm trong RAM
    - Hoặc GPU, Card đồ hoạ
    - TP nhỏ nhất của bộ đềm Frame là pixel
    - Bộ đệm Frame = kích thước màn hình
        - Pixel in Frame: chứa các con số
        - Pixel in Màn hình: chứa các màu 
    - Bộ quét dòng: định hướng đúng vị trí từ Frame sang màn hình
    - Bộ chuyển đổi: chuyển đổi màu sắc từ số sang màu
- Bề mặt hiển thị: trục x,y góc phần tư thứ IV
- ![](https://i.imgur.com/K59TQQO.png)
- Quét dòng
- ![](https://i.imgur.com/3TM2HVW.png)
- Video màu sắc
- ![](https://i.imgur.com/ndLbU2w.png)
- Với thông số này thì chỉ có thể hiển thị được 64 giá trị màu trong (bẳng 2^15 màu)
- ![](https://i.imgur.com/uAG2YUf.png)
- RGB table
- ![](https://i.imgur.com/3Nt8Sqn.png)
- Hệ thông trên chi phi = 4 lần hệ thông LUT
- Nhược của LUT: là 1 bức hình chỉ hiện thị được 256 màu(không ảnh hướng nhiều)
- ![](https://i.imgur.com/5rAIAv4.png)
- Mắt con người kém nhạy cảm với màu Blue
- nên khi Frame = 13 bit(k chia hết 3)thì có thể chia: RGB(5-5-3)

### 3.Tạo đối tượng
- Thông tin hình ảnh có 3 yếu tố:
    - Đối tượng
    - Camera
    - Nguồn sáng