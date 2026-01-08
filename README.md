# XAMPP Custom 4.0.0 – Revived Edition

---
## English

### Overview

**XAMPP Custom 4.0.0** is an unofficial, community-driven upgrade of XAMPP for Windows.

As official XAMPP development has slowed, modern web standards (PHP 8.5+, MariaDB 12+, modern TLS) continue to advance. This project serves as a **technical resurrection**, upgrading core components to their latest stable versions while preserving the classic XAMPP experience.

### 🚀 Truly Portable

This version is designed to be **fully portable**. You can carry your entire development environment on a USB drive or move it between folders without losing configurations or data. No installation, no registry mess—just plug and play.

### Included Components

|**Component**|**Version**|**Details**|
|---|---|---|
|**Apache HTTP Server**|**2.4.66**|x64, OpenSSL 3+|
|**PHP**|**8.5.1**|Latest stable engine|
|**MariaDB**|**12.1.2**|High-performance DB|
|**phpMyAdmin**|**5.2.3**|Web interface|

---

### Why Use This Version?

- **Modern Standards:** Supports the latest PHP features and security protocols.
    
- **Zero Complexity:** No Docker or virtualization required; just the familiar XAMPP workflow.
    
- **Ready for HTTPS:** Includes a pre-configured self-signed SSL certificate for local testing.
    
- **Legacy Support:** Perfect for developers maintaining older projects that need a performance boost.
    

### Included Setup Extras

To ensure a smooth "out-of-the-box" experience, the `setup/` directory includes:

- **`VC_redist.x64.exe`**: Essential Microsoft C++ runtimes to prevent "missing DLL" errors.
    
- **`server.crt`**: A ready-to-use SSL certificate for local HTTPS development.
    

> ⚠️ **Warning:** Not recommended for production environments. Use for local development only.

---

## Tiếng Việt

### Tổng quan

**XAMPP Custom 4.0.0** là phiên bản nâng cấp không chính thức, được duy trì bởi cộng đồng dành cho người dùng Windows.

Trong khi phiên bản XAMPP chính thức đã dừng phát triển tích cực, các ứng dụng web hiện đại (WordPress, Laravel) vẫn liên tục tiến hóa. Dự án này giúp **kéo dài vòng đời của XAMPP** bằng cách cập nhật các thành phần cốt lõi lên phiên bản mới nhất, bảo mật nhất mà vẫn giữ nguyên cấu trúc quen thuộc.

### 🚀 Khả năng Portable (Di động) tuyệt vời

Điểm mạnh nhất của phiên bản này là tính **Portable hoàn toàn**. Bạn có thể sao chép toàn bộ thư mục vào USB hoặc ổ cứng di động và mang đi làm việc ở bất cứ đâu. Không cần cài đặt rườm rà vào hệ thống, không làm rác Registry của Windows—chỉ cần giải nén và chạy.

### Các thành phần chính

|**Thành phần**|**Phiên bản**|**Chi tiết**|
|---|---|---|
|**Apache HTTP Server**|**2.4.66**|Windows x64|
|**PHP**|**8.5.1**|Động cơ PHP mới nhất|
|**MariaDB**|**12.1.2**|Cơ sở dữ liệu hiện đại|
|**phpMyAdmin**|**5.2.3**|Quản lý DB trực quan|

---

### Tại sao nên dùng bản này?

- **Cập nhật bảo mật:** Tương thích TLS/OpenSSL mới nhất, sửa các lỗi CVE quan trọng.
    
- **Đơn giản:** Tránh được sự phức tạp của Docker hay máy ảo; giữ nguyên cách làm việc truyền thống.
    
- **Hỗ trợ HTTPS:** Chuẩn bị sẵn chứng chỉ SSL để test các tính năng yêu cầu bảo mật như WordPress hay REST API.
    
- **Dành cho mọi người:** Từ lập trình viên chuyên nghiệp đến các bạn sinh viên đang học tập.
    

### Các tệp hỗ trợ đi kèm

Trong thư mục `setup/`, chúng tôi đã chuẩn bị sẵn:

- **`VC_redist.x64.exe`**: Microsoft Visual C++ Redistributable, giúp tránh lỗi thiếu file hệ thống khi chạy Apache/PHP.
    
- **`server.crt`**: Chứng chỉ SSL self-signed để bật HTTPS ngay lập tức.
    

> ⚠️ **Lưu ý:** Chỉ sử dụng cho môi trường phát triển (Local Development), không dùng cho môi trường thực tế (Production).
