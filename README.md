# 🏷️ Bartender Lite

**Bartender Lite** là ứng dụng web **thiết kế & in tem nhãn** đơn giản, nhẹ, chạy hoàn toàn trên trình duyệt — miễn phí, không cần cài đặt, không cần đăng nhập.

🔗 **Dùng thử ngay:** [ngthhung-dev.github.io/bartender-lite-web](https://ngthhung-dev.github.io/bartender-lite-web/)

## ✨ Tính năng chính

- **Thiết kế tem trực quan** — kéo thả, resize, xoay tự do các phần tử ngay trên khung thiết kế (canvas), căn chỉnh với trang bằng 1 cú click.
- **Các loại phần tử hỗ trợ:**
  - 📝 Văn bản (tùy chỉnh cỡ chữ, độ đậm, số dòng tối đa, căn lề)
  - 🔗 Trường dữ liệu Excel (hiển thị động theo từng dòng dữ liệu)
  - \|\|\|\| Mã vạch (nhiều định dạng, tùy chỉnh hiển thị số bên dưới)
  - ⬜ Mã QR
  - 🖼️ Khung hình / Chèn ảnh
- **Nạp dữ liệu từ Excel/CSV** (.xls, .xlsx, .csv) và **mapping** từng cột dữ liệu vào từng phần tử trên tem (kèm tiền tố/hậu tố tùy chỉnh) — in hàng loạt tem với dữ liệu khác nhau chỉ trong vài giây.
- **Xem trước dữ liệu** — duyệt qua từng dòng Excel đã nạp ngay trên khung thiết kế trước khi in.
- **Cài đặt in ấn linh hoạt** — tùy chỉnh kích thước tem, số lượng dòng/cột trên 1 khổ giấy, đơn vị đo (mm/...), chọn phạm vi in (tất cả / tùy chọn).
- **Lưu / mở mẫu thiết kế** để tái sử dụng về sau.
- **Hoàn tác / Làm lại (Undo/Redo)** cho mọi thao tác chỉnh sửa.
- **In tem trực tiếp** từ trình duyệt, không cần phần mềm trung gian.
- Giao diện thích ứng tốt với **chế độ tối (dark mode)** của trình duyệt/hệ điều hành, kể cả với mã vạch và mã QR.

## 🚀 Bắt đầu sử dụng

Không cần cài đặt gì cả — chỉ cần mở trình duyệt và truy cập:

👉 **[ngthhung-dev.github.io/bartender-lite-web](https://ngthhung-dev.github.io/bartender-lite-web/)**

Hoặc chạy cục bộ: tải file `index.html` về máy rồi mở bằng trình duyệt bất kỳ (Chrome, Edge, Firefox...).

## 🛠️ Công nghệ sử dụng

Dự án là một file `index.html` duy nhất (không cần build, không cần server), sử dụng:

- HTML/CSS/JavaScript thuần
- [Tailwind CSS](https://tailwindcss.com/) — giao diện
- [JsBarcode](https://github.com/lindell/JsBarcode) — tạo mã vạch
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) — tạo mã QR
- [SheetJS (xlsx)](https://sheetjs.com/) — đọc file Excel/CSV
- [Font Awesome](https://fontawesome.com/) — icon

## 📄 Giấy phép

Miễn phí sử dụng cho mọi mục đích.
