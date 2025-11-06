# Hệ thống Quản lý Bệnh viện (Hospital Management System)
## 1. Các yếu tố môi trường ảnh hưởng đến hệ thống
### 1.1. Người dùng (Users)
Bao gồm bác sĩ, y tá, nhân viên hành chính, kế toán, bệnh nhân và quản lý bệnh viện.  
Họ có nhu cầu và mức độ sử dụng hệ thống khác nhau.
Tác động đến yêu cầu kỹ thuật:  
- Hệ thống cần có phân quyền truy cập rõ ràng cho từng loại người dùng.  
- Giao diện phải thân thiện và dễ dùng, đặc biệt cho nhân viên y tế ít am hiểu công nghệ.
### 1.2. Phần cứng (Hardware)
Máy chủ lưu trữ dữ liệu bệnh nhân, máy tính tại các khoa, thiết bị y tế kết nối mạng như máy đo huyết áp hoặc máy xét nghiệm.
Tác động đến yêu cầu kỹ thuật:  
- Cần đảm bảo khả năng xử lý dữ liệu lớn và kết nối ổn định giữa các thiết bị.  
- Hệ thống phải tương thích với thiết bị y tế và máy in hóa đơn hoặc toa thuốc.
### 1.3. Phần mềm (Software)
Bao gồm hệ điều hành, phần mềm quản lý cơ sở dữ liệu, ứng dụng web và mobile dành cho bệnh nhân và nhân viên.
Tác động đến yêu cầu kỹ thuật:  
- Cần đảm bảo tính tương thích đa nền tảng như Windows, Linux, Android, iOS.  
- Phải có bảo mật cao và cơ chế sao lưu dữ liệu tự động.
### 1.4. Hệ thống bên ngoài (External Systems)
Các hệ thống liên kết như bảo hiểm y tế, cổng thanh toán viện phí, cơ quan quản lý y tế quốc gia.
Tác động đến yêu cầu kỹ thuật:  
- Cần API kết nối an toàn để trao đổi thông tin bệnh nhân và thanh toán.  
- Đòi hỏi tuân thủ các tiêu chuẩn dữ liệu y tế như HL7 hoặc FHIR.
### 1.5. Quy trình nghiệp vụ (Business Processes)
Bao gồm quy trình tiếp nhận, khám bệnh, xét nghiệm, điều trị nội trú, kê đơn, thanh toán và xuất viện.
Tác động đến yêu cầu kỹ thuật:  
- Hệ thống phải hỗ trợ đầy đủ các quy trình y tế hiện hành.  
- Cần tích hợp tự động hóa như in toa thuốc, gửi kết quả xét nghiệm và thống kê bệnh nhân.
### 1.6. Luật lệ và quy định (Regulations)
Các quy định của Bộ Y tế, luật bảo vệ dữ liệu cá nhân và quy tắc lưu trữ hồ sơ bệnh án.
Tác động đến yêu cầu kỹ thuật:  
- Hệ thống phải tuân thủ quy định bảo mật thông tin bệnh nhân.  
- Cần có chức năng nhật ký truy cập (audit log) để theo dõi hoạt động của người dùng.  
- Dữ liệu phải được lưu trữ tối thiểu theo thời gian quy định của pháp luật.