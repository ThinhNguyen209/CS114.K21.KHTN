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
 ![116298614_318765245945721_8799007558729821363_n](https://user-images.githubusercontent.com/62539475/88999006-907f5e00-d31d-11ea-8b95-04f5f842f899.jpg)
 - Loại dữ liệu: ảnh jpg
 - Phương thức: lập nhóm 3 người có chung ý tưởng làm đồ án liên quan về trái cây 
  - Train data: chúng em chụp hình và quay trái cây với nhiều góc quay khác nhau. Trong phần quay, chúng em lọc lấy frame ảnh
  - Test data: chúng em chụp hình là chủ yếu
 - Địa điểm thu thập: siêu thị, chợ, cây nhà lá vườn
 - Thống kê số lượng trái cây của mỗi loại:
 
|             | Train dataset | Test dataset |
|-------------|---------------|--------------|
| Ổi          |      697      |      200     |
| Xoài        |      764      |      200     |
| Mận         |      1149     |      200     |
| Khế         |      941      |      200     |
| Dừa         |      1055     |      200     |
| Cam         |      1038     |      200     |
| Táo         |      902      |      200     |
| Mãn Cầu(Na) |      1053     |      200     |
| Dưa hấu     |      710      |      200     |
| Bơ          |      1262     |      200     |
| Thanh long  |      356      |      200     |
| Chuối       |      1160     |      200     |
 ## 4. TIỀN XỬ LÍ DỮ LIỆU:
 - Phương thức: tiếp tục làm nhóm
 - Các bước thực hiện:
  - Xén ảnh để loại bỏ background thừa, có thể gây nhiễu. Trong đó em phụ trách cắt:
    - Train data: táo, 
    - Test data: 
  - 
