# Quản trị năng suất kênh - VNPT Tây Ninh

Web app xem năng suất kênh: theo tháng, nhóm kênh, tìm nhân viên, kết quả từng dịch vụ và đánh giá chung.
Là trang tĩnh (một file `index.html`), không cần cài đặt hay máy chủ.

## Cách đưa lên GitHub Pages
1. Vào github.com, bấm **New repository**, đặt tên (ví dụ `nang-suat-kenh`). Nên chọn **Private** vì có dữ liệu từng nhân viên.
2. Bấm **uploading an existing file**, kéo thả toàn bộ file trong thư mục này (gồm `index.html`, `.nojekyll`, `assets`), bấm **Commit changes**.
3. Vào **Settings > Pages**, mục Source chọn **Deploy from a branch**, Branch chọn `main`, thư mục `/ (root)`, bấm **Save**.
4. Chờ 1-2 phút, link có dạng `https://TEN-TAI-KHOAN.github.io/nang-suat-kenh/`.

Lưu ý: Pages của repo Private cần gói GitHub trả phí; repo Public thì ai có link cũng xem được dữ liệu.

## Chạy trực tiếp trên máy
Nhấp đúp `index.html`.

## Logo VNPT
Chép file logo vào `assets/logo.png`, trang tự hiện.

## Cập nhật số liệu
Gửi File đánh giá mới cho Claude để tạo lại `index.html`, rồi tải đè lên repository.
