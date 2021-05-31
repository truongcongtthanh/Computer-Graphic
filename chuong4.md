# Chương 4: sử lý sự kiện
### 1. Sự kiện bấm phím
![](https://i.imgur.com/pVniCwi.png)
- phím bấm thông thường
- ![](https://i.imgur.com/BCN17qp.png)
- phím bấm đặc biệt

### 2. Sự kiện bấm chuột
![](https://i.imgur.com/j0bvDjC.png)
- void myMouse: hàm call back
- glutMouse: Đăng ký sự kiện bấm chuột
- (GLUT_UP, GLUT_DOWN): 1 cái click (ấn và nhã)
- ![](https://i.imgur.com/905mwll.png)
- Chuyển đổi giữa 2 hệ toạ độ
- ![](https://i.imgur.com/gwH6Blz.png)
- thiết đặt sự kiện bấm chuột
- ![](https://i.imgur.com/xD7YHnN.png)
- sự kiện di chuyển chuột và nhấn giữ chuột
- ![](https://i.imgur.com/c87Jytv.png)
- sự kiện di chuyển chuột k cần bấm (tự vẽ)

### 3. Sự kiện thay đổi kích thước màn hình
![](https://i.imgur.com/mr7o7FB.png)
- trường hợp 3: chưa qua xử lý
- ![](https://i.imgur.com/aVBXfRa.png)
- gọi hàm xử lý sự kiện thay đổi kích thước màn hình
- ![](https://i.imgur.com/dGnkaTC.png)
- xử lý trường hợp 2
- ![](https://i.imgur.com/y0bKtY4.png)
- ![](https://i.imgur.com/HPKo84c.png)
- xử lý trường hợp 1
### 4. Sự kiện nhàn rỗi:glutIdleFunc(callback) - dùng trong làm phim hoạt hình
![](https://i.imgur.com/on13PSt.png)
- tăng góc hình cầu 
- ![](https://i.imgur.com/T7A7VSG.png)
- khi không làm gì, hình cầu sẽ xoay

### 5. Bộ đệm Double - dùng trong làm phim hoạt hình
![](https://i.imgur.com/gMSrom4.png)
- glutSwapBuffers(): đổi vị trí 2 bộ bệm phía trước và phía sau cho nhau
- Mục đích: khi vẽ hình phức tạp ta sẽ vẽ bộ đệm phía sau trước, vẽ xong mới chuyển lên phía trước

### 6. Tạo giao diện
![](https://i.imgur.com/99XbkRy.png)
- tạo menu:
    - 1. Menu thường trực (thấy được)
    - 2. Menu pop-up (bấm phải chuột mới thấy)
![](https://i.imgur.com/7Clx19K.png)
- glutAttachMenu(GLUT_RIGHT_BUTTON): bấm phải chuốt sẽ hiện menu
- ![](https://i.imgur.com/Tu0AXNc.png)
- hàm callback
- s