# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Trương Văn Ban

**MSSV:** 1871020070

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: thông tin người dùng (tên tài khoản, mật khẩu, email)
- Asset 2: source code của dự án lưu trên Github repository
- Asset 3 (nếu có):Project documentation và dữ liệu cấu hình hệ thống.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality (Thông tin người dùng bị lộ hoặc truy cập trái phép)
- Sự cố B -> Integrity (Dữ liệu hoặc source code bị thay đổi trái phép)
- Sự cố C -> Availability (Hệ thống hoặc repository không truy cập được)

---

## 3. Phân tích sự cố B
- Threat: Hacker hoặc người dùng không có quyền sửa đổi source code trong repository.
- Vulnerability:Repository không được cấu hình quyền truy cập đúng cách hoặc thiếu cơ chế kiểm soát thay đổi.
- Mitigation:Sử dụng access control, bật branch protection, kiểm tra pull request trước khi merge và sử dụng xác thực 2FA cho tài khoản GitHub.

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài lab này, em hiểu rõ hơn về mô hình CIA (Confidentiality, Integrity, Availability) trong an toàn thông tin. Mô hình này giúp xác định những rủi ro có thể xảy ra với hệ thống và cách bảo vệ các tài sản quan trọng. Việc phân tích các sự cố giúp em nhận ra rằng dữ liệu không chỉ cần được bảo mật mà còn phải đảm bảo tính toàn vẹn và khả năng truy cập. Ngoài ra, em cũng học được cách xác định threat, vulnerability và mitigation để giảm thiểu rủi ro. Kiến thức này rất hữu ích khi phát triển và quản lý hệ thống phần mềm trong thực tế.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:

