# 📈 RetailStockVN - Web Dashboard Phân Tích Tài Chính Ngành Bán Lẻ

Giao diện Web Frontend hiện đại giúp giới thiệu và trực quan hóa (nhúng Power BI) báo cáo phân tích tình hình tài chính của các doanh nghiệp thuộc nhóm ngành Bán lẻ đang niêm yết trên thị trường chứng khoán Việt Nam. Dự án này thuộc đồ án tốt nghiệp nghiên cứu phân tích tài chính doanh nghiệp.

---

## 🖥️ Giao diện trang chủ (Preview)
Dự án được thiết kế với phong cách **Dark Mode hiện đại (Modern Dark Aesthetic)**, sử dụng hiệu ứng đổ bóng phát sáng (Aesthetic Blobs) ở nền và font chữ tinh tế, mang lại trải nghiệm xem báo cáo cao cấp và chuyên nghiệp.

---

## ✨ Tính năng nổi bật
* **Trang chủ (`index.html`)**: Giới thiệu dự án, quy mô nghiên cứu (20 doanh nghiệp ngành bán lẻ) và lịch cập nhật dữ liệu hàng ngày.
* **Trang Dashboard chuyên dụng (`dashboard.html`)**: Nhúng trực tiếp báo cáo **Power BI tương tác trực quan**, tích hợp nút bấm chuyển đổi nhanh sang chế độ toàn màn hình web (Fullscreen API) để tối ưu không gian phân tích dữ liệu.
* **Trang Giới thiệu (`about.html`)**: Mô tả chi tiết phương pháp nghiên cứu tài chính, các chỉ số phân tích, mục tiêu và phạm vi của đề tài đồ án tốt nghiệp.
* **Trang Liên hệ (`contact.html`)**: Biểu mẫu liên hệ phản hồi dành cho người dùng quan tâm đến dự án.

---

## 🛠️ Công nghệ sử dụng
* **Frontend**: HTML5 & CSS3 (Vanilla CSS thuần túy cho độ tùy biến giao diện tối đa).
* **Nhúng báo cáo**: iframe Power BI hỗ trợ xem tương tác trực tuyến trên máy chủ đám mây của Microsoft.
* **Interactive Scripts**: JavaScript (Vanilla JS) điều khiển tính năng Fullscreen và tương tác cơ bản trên thanh điều hướng.

---

## 📁 Cấu trúc thư mục
* `index.html`: Giao diện trang chủ giới thiệu.
* `dashboard.html`: Giao diện nhúng biểu đồ báo cáo Power BI.
* `about.html`: Giao diện giới thiệu phương pháp phân tích của đồ án.
* `contact.html`: Giao diện trang liên hệ.
* `style.css`: Toàn bộ mã phong cách thiết kế, định dạng giao diện, hiệu ứng chuyển động và responsive.

---

## 🚀 Hướng dẫn khởi chạy dự án
Vì dự án được xây dựng bằng HTML/CSS tĩnh nên bạn không cần cài đặt bất kỳ server hay thư viện phức tạp nào:
1. Tải dự án về máy:
   ```bash
   git clone https://github.com/ThanhHoaNg-12/web-dashboard.git
   ```
2. Click đúp chuột trực tiếp vào file **`index.html`** để mở ứng dụng trên bất kỳ trình duyệt nào (Chrome, Edge, Firefox, Safari).
3. (Khuyến nghị cho nhà phát triển): Sử dụng extension **Live Server** trên VS Code để chạy dự án với tính năng tự động tải lại (hot reload) khi chỉnh sửa code.
