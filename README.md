# ⚡ Electric Vehicle Population Analysis

Phân tích dữ liệu dân số xe điện để khám phá xu hướng phát triển phương tiện thân thiện môi trường. Dự án này sử dụng dữ liệu thực tế để phân tích theo năm, hãng xe, địa phương và loại xe điện.

## 📁 Dataset

- **File**: `Electric_Vehicle_Population_Data.csv`
- **Thông tin bao gồm**:
  - `Make`, `Model`, `Model Year`
  - `Electric Vehicle Type`: BEV / PHEV
  - `Electric Range`, `Base MSRP`
  - `County`, `City`, `ZIP Code`
  - `Vehicle Location` (GPS)
  - `Utility Provider`, `VIN` (ẩn danh)

## 🎯 Mục tiêu

- Thống kê số lượng xe điện theo năm sản xuất
- Phân loại theo loại xe (BEV, PHEV)
- Phân tích sự phân bố xe theo địa lý
- Quan hệ giữa `Electric Range` và `Base MSRP`
- Xác định các hãng xe phổ biến nhất
- Gợi ý chính sách và chiến lược phát triển hạ tầng

## 📒 Notebook chính

- **`Electric Vehicle Population Analysis.ipynb`**
  - Đọc và xử lý dữ liệu
  - Trực quan hóa:
    - Phân bố xe theo năm
    - Top hãng xe có nhiều EV nhất
    - Mối quan hệ giữa tầm hoạt động và giá xe
    - Heatmap hoặc bản đồ địa lý (nếu áp dụng)
  - Phân tích xu hướng và rút ra kết luận

## 🛠️ Công nghệ sử dụng

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- plotly (nếu cần đồ họa tương tác)
- folium hoặc geopandas (cho bản đồ)
- scikit-learn (nếu mở rộng thêm phân cụm)

## 📊 Một số kết quả dự kiến

- Tỷ lệ BEV đang tăng đều qua các năm
- Một số thành phố như Seattle, Bellevue có mật độ EV cao
- Tesla chiếm phần lớn thị phần EV
- Các dòng xe có tầm hoạt động cao thường có giá cao hơn

## 📂 Cấu trúc dự án

<pre lang="markdown"><code>## 📂 Cấu trúc dự án ``` 📦 EV-Population-Analysis ┣ 📊 Electric Vehicle Population Analysis.ipynb ┣ 📁 data ┃ ┗ 📄 Electric_Vehicle_Population_Data.csv ┣ 📄 README.md ┗ 📄 requirements.txt ``` </code></pre>
