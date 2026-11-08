# Hương Vị Sóc Trăng

Website giới thiệu ẩm thực Sóc Trăng, có khu vực thành viên để đăng, sửa và xóa bài viết.

## Chạy trên máy tính Windows

1. Cài Python 3.
2. Giải nén toàn bộ dự án.
3. Chạy `BAT_DAU_WEBSITE.bat`.
4. Mở trình duyệt tại http://127.0.0.1:8000.
5. Lần chạy đầu, xem tệp `THONG_TIN_TAI_KHOAN.txt` được tạo ngay trong thư mục để nhận 6 tài khoản tạm. Gửi riêng thông tin cho từng thành viên và đổi mật khẩu sau khi đăng nhập.

Dữ liệu bài viết và tài khoản được lưu trong `website_data.sqlite3` trên máy chạy máy chủ.

## Lưu ý quan trọng

- Đây là ứng dụng Python chạy cục bộ, **không phải website có thể triển khai trực tiếp bằng GitHub Pages**.
- Repository chỉ chứa mã nguồn. Cơ sở dữ liệu, mật khẩu và tệp tài khoản không được đưa lên GitHub.
- Không mở cổng Internet hoặc tạo public tunnel tới máy chủ này. Máy chủ mặc định chỉ lắng nghe trên `127.0.0.1`.
- Nếu muốn đưa website lên Internet, cần triển khai backend trên dịch vụ hosting phù hợp và bổ sung HTTPS, giới hạn đăng nhập, chống CSRF và các biện pháp bảo mật khác trước khi dùng thật.
- Mọi thành viên hiện có quyền sửa/xóa bài viết; chỉ dùng với nhóm tin cậy.
