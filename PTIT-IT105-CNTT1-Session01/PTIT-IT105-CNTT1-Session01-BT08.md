## 1. Xác định các tác nhân chính và chức năng tương ứng
- Học viên: Đăng ký tài khoản, đăng ký khóa học, học bài, làm bài kiểm tra, xem điểm
- Giảng viên: Tạo khóa học, đăng bài học, chấm điểm, theo dõi tiến độ học viên
- Admin: Quản lý người dùng, thống kê báo cáo, phân quyền, theo dõi hệ thống
## 2. Phân loại hệ thống thông tin phù hợp
- Ghi nhận đăng ký, điểm, bài nộp => TPS (Xử lý giao dịch hằng ngày của người dùng)
- Báo cáo thống kê cho quản lý trung tâm => MIS (Tổng hợp dữ liệu và tạo báo cáo định kỳ)
- Phân tích kết quả học tập, gợi ý cải thiện => DSS (Hỗ trợ ra quyết định và đề xuất cải tiến đào tạo)
## 3. Mô hình phát triển phần mềm đề xuất
- Mô hình Agile (Scrum)
    - Dự án có nhiều tính năng thay đổi theo phản hồi người dùng.
    - Cần phát hành bản cập nhật thường xuyên (thêm khóa học, chỉnh sửa bài học).
    - Làm việc nhóm hiệu quả, dễ kiểm thử và cải thiện liên tục.
## 4. Ba sơ đồ UML sẽ sử dụng khi thiết kế hệ thống
- Use Case Diagram: Xác định tác nhân và chức năng hệ thống (ai làm gì)
- Class Diagram: Thiết kế các lớp chính (HọcVien, KhoaHoc, BaiHoc, GiangVien...) và quan hệ giữa chúng
- Activity Diagram: Mô tả luồng hoạt động: Học viên -> Đăng ký -> Học -> Làm bài -> Xem điểm