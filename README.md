# 📈 Stock Revenue Dashboard — Tesla & GameStop

Dự án phân tích và trực quan hóa dữ liệu chứng khoán kết hợp web scraping doanh thu theo quý.

## 🎯 Mục tiêu

So sánh **giá cổ phiếu** và **doanh thu thực tế** của hai công ty nổi tiếng nhằm trả lời câu hỏi: _giá cổ phiếu có thực sự phản ánh sức khỏe kinh doanh không?_

## 🗂️ Nội dung

| File | Mô tả |
|------|-------|
| `stock_dashboard.ipynb` | Notebook chính — toàn bộ code phân tích và dashboard |
| `tesla_dashboard.png` | Ảnh dashboard Tesla (output sau khi chạy) |
| `gamestop_dashboard.png` | Ảnh dashboard GameStop (output sau khi chạy) |

## ⚡ Cách chạy

```bash
# Clone repo
git clone https://github.com/NguyenBao-33/stock-revenue-dashboard.git
cd stock-revenue-dashboard

# Cài thư viện
pip install -r requirements.txt

# Mở notebook
jupyter notebook stock_dashboard.ipynb
```

## 📦 Thư viện sử dụng

```
yfinance>=0.2.38
pandas>=1.3.0
requests>=2.25.0
beautifulsoup4>=4.9.0
matplotlib>=3.4.0
lxml>=4.6.0
```

## 🔍 Kết quả & Nhận xét

**Tesla (TSLA):**
- Giá tăng mạnh từ cuối 2019 do kỳ vọng vào xe điện
- Doanh thu tăng trưởng đều đặn và bền vững — nền tảng thực chất

**GameStop (GME):**
- Doanh thu thực đang suy giảm (mô hình game vật lý lỗi thời)
- Giá cổ phiếu bơm cực mạnh đầu 2021 do **short squeeze** từ r/WallStreetBets
- Ví dụ điển hình: **giá ≠ giá trị thực của doanh nghiệp**

## 🛠️ Tech stack

- **Data collection:** `yfinance` API + web scraping với `BeautifulSoup`
- **Data processing:** `pandas`
- **Visualization:** `matplotlib`

---

> Dữ liệu chỉ hiển thị đến tháng 6/2021 để khớp với nguồn dữ liệu scraping.
