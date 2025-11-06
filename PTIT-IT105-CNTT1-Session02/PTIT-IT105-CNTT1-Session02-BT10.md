# Báo cáo phân tích hệ thống: Hệ thống Quản lý Tuyển dụng (Recruitment Management System)
## 1. Các yếu tố môi trường hệ thống
### 1.1. Người dùng
- Ứng viên: nộp hồ sơ, theo dõi trạng thái tuyển dụng.
- Nhân sự (HR): đăng tin tuyển dụng, lọc hồ sơ, sắp xếp phỏng vấn.
- Quản lý bộ phận: phê duyệt nhu cầu tuyển dụng, đánh giá ứng viên.
- Quản trị hệ thống: quản lý tài khoản, phân quyền, sao lưu dữ liệu.
### 1.2. Phần cứng
- Máy chủ lưu trữ ứng dụng và cơ sở dữ liệu.
- Máy tính, laptop, thiết bị di động của người dùng.
- Thiết bị mạng và hệ thống sao lưu (backup).
### 1.3. Phần mềm
- Ứng dụng web hoặc mobile quản lý tuyển dụng.
- Hệ quản trị cơ sở dữ liệu (MySQL, PostgreSQL...).
- Hệ điều hành máy chủ (Linux/Windows Server).
### 1.4. Hệ thống bên ngoài
- Email server để gửi thông báo.
- Cổng xác minh hồ sơ (LinkedIn, cổng việc làm).
- Cổng thanh toán hoặc nền tảng quảng cáo tuyển dụng (VietnamWorks, TopCV...).
### 1.5. Quy trình nghiệp vụ
- Đăng nhu cầu tuyển dụng → Đăng tin → Tiếp nhận hồ sơ → Lọc ứng viên → Phỏng vấn → Ra quyết định tuyển dụng → Lưu trữ dữ liệu.
### 1.6. Luật lệ và quy định
- Quy định bảo mật thông tin cá nhân (Nghị định 13/2023/NĐ-CP).
- Chính sách lao động, hợp đồng và lưu trữ hồ sơ nhân sự.
## 2. Phân tích Stakeholders
| Stakeholder | Vai trò | Mối quan tâm | Mức độ ưu tiên |
|--------------|----------|--------------|----------------|
| Ứng viên | Người nộp hồ sơ | Giao diện dễ dùng, thông tin tuyển dụng rõ ràng, phản hồi nhanh | Critical |
| Nhân viên HR | Quản lý tuyển dụng | Dễ dàng đăng tin, lọc ứng viên, theo dõi tiến độ | Critical |
| Quản lý bộ phận | Xét duyệt và phỏng vấn | Có báo cáo chi tiết, truy cập thông tin ứng viên nhanh | Major |
| Quản trị hệ thống | Duy trì hệ thống | Ổn định, bảo mật, dễ bảo trì | Major |
| Ban giám đốc | Ra quyết định chiến lược | Báo cáo thống kê hiệu quả tuyển dụng | Minor |
## 3. Các nguồn yêu cầu
- Phỏng vấn nhân viên HR và quản lý bộ phận.
- Khảo sát người dùng (ứng viên) qua biểu mẫu trực tuyến.
- Phân tích quy trình tuyển dụng hiện có của công ty.
- Tham khảo tài liệu hệ thống nhân sự (HRM) hiện hành.
## 4. Một số yêu cầu chức năng & phi chức năng
### 4.1. Yêu cầu chức năng
1. Đăng và quản lý tin tuyển dụng.  
2. Tiếp nhận và lưu trữ hồ sơ ứng viên trực tuyến.  
3. Tìm kiếm, lọc và sắp xếp ứng viên theo tiêu chí.  
4. Quản lý lịch phỏng vấn và phản hồi kết quả cho ứng viên.  
5. Xuất báo cáo thống kê tuyển dụng (số lượng ứng viên, nguồn ứng viên, tỉ lệ tuyển thành công...).
### 4.2. Yêu cầu phi chức năng
1. Bảo mật: dữ liệu ứng viên và tài khoản HR phải được mã hóa.  
2. Hiệu năng: phản hồi tìm kiếm và tải dữ liệu dưới 3 giây.  
3. Khả năng mở rộng: hỗ trợ tối thiểu 5000 tài khoản ứng viên đồng thời.  
4. Tính khả dụng: hệ thống hoạt động 24/7 với uptime ≥ 99.5%.
## 5. Gợi ý cấu trúc tài liệu mô tả yêu cầu (SRS)
1. Giới thiệu  
   - Mục đích, phạm vi, đối tượng sử dụng, định nghĩa thuật ngữ.  
2. Mô tả tổng quan hệ thống  
   - Bối cảnh, môi trường, ràng buộc và giả định.  
3. Yêu cầu chức năng  
   - Mô tả chi tiết từng chức năng, use case, luồng xử lý.  
4. Yêu cầu phi chức năng  
   - Hiệu năng, bảo mật, tính sẵn sàng, khả năng mở rộng, giao diện.  
5. Giao diện người dùng  
   - Bố cục, mô tả màn hình, sơ đồ điều hướng.  
6. Giao diện hệ thống  
   - Liên kết API, tích hợp email, hoặc hệ thống khác.  
7. Phụ lục  
   - Sơ đồ use case, từ điển dữ liệu, tài liệu tham khảo.