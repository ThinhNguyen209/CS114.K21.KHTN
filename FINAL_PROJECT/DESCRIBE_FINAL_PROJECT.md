# ĐỒ ÁN MÔN HỌC
## I.ĐỒ ÁN: DỰ ĐOÁN LOẠI TRÁI CÂY TRONG ẢNH 
![fruit](https://user-images.githubusercontent.com/62539475/87747768-5e9ad180-c81e-11ea-92f8-ac4fa70787f3.jpg)
### MÔ TẢ BÀI TOÁN:
- Dự đoán trái cây trong ảnh thuộc loại trái gì?
  - Input: là bức ảnh chụp một trái cây
  - Output: là tên của loại trái trong ảnh
- Có 12 loại trái cây được dùng trong đồ án gồm:
  ![image fruit-1](https://user-images.githubusercontent.com/62539475/87951188-77331200-cad2-11ea-89b6-74b2bea1d883.jpg)
## II. 7 BƯỚC TRONG MACHINE LEARNING
 ### 1. THU THẬP DỮ LIỆU:
 ![116298614_318765245945721_8799007558729821363_n](https://user-images.githubusercontent.com/62539475/88999006-907f5e00-d31d-11ea-8b95-04f5f842f899.jpg)
 - Loại dữ liệu: ảnh jpg
 - Phương thức: lập nhóm 3 người có chung ý tưởng làm đồ án liên quan về trái cây 
   - Train data: chúng em chụp hình và quay trái cây với nhiều góc quay khác nhau. Trong phần quay, chúng em lọc lấy frame ảnh
   - Test data: chúng em chụp hình là chủ yếu
 - Địa điểm thu thập: siêu thị, chợ, cây nhà lá vườn
 - Bộ dataset lúc đầu: 15200 ảnh nhưng do em lọc bớt ảnh gây nhiễu với trùng nhau còn là 14337 ảnh
 - Thống kê số lượng ảnh của mỗi loại trái cây:
 
|             | Train dataset | Test dataset |
|-------------|---------------|--------------|
| Ổi          |      697     |      200     |
| Xoài        |      963      |      200     |
| Mận         |      1149     |      200     |
| Khế         |      1172      |      200     |
| Dừa         |      1055     |      200     |
| Cam         |      1038     |      200     |
| Táo         |      1154      |      200     |
| Mãn Cầu(Na) |      938     |      200     |
| Dưa hấu     |      955      |      200     |
| Bơ          |      1262     |      200     |
| Thanh long  |      394      |      200     |
| Chuối       |      1160     |      200     |
 ### 2. CHUẨN BỊ DỮ LIỆU:
 - Phương thức: tiếp tục làm nhóm
 - Các bước thực hiện:
  - Xén ảnh thủ công để loại bỏ background thừa, có thể gây nhiễu (tốn thời gian làm nhất)
  - Resize ảnh với kích thước 256x256. 
 - Rút trích đặt trưng: làm cá nhân 
  -Sử dụng HOG(Histogram of Oriented Gradients)
### 3. CHỌN MODEL:
- Support Vector Machine (SVC)
- K-Nearest Neighbor
- Decision Tree
### 4. TRAIN MODEL
### 5. ĐÁNH GIÁ MODEL
### 6. TINH CHỈNH THAM SỐ
### 7. SỬ DỤNG MODEL ĐỂ DỰ ĐOÁN
