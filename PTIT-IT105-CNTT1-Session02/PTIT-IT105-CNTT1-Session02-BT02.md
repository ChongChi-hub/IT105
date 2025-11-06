# Ứng dụng Ngân hàng Trực Tuyến (Mobile Banking App)

## Yêu cầu chức năng (Functional Requirements)
### 1. Đăng nhập và xác thực người dùng
- Người dùng có thể đăng nhập bằng tên đăng nhập, mật khẩu hoặc sinh trắc học (vân tay, khuôn mặt).
### 2. Chuyển khoản nội bộ và liên ngân hàng
- Cho phép người dùng chuyển tiền giữa các tài khoản trong cùng ngân hàng hoặc khác ngân hàng.
### 3. Tra cứu lịch sử giao dịch
- Người dùng có thể xem, lọc và tải lịch sử giao dịch trong khoảng thời gian tùy chọn.
## Yêu cầu phi chức năng (Non-functional Requirements)
### 1. Hiệu năng (Performance)
- Thời gian phản hồi cho mỗi giao dịch không vượt quá 3 giây.
### 2. Bảo mật (Security)
- Dữ liệu phải được mã hóa (SSL/TLS) khi truyền.
- Giao dịch yêu cầu xác thực hai lớp (OTP hoặc sinh trắc học).
### 3. Tính khả dụng (Usability & Availability)
- Giao diện thân thiện, dễ sử dụng trên mọi thiết bị.
- Hệ thống đạt 99,9% uptime, đảm bảo sẵn sàng phục vụ liên tục.