# Chương 8: TÔ MÀU
## 1. Một số cách vẽ hình
![](https://i.imgur.com/PRk882S.png)
- Vẽ hình bằng các đường

![](https://i.imgur.com/bAz5SKz.png)
- Vẽ hình bằng các đường xoá đi đường bị dấu (không thấy)

![](https://i.imgur.com/gXpggOD.png)
- Vẽ hình bằng tô màu phẳng

![](https://i.imgur.com/9Kzkxd8.png)
- Vẽ hình bằng tô màu vùng trơn (tăng độ chân thực)

![](https://i.imgur.com/Qh3E1Qq.png)
- Kết hợp dán texture
- Một số phần mềm: 3D-SMax, May-a

## 2. Ánh sáng phản xạ
![](https://i.imgur.com/3xOSDZU.png)
- Để to màu một hình cần 2 giai đoạn
    - giai đoạn 1: Tô màu các đỉnh, thiết lập nguồn sáng, màu sắc..
    - Thiết lập kiểu tô: tô màu phẳng / tô màu trơn, các phần còn lại sẽ tự tô bằng phép nội suy
    
![](https://i.imgur.com/o8OAiOo.png)
![](https://i.imgur.com/im4wM2m.png)
- 2 thành phần ánh sáng phản xạ:
    - Khuếch tán: Cho biết màu sắc
    - Phản chiếu: Độ chói, tập trung ở một số khu vực nhất định (tuỳ thuộc mắt nhìn)

#### Tính AS khuếch tán
![](https://i.imgur.com/dwBQtPU.png)
- Công thức tính cường độ ánh sáng khuếch tán

![](https://i.imgur.com/mrFbN17.png)
- Một số giá trị Pd (Độ khuếch tán AS của vật liệu)

#### Tính AS phản chiếu
![](https://i.imgur.com/oiIA2wc.png)

![](https://i.imgur.com/cxXABtl.png)
- Một vài giá trị hằng

## 3. Ánh sáng môi trường
![](https://i.imgur.com/6iaHivm.png)
- Ánh sáng môi trường làm cho ta thấy được mặt khuất

![](https://i.imgur.com/7qqH14s.png)
- Nguyên tắc cộng AS (trên 1 làm tròn = 1 -> có màu trắng)
![](https://i.imgur.com/oJslAr9.png)
- Công thức chung

![](https://i.imgur.com/WvN9p6Q.png)
- Nguồn sáng: glEnable(GL_LIGHTING)
- Hổ trợ 8 nguồn sáng (OPENGL)

![](https://i.imgur.com/vVE6TdT.png)
- tính pháp tuyến bằng glNormal(x,y,z)