# [Thực hành] Tạo Website Template Có Giao Diện Đẹp Mắt

Dự án bài thực hành **Tạo Website Template Có Giao Diện Đẹp Mắt (Website Template Advanced)**, ứng dụng các kỹ thuật thiết kế web hiện đại:
- **Header với hình nền và hiệu ứng mờ (Background Blur Overlay)**.
- **Thanh điều hướng cố định (Fixed Navigation Menu)** kèm hiệu ứng chuyển màu khi di chuột (Hover effect).
- **Phần nội dung dạng lưới thẻ (CSS Grid Card Layout)** với hiệu ứng phóng to tương tác (`transform: scale(1.05)`).
- **Chân trang chuyên nghiệp 2 cột (Flexbox Footer)** với dấu chấm (`•`) phân cấp nội dung chuẩn mực.

---

## 🎯 Mục Tiêu Bài Tập

1. **Nâng cấp giao diện**: Áp dụng hình nền, hiệu ứng mờ kính (blur), chữ nổi bật và hiệu ứng hover mượt mà.
2. **Thực hành CSS Flexbox & Grid**:
   - Sử dụng **Flexbox** cho Navigation Menu và Footer 2 cột.
   - Sử dụng **CSS Grid** (`repeat(3, 1fr)`) cho phần danh sách dịch vụ dạng thẻ.
3. **Cải thiện UX/UI**: Thiết kế chuyên nghiệp, thanh menu cố định giúp người dùng điều hướng nhanh chóng từ bất kỳ vị trí nào trên trang.

---

## 📁 Cấu Trúc Thư Mục Dự Án

```plaintext
website-template-advanced/
├── index.html               # Mã nguồn HTML cấu trúc trang web
├── css/
│   └── style.css           # Toàn bộ mã CSS định dạng và hiệu ứng
├── images/
│   ├── banner.jpg          # Hình nền header chính
│   ├── service1.jpg        # Hình ảnh minh họa Dịch vụ 1 (Thiết kế Website)
│   ├── service2.jpg        # Hình ảnh minh họa Dịch vụ 2 (SEO & Marketing)
│   └── service3.jpg        # Hình ảnh minh họa Dịch vụ 3 (Hỗ trợ 24/7)
├── README.md                # Tài liệu hướng dẫn chi tiết
└── .gitignore               # Tệp cấu hình loại trừ file rác Git
```

---

## 💡 Các Kỹ Thuật CSS Nổi Bật Được Triển Khai

| Thành phần | Thuộc tính CSS cốt lõi | Ý nghĩa và hiệu ứng |
| :--- | :--- | :--- |
| **Header Background Blur** | `filter: blur(8px)`, `::before`, `::after` | Tạo lớp nền ảnh mờ nghệ thuật kèm lớp phủ tối giúp chữ màu trắng nổi bật rõ ràng |
| **Fixed Navigation** | `position: fixed; top: 0; width: 100%; z-index: 1000` | Menu luôn ghim chặt ở đầu màn hình khi người dùng cuộn trang |
| **Menu Hover Transition** | `transition: 0.3s; color: #f39c12;` | Đổi màu chữ sang cam vàng mượt mà khi rê chuột vào liên kết |
| **Card Layout (CSS Grid)** | `display: grid; grid-template-columns: repeat(3, 1fr); gap: 25px;` | Bố cục dạng lưới 3 cột cân đối và tự động co giãn |
| **Card Hover Effect** | `transform: scale(1.05); box-shadow: ...` | Thẻ dịch vụ nâng lên và phóng to nhẹ tạo cảm giác tương tác sống động |
| **Footer (Flexbox)** | `display: flex; justify-content: space-between;` | Chia 2 cột thông tin bản quyền và liên kết mạng xã hội |

---

## 🚀 Hướng Dẫn Chạy Thử Nghiệm

1. Mở file [index.html](file:///d:/BaiTapGithub/index.html) trực tiếp bằng trình duyệt (Chrome, Edge, Firefox).
2. Hoặc mở qua tiện ích mở rộng **Live Server** trong VS Code / Antigravity IDE:
   - Chuột phải vào `index.html` chọn **Open with Live Server**.
   - Truy cập địa chỉ `http://127.0.0.1:5500/index.html`.

---

## 👨‍💻 Thông Tin Học Viên

- **Học viên**: dtc245200059
- **Email**: dtc245200059@ictu.edu.vn
- **Bài thực hành**: Tạo Website Template Có Giao Diện Đẹp Mắt
