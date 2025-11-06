# Báo cáo tư vấn ban đầu: Hệ thống Quản lý Trung tâm Đào tạo Ngoại ngữ
## 1. Phân tích môi trường hệ thống
### 1.1. Bối cảnh
Trung tâm đào tạo ngoại ngữ hiện quản lý học viên, lịch học, giảng viên và học phí chủ yếu bằng file Excel và trao đổi qua email.  
Điều này dẫn đến sai sót dữ liệu, khó theo dõi tiến độ học tập và mất nhiều thời gian xử lý hồ sơ.
### 1.2. Môi trường hoạt động
- Người dùng: học viên, giảng viên, nhân viên hành chính, kế toán, quản lý trung tâm.  
- Phần cứng: máy tính văn phòng, máy chủ lưu trữ dữ liệu, thiết bị di động của người dùng.  
- Phần mềm: hệ điều hành, trình duyệt web, hệ thống cơ sở dữ liệu.  
- Hệ thống bên ngoài: cổng thanh toán học phí online (VNPay, Momo), hệ thống gửi email thông báo.  
- Quy trình nghiệp vụ: đăng ký học → xếp lớp → điểm danh → thanh toán → cấp chứng chỉ.  
- Luật lệ: quy định về bảo mật thông tin cá nhân và lưu trữ dữ liệu học viên.
## 2. Xác định Stakeholders
| Stakeholder | Vai trò | Mối quan tâm | Mức độ ưu tiên |
|--------------|----------|--------------|----------------|
| Học viên | Người sử dụng hệ thống để đăng ký và theo dõi khóa học | Dễ sử dụng, xem lịch học, thanh toán thuận tiện | Critical |
| Giảng viên | Quản lý lớp học, điểm danh, nhập điểm | Giao diện thân thiện, dễ truy cập tài liệu và nhập điểm | Major |
| Nhân viên hành chính | Quản lý học viên, lớp học, lịch học | Dễ tìm kiếm, quản lý và báo cáo dữ liệu | Critical |
| Quản lý trung tâm | Theo dõi tình hình hoạt động, báo cáo tài chính và chất lượng giảng dạy | Có dashboard, biểu đồ thống kê, báo cáo tổng hợp | Major |
| Bộ phận IT | Phát triển và bảo trì hệ thống | Dễ mở rộng, dễ sao lưu, bảo mật cao | Minor |
## 3. Xác định nguồn yêu cầu và kỹ thuật thu thập
### 3.1. Nguồn yêu cầu
- Phỏng vấn nhân viên hành chính và giảng viên.  
- Khảo sát học viên về trải nghiệm đăng ký khóa học hiện tại.  
- Phân tích quy trình nội bộ hiện hành.  
- Tham khảo tài liệu và hệ thống cũ của trung tâm.
### 3.2. Kỹ thuật thu thập
- Phỏng vấn bán cấu trúc (semi-structured interview).  
- Quan sát trực tiếp quy trình nhập dữ liệu và quản lý lớp học.  
- Phát phiếu khảo sát (online survey).  
- Phân tích tài liệu nội bộ (mẫu đăng ký, sổ điểm, hóa đơn học phí).
## 4. Phân loại yêu cầu chức năng và phi chức năng
### 4.1. Yêu cầu chức năng
1. Quản lý hồ sơ học viên (thêm, sửa, tra cứu, xuất danh sách).  
2. Quản lý khóa học và lịch học.  
3. Điểm danh và nhập điểm học viên.  
4. Quản lý thanh toán học phí và in hóa đơn.  
5. Gửi thông báo tự động qua email hoặc SMS.
### 4.2. Yêu cầu phi chức năng
1. Hiệu năng: thời gian phản hồi dưới 3 giây khi tải danh sách học viên.  
2. Bảo mật: dữ liệu học viên được mã hóa và phân quyền truy cập rõ ràng.  
3. Khả năng mở rộng: hỗ trợ tối thiểu 5000 học viên và 100 giảng viên đồng thời.  
4. Tính khả dụng: hoạt động ổn định 24/7 với downtime không quá 1%.  
## 5. Gợi ý cấu trúc tài liệu mô tả yêu cầu (SRS)
1. Giới thiệu  
   - Mục đích, phạm vi, định nghĩa thuật ngữ.  
2. Mô tả tổng quan hệ thống  
   - Bối cảnh, môi trường, ràng buộc và giả định.  
3. Yêu cầu chức năng  
   - Mô tả chi tiết từng chức năng, use case, sơ đồ luồng dữ liệu.  
4. Yêu cầu phi chức năng  
   - Hiệu năng, bảo mật, khả năng mở rộng, giao diện.  
5. Giao diện người dùng  
   - Mô tả màn hình chính, bố cục, sơ đồ điều hướng.  
6. Giao diện hệ thống  
   - Mô tả API kết nối với cổng thanh toán, email.  
7. Phụ lục  
   - Sơ đồ use case, từ điển dữ liệu, tài liệu tham khảo.