## 1. Xác định các tác nhân chính và chức năng tương ứng
- Khách hàng: Tạo đơn hàng, theo dõi trạng thái giao hàng, xác nhận đã nhận hàng.  
- Nhân viên giao hàng: Cập nhật trạng thái đơn (đang giao, giao thành công, giao thất bại), ghi chú lý do.  
- Quản lý: Theo dõi hiệu suất giao hàng, khu vực tồn đọng, xuất báo cáo.  
- CEO: Xem tổng quan tình hình kinh doanh, vùng hoạt động, tỷ lệ giao đúng hẹn.
## 2. Phân loại hệ thống thông tin phù hợp
- Xử lý tạo đơn, cập nhật trạng thái giao hàng -> TPS (Transaction Processing System – xử lý giao dịch hằng ngày).  
- Theo dõi, báo cáo hiệu suất cho quản lý -> MIS (Management Information System – tổng hợp báo cáo định kỳ).  
- Phân tích vùng giao hàng chậm, tối ưu tuyến đường -> DSS (Decision Support System – hỗ trợ ra quyết định).  
- Cung cấp bảng điều khiển cho CEO -> EIS (Executive Information System – thông tin tổng hợp cấp cao).
## 3. Mô hình phát triển phần mềm đề xuất
- Mô hình Spiral (Xoắn ốc):
    - Hệ thống phức tạp, nhiều rủi ro về bảo mật, độ tin cậy và quy mô dữ liệu lớn.  
    - Cần kết hợp giữa phân tích rủi ro, thử nghiệm và cải tiến liên tục.  
    - Thích hợp với hệ thống yêu cầu an toàn và chính xác cao trong từng vòng phát triển.
## 4. Bốn sơ đồ UML sẽ sử dụng khi thiết kế hệ thống
- Use Case Diagram: Xác định các tác nhân (khách hàng, nhân viên, quản lý, CEO) và chức năng chính.  
- Class Diagram: Thiết kế các lớp như DonHang, KhachHang, NhanVien, GiaoHang, BaoCao và mối quan hệ giữa chúng.  
- Activity Diagram: Mô tả quy trình giao hàng: Tạo đơn -> Nhận đơn -> Giao hàng -> Hoàn tất.  
- Sequence Diagram: Minh họa trình tự tương tác khi cập nhật trạng thái giao hàng giữa các thành phần hệ thống.
