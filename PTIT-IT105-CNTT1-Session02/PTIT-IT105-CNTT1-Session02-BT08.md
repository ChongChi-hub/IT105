# Quy trình: Mua hàng online
## Mô tả ngắn
Người dùng truy cập website hoặc ứng dụng mua sắm, tìm kiếm sản phẩm mong muốn, thêm vào giỏ hàng, thanh toán trực tuyến và nhận hàng tại địa chỉ đã đăng ký.
## Yêu cầu chức năng (Functional Requirements)
1. Tìm kiếm và xem thông tin sản phẩm  
   - Hệ thống cho phép người dùng tìm kiếm theo tên, danh mục hoặc giá sản phẩm.
2. Thêm sản phẩm vào giỏ hàng  
   - Người dùng có thể thêm, chỉnh sửa số lượng hoặc xóa sản phẩm trong giỏ hàng.
3. Thanh toán và xác nhận đơn hàng  
   - Hệ thống hỗ trợ nhiều phương thức thanh toán (thẻ, ví điện tử, COD).  
   - Sau khi thanh toán, hệ thống gửi xác nhận đơn hàng qua email hoặc tin nhắn.
4. Theo dõi trạng thái giao hàng  
   - Người dùng có thể xem trạng thái đơn hàng: chờ xử lý, đang giao, hoặc đã nhận.
## Yêu cầu phi chức năng (Non-functional Requirements)
1. Hiệu năng (Performance)  
   - Thời gian tải trang và phản hồi không quá 3 giây trong điều kiện bình thường.
2. Bảo mật (Security)  
   - Dữ liệu cá nhân và thông tin thanh toán phải được mã hóa và bảo vệ khỏi truy cập trái phép.
3. Khả năng mở rộng (Scalability)  
   - Hệ thống có thể phục vụ tối thiểu 10.000 người dùng đồng thời trong các dịp khuyến mãi lớn.