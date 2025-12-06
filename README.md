# 📈 Ultima: AI-Powered Stock Trading System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Enabled-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📖 Giới thiệu (Overview)

**Ultima** là một hệ thống Khoa học Dữ liệu toàn diện (End-to-End Data Science Project) được thiết kế để dự đoán biến động giá cổ phiếu BlackRock (BLK) và giả lập giao dịch tự động.

Dự án không chỉ dừng lại ở việc dự báo, mà còn tích hợp một **Backtesting Pipeline** để kiểm chứng lợi nhuận thực tế so với chiến lược Mua và Nắm giữ (Buy & Hold).

## 🚀 Tính năng chính (Key Features)

* **Data Pipeline:** Tự động tải, làm sạch và xử lý dữ liệu chuỗi thời gian (Time Series).
* **EDA chuyên sâu:** Phân tích phân phối lợi nhuận, tương quan và tính mùa vụ (Seasonality).
* **Ensemble Modeling:** Kết hợp sức mạnh của 3 thuật toán hàng đầu:
    * 🧠 **LSTM (Long Short-Term Memory):** Deep Learning cho chuỗi thời gian.
    * 🌳 **Random Forest:** Thuật toán nền tảng (Baseline).
    * 🚀 **XGBoost:** Thuật toán tăng cường (Gradient Boosting) tốc độ cao.
* **Backtesting Engine:** Giả lập giao dịch với số vốn thực tế, có tính phí giao dịch và vẽ đường cong tài sản (Equity Curve).

## 🛠️ Công nghệ sử dụng (Tech Stack)

* **Ngôn ngữ:** Python
* **Xử lý dữ liệu:** Pandas, NumPy
* **Trực quan hóa:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, XGBoost
* **Deep Learning:** TensorFlow / Keras

## 📊 Kết quả (Results)

> *Kết quả chạy thử nghiệm trên dữ liệu 10 năm của BlackRock (BLK):*

| Model Strategy | Lợi nhuận (Profit) | So với thị trường | Đánh giá |
| :--- | :--- | :--- | :--- |
| **LSTM Strategy** | `$14,340.45` | ✅ Vượt trội | Tốt nhất |
| **XGBoost** | `$14,340.45` | ❌ Thấp hơn | Cần cải thiện |
| **Buy & Hold** | `$14,340.45` | (Benchmark) | - |

## ⚙️ Cài đặt & Sử dụng (Installation)

1. **Clone repository:**
   ```bash
   git clone https://github.com/TranNhatMinhTri/CE_Tri23280094.git
## 📝 Tác giả
* **Trần Nhật Minh Trí** 
* Liên hệ: nhatminhtri80@gmail.com
