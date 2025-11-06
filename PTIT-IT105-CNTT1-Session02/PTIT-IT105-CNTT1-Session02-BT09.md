# Quy trình: Đặt vé máy bay
## Mô tả ngắn
Người dùng truy cập vào hệ thống đặt vé (website hoặc ứng dụng), tìm chuyến bay theo điểm đi và điểm đến, chọn lịch trình phù hợp, nhập thông tin hành khách, thanh toán và nhận vé điện tử qua email.
## Yêu cầu chức năng (Functional Requirements)
1. Tìm kiếm chuyến bay  
   - Hệ thống cho phép người dùng nhập điểm đi, điểm đến, ngày khởi hành và lọc theo hãng bay, giá hoặc thời gian.
2. Đặt chỗ và nhập thông tin hành khách  
   - Người dùng có thể chọn chuyến bay, nhập thông tin cá nhân và chọn chỗ ngồi nếu có hỗ trợ.
3. Thanh toán và xác nhận vé  
   - Hệ thống hỗ trợ thanh toán trực tuyến qua thẻ, ví điện tử hoặc cổng thanh toán trung gian.  
   - Sau khi thanh toán, hệ thống gửi mã đặt vé và hóa đơn điện tử qua email.
4. Tra cứu và hủy đặt vé  
   - Người dùng có thể đăng nhập để xem lịch sử đặt vé hoặc yêu cầu hủy/chuyển đổi chuyến bay.
## Yêu cầu phi chức năng (Non-functional Requirements)
1. Hiệu năng (Performance)  
   - Thời gian phản hồi khi tìm kiếm chuyến bay không vượt quá 5 giây.
2. Bảo mật (Security)  
   - Hệ thống phải mã hóa thông tin cá nhân và thanh toán của khách hàng bằng giao thức SSL/TLS.
3. Tính sẵn sàng (Availability)  
   - Hệ thống cần đảm bảo hoạt động 24/7 với độ tin cậy tối thiểu 99,9%.