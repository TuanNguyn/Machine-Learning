# Machine Learning

Đây là repository lưu trữ các bài tập, bài thực hành và ghi chú trong quá trình học Machine Learning.
Giảng viên hướng dẫn: Đỗ Như Tài

## Mục tiêu

- Nắm được các khái niệm nền tảng của học máy.
- Thực hành quy trình xử lý dữ liệu và xây dựng mô hình.
- Đánh giá, so sánh và cải thiện kết quả dự đoán.
- Lưu lại mã nguồn, notebook và kết quả của từng bài tập.

## Nội dung

Các chủ đề có thể bao gồm:

- Tiền xử lý và khám phá dữ liệu.
- Hồi quy tuyến tính và hồi quy logistic.
- K-Nearest Neighbors (KNN).
- Decision Tree và Random Forest.
- Support Vector Machine (SVM).
- Clustering.
- Đánh giá mô hình và tối ưu tham số.

## Cấu trúc thư mục

```text
Machine-Learning/
├── README.md
├── data/             # Dữ liệu sử dụng trong bài tập
├── notebooks/        # Jupyter Notebook
├── src/              # Mã nguồn Python
├── results/          # Kết quả, biểu đồ và báo cáo
└── requirements.txt  # Các thư viện cần thiết
```

> Cấu trúc có thể thay đổi tùy theo yêu cầu của từng bài tập.

## Cài đặt môi trường

Khuyến nghị sử dụng Python 3.10 trở lên và môi trường ảo:

```bash
python -m venv .venv
```

Kích hoạt môi trường trên Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Cài đặt thư viện:

```bash
pip install -r requirements.txt
```

Nếu chưa có `requirements.txt`, có thể cài các thư viện thường dùng:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Cách sử dụng

1. Kích hoạt môi trường Python.
2. Mở notebook hoặc chạy chương trình tương ứng với bài tập.
3. Đọc phần mô tả và mục tiêu ở đầu mỗi bài.
4. Chạy các bước xử lý dữ liệu, huấn luyện và đánh giá mô hình.
5. Lưu kết quả và ghi chú những điểm quan trọng sau mỗi bài.

Khởi động Jupyter Notebook:

```bash
jupyter notebook
```

## Tác giả

Repository phục vụ mục đích học tập và thực hành Machine Learning.