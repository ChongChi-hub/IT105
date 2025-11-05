## 1. Xác định các tác nhân chính và chức năng tương ứng
- Khách hàng -> Tạo đơn hàng, theo dõi trạng thái giao hàng, xác nhận đã nhận hàng  
- Nhân viên giao hàng -> Cập nhật trạng thái đơn (đang giao, giao thành công, giao thất bại), ghi chú lý do  
- Quản lý -> Theo dõi hiệu suất giao hàng, khu vực tồn đọng, xuất báo cáo  
- CEO -> Xem tổng quan giao dịch, vùng hoạt động, tỉ lệ giao đúng hẹn
## 2. Phân loại hệ thống thông tin phù hợp
- Tạo đơn hàng, cập nhật trạng thái giao hàng -> TPS (Xử lý giao dịch hằng ngày)  
- Theo dõi, báo cáo hiệu suất giao hàng -> MIS (Tổng hợp dữ liệu và báo cáo định kỳ)  
- Phân tích tuyến đường, tối ưu hiệu suất giao hàng -> DSS (Hỗ trợ ra quyết định)  
- Tổng hợp thông tin điều hành cho CEO -> EIS (Cung cấp thông tin tổng hợp cấp cao)
## 3. Mô hình phát triển phần mềm đề xuất
- Mô hình Spiral (Xoắn ốc)  
    - Hệ thống có độ phức tạp và rủi ro cao về bảo mật, dữ liệu lớn.  
    - Cho phép đánh giá, kiểm thử và cải tiến sau mỗi vòng lặp.  
    - Phù hợp với dự án cần kiểm soát rủi ro và nâng cấp định kỳ.   
## 4. Bốn sơ đồ UML sẽ sử dụng khi thiết kế hệ thống
- Use Case Diagram -> Xác định tác nhân và chức năng chính của hệ thống  
- Class Diagram -> Thiết kế các lớp như DonHang, KhachHang, NhanVien, BaoCao và mối quan hệ giữa chúng  
- Activity Diagram -> Mô tả quy trình xử lý: Tạo đơn -> Giao hàng -> Hoàn tất  
- Sequence Diagram -> Minh họa thứ tự tương tác khi cập nhật trạng thái giao hàng giữa người dùng và hệ thống
