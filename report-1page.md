# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- User account information (username, password, email).
- Source code của dự án lưu trên GitHub repository.

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Người dùng hoặc hacker thay đổi source code trái phép.
- Vulnerability: Hệ thống không kiểm soát quyền truy cập hoặc không kiểm tra thay đổi trước khi cập nhật code.
- Mitigation: Thiết lập quyền truy cập hợp lý, sử dụng pull request để kiểm tra code và bật xác thực hai lớp (2FA).

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn về mô hình CIA (Confidentiality, Integrity, Availability) trong an toàn thông tin. Việc phân tích các sự cố giúp xác định được loại rủi ro mà hệ thống có thể gặp phải. Em cũng học được cách xác định threat, vulnerability và mitigation để giảm thiểu rủi ro. Phần khó nhất là phân biệt chính xác giữa ba yếu tố của CIA. Khi phân tích một sự cố an toàn thông tin, cần chú ý xác định đúng tài sản cần bảo vệ và nguyên nhân gây ra lỗ hổng.