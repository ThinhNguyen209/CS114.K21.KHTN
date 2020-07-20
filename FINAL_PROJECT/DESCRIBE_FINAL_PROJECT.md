# ĐỒ ÁN MÔN HỌC
## 1. TÊN ĐỒ ÁN: DỰ ĐOÁN LOẠI TRÁI CÂY TRONG ẢNH 
![fruit](https://user-images.githubusercontent.com/62539475/87747768-5e9ad180-c81e-11ea-92f8-ac4fa70787f3.jpg)
## 2. MÔ TẢ BÀI TOÁN:
- Dự đoán trái cây trong ảnh thuộc loại trái gì?
  - Input: là bức ảnh chụp một trái cây
  - Output: là tên của loại trái trong ảnh
- Có 12 loại trái cây được dùng trong đồ án gồm:
  ![image fruit-1](https://user-images.githubusercontent.com/62539475/87951188-77331200-cad2-11ea-89b6-74b2bea1d883.jpg)

 ## 3. THU THẬP DỮ LIỆU:
 - Loại dữ liệu: ảnh jpg
 - Phương thức: lập nhóm 3 người có chung ý tưởng làm đồ án liên quan về trái cây 
  - Train data: chúng em chụp hình và quay trái cây với nhiều góc quay khác nhau. Trong phần quay, chúng em lọc lấy frame ảnh
  - Test data: chúng em chụp hình là chủ yếu
 - Địa điểm thu thập: siêu thị, chợ, cây nhà lá vườn
 - Thống kê số lượng trái cây của mỗi loại:
 
|             | Train dataset | Test dataset |
|-------------|---------------|--------------|
| Ổi          |      697      |      434     |
| Xoài        |      764      |      402     |
| Mận         |      1149     |      533     |
| Khế         |      941      |      434     |
| Dừa         |      1055     |      330     |
| Cam         |      1038     |      650     |
| Táo         |      902      |      457     |
| Mãn Cầu(Na) |      1053     |      307     |
| Dưa hấu     |      710      |      447     |
| Bơ          |      1262     |      416     |
| Thanh long  |      356      |      394     |
| Chuối       |      1160     |      348     |
 ## 4. TIỀN XỬ LÍ DỮ LIỆU:
 - Phương thức: tiếp tục làm nhóm
 - Các bước thực hiện:
  - Xén ảnh để loại bỏ background thừa, có thể gây nhiễu. Trong đó em phụ trách cắt:
    - Train data: táo, 
    - Test data: 
  - 
