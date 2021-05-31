# Chương 7: GÓC NHÌN

## 1. Phép chiếu
- Chụp ảnh: thực chất là ánh xá không gian 3D sang 2D
![](https://i.imgur.com/y4ZI3dO.png)
- Các loại phép chiếu
![](https://i.imgur.com/qy44Adi.png)

### 1.1 Phép chiếu song song 
- Phép chiếu trục giao: các tia chiếu vuông góc mặt phẳng chiếu
- Phép chiếu xiên: không vuông góc
![](https://i.imgur.com/12u0rS2.png)

#### 1.1.1 Phép chiếu nhiều hình chiếu (Trực giao)
![](https://i.imgur.com/EBpmDeu.png)

#### 1.1.2 Phép chiếu xiên
![](https://i.imgur.com/epxaUbW.png)


### 1.2 Phép chiếu khối cạnh (chân thực với con người)
![](https://i.imgur.com/K179tp8.png)
- Các tia chiếu hội tụ tại 1 điểm gọi là tâm của phép chiếu
- Có 3 dạng: 1 điểm biến mất, 2 ĐBM, 3 ĐBM

#### 1.2.1 1 điểm biến mất
![](https://i.imgur.com/FEYulkW.png)
![](https://i.imgur.com/FFSgINj.png)
![](https://i.imgur.com/E8bLuYu.png)
- Vẽ tranh bằng phép chiếu xiên 1 ĐBM

#### 1.2.2 2DBM
![](https://i.imgur.com/jHnql3U.png)

#### 1.2.3 3DBM
![](https://i.imgur.com/9cvZgW7.png)

### 2. Thiết lập camera
![](https://i.imgur.com/1ea2ApY.png)
- v1v2 là lưới đa giác (ma trận điểm)
- VM (VIEWMODEL): khi đưa vào thì đưa VIEW.dot(MODEL) - xuất hiện trước thì đưa sau
    - VIEW: matrix camera
    - MODEL: matrix vật thể

![](https://i.imgur.com/Gkskoww.png)
- vector (up.x,up.y,up.z): cho biết góc xoay camera

![](https://i.imgur.com/bLHmDvV.png)
- Camera đặt tại 0,0,10 nhìn vào điểm 0,0,0 góc xoáy 0,1,0 (bình thường: chưa bị xoay)

![](https://i.imgur.com/14gcBAv.png)
- Hình ảnh bị mất do nhìn vào 0,1,0

![](https://i.imgur.com/YA8qJOs.png)
- Xoay camera theo vector 2,1,0

![](https://i.imgur.com/TSWsDvg.png)
- Từng bước biến đổi từ hệ vật sang hệ camera

![](https://i.imgur.com/0ltgmiv.png)
- Biến đổi trong hình chiếu trực giao

![](https://i.imgur.com/hGCpaop.png)
![](https://i.imgur.com/H6lpSg5.png)
- Ánh xạ từ Vật sang hệ thế giới

![](https://i.imgur.com/VDVRRFh.png)
![](https://i.imgur.com/GT2OwBc.png)
![](https://i.imgur.com/whKNY3K.png)
- biến đổi từ hệ thế giới sang hệ camera

![](https://i.imgur.com/7UpT3e6.png)
- Cắt xén

![](https://i.imgur.com/xoGmItv.png)
- Chia tỉ lệ
##### Thiết lập P cho phép chiếu trực giao
![](https://i.imgur.com/deSWPOZ.png)
![](https://i.imgur.com/L9OK1of.png)
- Thiết lập P theo hệ camera dùng hàm GlOrtho

![](https://i.imgur.com/VNJ75qy.png)
![](https://i.imgur.com/aA12bM6.png)
![](https://i.imgur.com/LF1hmjJ.png)
- Thiết lập P bằng tay

![](https://i.imgur.com/7RsYjNA.png)
- Mô tả khác của cách thiết lập P bằng tay

##### Thiết lập P cho phép chiếu phối cảnh
![](https://i.imgur.com/LLUlcuQ.png)
- dùng hàm glFrustum(left,right,bottom,top,near,far)

![](https://i.imgur.com/9d8v8dx.png)
- Dùng hàm gluPerpective(fovy,aspect,near,far)

![](https://i.imgur.com/FAtnWJ0.png)
- Thiết lập bằng tay

##### Thiết lập P cho phép chiếu xiên
![](https://i.imgur.com/Q3kQUdz.png)
- Đói với phép chiếu xiên phải chuẩn hoá trước

![](https://i.imgur.com/EANqq31.png)
- Góc nhìn phi, theta khi chiếu xiên

![](https://i.imgur.com/OiOqLnD.png)
- Phép trượt xong nhân với 8 đỉnh để biến hình hộp xiên thành hình hộp đứng