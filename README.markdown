# 🐶🐱 Phân Loại Chó và Mèo bằng SVM

Dự án này xây dựng một mô hình phân loại hình ảnh nhị phân để phân biệt giữa **chó và mèo** sử dụng thuật toán **Support Vector Machine (SVM)** cùng với các kỹ thuật tiền xử lý và trích xuất đặc trưng tối ưu.

## 📌 Điểm Nổi Bật

- 🔍 Thay đổi kích thước ảnh về **128×128 pixels**
- 🧠 Trích xuất đặc trưng bằng **HOG (Histogram of Oriented Gradients)**
- 🔄 Chuẩn hóa dữ liệu với **StandardScaler**
- 📉 Giảm chiều dữ liệu bằng **PCA (50 thành phần chính)**
- ⚙️ Huấn luyện mô hình SVM với **kernel RBF**
- 🔎 Tối ưu siêu tham số với **GridSearchCV**
- 📊 Dự đoán ảnh ngẫu nhiên từ tập kiểm tra

## 🗂️ Dữ liệu

Bộ dữ liệu được sử dụng được công khai trên Kaggle:  
👉 [Cat and Dog Dataset – Tong Python trên Kaggle](https://www.kaggle.com/datasets/tongpython/cat-and-dog)

Cấu trúc thư mục sau khi giải nén:

```
dataset/
│
├── training_set/
│   ├── cats/
│   └── dogs/
│
└── test_set/
    ├── cats/
    └── dogs/
```

## 🚀 Cách Chạy Dự Án

1. Clone repository này về máy:

```bash
git clone https://github.com/ten-cua-ban/ten-repo-cua-ban.git
cd ten-repo-cua-ban
```

2. Cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

3. Tải dữ liệu từ Kaggle và giải nén vào thư mục `dataset/`

4. Mở notebook để chạy:

```bash
jupyter notebook SVMCatDogUpdate.ipynb
```

## 🧪 Kết Quả Mẫu

Ảnh ngẫu nhiên từ tập kiểm tra cùng với dự đoán:

```
Dự đoán: Dog ✅
Thực tế: Dog
```

## 🧠 Thư Viện Sử Dụng

- scikit-learn
- matplotlib
- numpy
- opencv-python
- scikit-image (dùng cho HOG)

## 📄 Mô Tả Tập Tin

- `SVMCatDogUpdate.ipynb`: Notebook chính thực hiện tiền xử lý, huấn luyện, đánh giá và hiển thị kết quả.