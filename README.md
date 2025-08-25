# 😰 Phân tích mức độ căng thẳng (Stress Level Analysis)

## 📌 Giới thiệu
Dự án này tập trung vào việc **phân tích và dự đoán mức độ căng thẳng** của con người dựa trên dữ liệu khảo sát.  
Mục tiêu chính:
- Khám phá dữ liệu và trực quan hóa  
- Phân tích mối quan hệ giữa các yếu tố cá nhân và mức độ stress  
- Áp dụng **PCA** để giảm chiều dữ liệu  
- Xây dựng mô hình học máy để dự đoán mức độ stress  

---

## 📂 Dữ liệu
Bộ dữ liệu bao gồm nhiều biến liên quan đến thông tin cá nhân và lối sống, ví dụ:
- **Gender** – giới tính  
- **Age** – tuổi  
- **Sleep Duration** – thời gian ngủ  
- **Work/Study Hours** – số giờ làm việc/học tập  
- **Diet, Physical Activity** – chế độ ăn, vận động  
- **Stress Level** – biến mục tiêu (Low, Medium, High)  

---

## 🛠️ Quy trình
1. **Tiền xử lý dữ liệu**
   - Xử lý dữ liệu thiếu  
   - Chuẩn hóa dữ liệu số  
   - Mã hóa biến phân loại  

2. **Phân tích khám phá (EDA)**
   - Thống kê mô tả  
   - Biểu đồ phân phối mức độ stress  
   - Heatmap ma trận tương quan  

3. **Giảm chiều dữ liệu**
   - **PCA** để phát hiện các yếu tố tiềm ẩn  

4. **Xây dựng mô hình**
   - Decision Tree  
   - Random Forest  
   - Logistic Regression  
   - KNN (k-Nearest Neighbors)  
   - SVM (Support Vector Machine)  

5. **Đánh giá mô hình**
   - Accuracy, Precision, Recall, F1-score  
   - Ma trận nhầm lẫn  

---

## 📈 Kết quả nổi bật
- Các yếu tố **giấc ngủ** và **số giờ làm việc/học tập** có ảnh hưởng rõ rệt đến mức độ stress  
- **Chế độ ăn uống và vận động** cũng đóng vai trò quan trọng  
- **Random Forest** và **SVM** đạt kết quả tốt nhất (Accuracy ~80–85%)  
- PCA cho thấy dữ liệu có thể rút gọn còn **2–3 thành phần chính**  

---

## 🚀 Công nghệ sử dụng
- **Ngôn ngữ:** R  
- **Thư viện:**  
  - `dplyr`, `tidyr` – xử lý dữ liệu  
  - `ggplot2`, `corrplot` – trực quan hóa  
  - `psych`, `factoextra` – PCA  
  - `caret`, `randomForest`, `e1071`, `class` – mô hình học máy  

---

## 📊 Trực quan hóa
- Biểu đồ phân phối stress level  
- Heatmap tương quan  
- PCA Biplot  
- Ma trận nhầm lẫn của mô hình  

---

## 📁 Cấu trúc repo
- `StressLevelDataset.csv` – dữ liệu gốc  
- `Stress_level_analysis.Rmd` – code phân tích và mô hình  
- `Stress_level_analysis.pdf` – báo cáo chi tiết  

---

## 👨‍💻 Tác giả
Thực hiện bởi [Trần Đăng Khôi](www.linkedin.com/in/trandangkhoi184)\\
Mục đích: Học tập và nghiên cứu trong lĩnh vực **Phân tích dữ liệu & Tâm lý học với R**.
