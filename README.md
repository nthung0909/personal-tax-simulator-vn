# 🇻🇳 vietnam-tax-reform-calculator

## Công Cụ So Sánh Thuế Thu nhập Cá nhân (TNCN) Việt Nam

Đây là một công cụ web đơn giản, được xây dựng bằng HTML, CSS (Bootstrap 5) và JavaScript, nhằm mục đích tính toán và so sánh mức Thuế Thu nhập Cá nhân (PIT) phải nộp theo **Kịch bản hiện hành** (trước 01/07/2026) và **Kịch bản mới dự kiến** (sau 01/07/2026).

Mục tiêu chính là giúp người lao động hình dung được mức chênh lệch (tiết kiệm hoặc đóng thêm) hàng tháng sau khi áp dụng các mức giảm trừ và biểu thuế mới.

### ✨ Các Tính Năng Chính

* **So sánh Hai Kịch bản:** Tính toán song song mức thuế theo quy định hiện hành và dự thảo mới.
* **Tính toán Tự động:** Kết quả cập nhật ngay lập tức khi người dùng thay đổi bất kỳ trường nhập liệu nào (Lương Gross, Lương đóng BHXH, Số người phụ thuộc, Vùng lương).
* **Định dạng Tiền tệ:** Tự động định dạng các trường nhập liệu tiền tệ (dấu chấm phân cách hàng nghìn) và chỉ cho phép nhập số.
* **Chi tiết Tính toán:** Hiển thị chi tiết từng bước tính toán (BHXH, Giảm trừ, Thu nhập chịu thuế) cho cả hai kịch bản.

### ⚙️ Cấu Trúc Dự Án

Dự án chỉ bao gồm một file duy nhất:

| File | Mô tả |
| :--- | :--- |
| `index.html` | Chứa toàn bộ giao diện (HTML/Bootstrap 5) và logic tính toán (JavaScript). |

### 🚀 Cách Sử Dụng (Local)

Đây là một ứng dụng tĩnh (Static Application) và không yêu cầu môi trường máy chủ (Server).

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Tên_Tài_Khoản_Của_Bạn]/vietnam-tax-reform-calculator.git
    cd vietnam-tax-reform-calculator
    ```
2.  **Mở file:** Mở file `index.html` bằng bất kỳ trình duyệt web hiện đại nào (Chrome, Firefox, Edge).
3.  **Sử dụng:** Nhập các thông số đầu vào và xem kết quả so sánh.

### 📊 Các Thông Số & Quy tắc Tính Toán

Công cụ này dựa trên các dự thảo luật thuế TNCN mới nhất và các quy định bảo hiểm xã hội hiện hành.

| Thông số | Kịch bản Hiện hành (7 Bậc, 11tr/4.4tr) | Kịch bản Mới Dự kiến (5 Bậc, 15.5tr/6.2tr) |
| :--- | :--- | :--- |
| **Giảm trừ bản thân** | 11,000,000 VNĐ/tháng | 15,500,000 VNĐ/tháng |
| **Giảm trừ người phụ thuộc** | 4,400,000 VNĐ/tháng | 6,200,000 VNĐ/tháng |
| **Biểu thuế PIT** | 7 Bậc (Lũy tiến từng phần) | 5 Bậc (Lũy tiến từng phần) |
| **BHXH** | 8% lương đóng BHXH (Trần 20 lần Lương Cơ sở) | 8% lương đóng BHXH (Trần 20 lần Lương Cơ sở) |
| **BHTN** | 1% lương đóng BHXH (Trần 20 lần Lương Tối thiểu Vùng) | 1% lương đóng BHXH (Trần 20 lần Lương Tối thiểu Vùng) |

***Lưu ý:*** *Các mức giảm trừ và biểu thuế MỚI chỉ là **dự kiến** theo các đề xuất sửa đổi Luật Thuế TNCN. Kết quả chỉ mang tính tham khảo và không phải là cam kết pháp lý.*
