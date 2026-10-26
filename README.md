# Ghép Hàng Nhanh – Website Phát hành 1

Website tĩnh (HTML/CSS/JS thuần), không cần build.

- `index.html`: toàn bộ trang, gồm máy tính cước (công thức từ file Excel của GHN).
- `img/`: logo, ảnh chuyến hàng, ảnh văn phòng, video.

## Chạy thử
Mở `index.html` bằng trình duyệt, hoặc `python3 -m http.server` rồi vào http://localhost:8000.

## Đăng lên GitHub Pages
1. Tạo repo mới trên GitHub, tải toàn bộ thư mục này lên (giữ `index.html` ở thư mục gốc).
2. Vào Settings > Pages > Source: Deploy from a branch > nhánh `main`, thư mục `/ (root)`.
3. Sau 1–2 phút trang chạy tại `https://<tài-khoản>.github.io/<tên-repo>/`.

## Lưu ý
- Giá dầu tham chiếu nằm trong `index.html` (biến `OIL`, đang 32000 đ/lít); bảng xe là mảng `V`.
- Đăng nhập, tra cứu đơn, bảng đơn cần xe hiện là dữ liệu mẫu; chưa có máy chủ.
- Ảnh có người: xác nhận đồng ý của nhân viên trước khi công khai.
