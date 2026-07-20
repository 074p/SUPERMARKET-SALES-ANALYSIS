# 🛒 Supermarket Sales Analysis

## 📌 Giới thiệu
Dự án này phân tích dữ liệu bán hàng của siêu thị nhằm tìm hiểu hiệu suất kinh doanh, xu hướng tiêu thụ, và đưa ra các giải pháp quản lý phù hợp. Báo cáo được thực hiện bởi **Nhóm 7 – Lớp INS3254 – 03, Học kỳ 2 (2023–2024), Trường Quốc tế – ĐHQGHN**.

## 🎯 Mục tiêu
- Phân tích dữ liệu bán hàng theo **năm, khu vực, thành phố, danh mục và sản phẩm**.  
- Xác định **top sản phẩm bán chạy**, **phân khúc khách hàng**, và **xu hướng theo khu vực**.  
- Ứng dụng các công cụ phân tích (Python, Tableau, RapidMiner) để trực quan hóa dữ liệu và xây dựng mô hình dự đoán.  
- Đề xuất giải pháp quản lý doanh thu và chiến lược marketing cho siêu thị.

## 📊 Dataset
Dữ liệu bao gồm các thuộc tính chính:
- **Order_Date, Ship_Date** – Ngày đặt và ngày giao hàng  
- **Ship_Mode** – Phương thức vận chuyển  
- **Segment** – Phân khúc khách hàng (Consumer, Corporate, Home Office)  
- **City, State, Region** – Thông tin địa lý  
- **Category, Sub_Category** – Loại sản phẩm  
- **Sales** – Doanh thu  

## 🛠️ Công cụ sử dụng
- **Python** (Pandas, Matplotlib, Seaborn, NumPy)  
- **Tableau** – Trực quan hóa dữ liệu (Bar chart, Column chart)  
- **RapidMiner** – Mô hình cây quyết định (ID3)  

## 📈 Các phân tích chính
- **Tổng doanh thu theo năm (2015–2018)**  
- **Doanh thu theo danh mục & phân loại sản phẩm**  
- **Top sản phẩm bán chạy nhất**  
- **Phân khúc khách hàng & doanh thu theo khu vực**  
- **Top 10 thành phố có doanh thu cao nhất & thấp nhất**  
- **Mô hình cây quyết định (Decision Tree)** để dự đoán xu hướng bán hàng.  

## ✅ Kết quả
- **Technology** là danh mục có doanh thu cao nhất.  
- **Phones và Chairs** là các sub-category bán chạy nhất.  
- **Consumer segment** chiếm ~50% tổng doanh thu.  
- **New York City** là thành phố có doanh thu cao nhất.  
- Mô hình **ID3 Decision Tree** giúp đưa ra giải pháp quản lý và marketing phù hợp cho từng khu vực.  

## 🚀 Hướng phát triển
- Nâng cao độ chính xác của mô hình dự đoán bằng cách thử nghiệm thêm các thuật toán khác.  
- Mở rộng dataset để phân tích xu hướng dài hạn.  
- Ứng dụng kết quả phân tích vào thực tế quản lý siêu thị.  

---

📍 **Hà Nội, 2024**  
Dự án học phần *Introduction to Data Science* – Trường Quốc tế, ĐHQGHN.
