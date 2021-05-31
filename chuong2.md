# Chương 2
### 1
![](https://i.imgur.com/7EooOik.png)
- glutCreateWindow("simple") -> tạo cửa sổ với tên là simple
- glutDisplayFunc(mydisplay) -> chạy hàm mydisplay() và cho hiển thị lên cửa sổ
- glClear(GL_COLOR_BUFFER_BIT) -> xoá màn hình
- glBegin(GL_POLYGON) -> Vẽ hình đa giác
- glEnd() 
- glutMainLoop() -> đặt chương trình vào trong vòng lặp sự kiện

![](https://i.imgur.com/txEGqMa.png)
- hiển thị khung nhìn ở góc phần tư thứ I
![](https://i.imgur.com/uRznrbe.png)
- I và II
![](https://i.imgur.com/VpNYALb.png)
- góc nhìn bất kỳ

## Một số câu lệnh
![](https://i.imgur.com/9aYRVYI.png)
- glBegin(GL_POINTS)
![](https://i.imgur.com/J1uZjbu.png)
- glBegin(GL_LINES)
![](https://i.imgur.com/uBNzUT2.png)
- glBegin(GL_LINE_STRIP)
![](https://i.imgur.com/Sv4xaLi.png)
- glBegin(GL_LINE_LOOP)
![](https://i.imgur.com/6iTQ2VF.png)
- glBegin(GL_TRIANGLES)
- ![](https://i.imgur.com/7vzEojk.png)
- vẽ đường biên và tô màu đường
![](https://i.imgur.com/pMSJA5s.png)
- tô điểm
- ![](https://i.imgur.com/mqVXVVh.png)
![](https://i.imgur.com/9ny7mpD.png)
- vừa vẽ hình vừa vẽ biên
- ![](https://i.imgur.com/BYlSulL.png)
![](https://i.imgur.com/YVOegin.png)
- glBegin(GL_TRIANGLE_STRIP): vẽ 4 tâm trên 6 đỉnh 
- 3 đỉnh liền
- ![](https://i.imgur.com/MCmwVI4.png)
- GL_TRIANGLES_FAN: như quạt, các tam giác chung 1 đỉnh(v0)
- GL_POLYGON: bất kỳ
- 