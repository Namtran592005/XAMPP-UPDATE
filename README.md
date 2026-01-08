# XAMPP Custom 4.0.0 – Revived Edition

---

## 🇬🇧 English

### Overview

**XAMPP Custom 4.0.0** is an unofficial, community-driven upgrade of XAMPP for Windows.

XAMPP has effectively stopped active development, while modern web applications (WordPress, Laravel, frameworks, browsers) continue to evolve rapidly. This project exists to **extend the usable life of XAMPP** by upgrading its core components to modern, secure, and supported versions — while keeping the familiar XAMPP structure.

This is **not a fork maintained by Apache Friends**.
It is a **technical resurrection** for developers who still rely on XAMPP.

---

### Included Components

| Component | Version |
|--------|--------|
| Apache HTTP Server | **2.4.66** |
| PHP | **8.5.1** |
| MariaDB | **12.1.2** |
| phpMyAdmin | **5.2.3** |

All components are:
- Windows x64
- Modern TLS / OpenSSL compatible
- Tested to work together

---

### Why This Project Exists

- XAMPP official releases lag behind modern PHP and database versions
- Security updates are critical (TLS, OpenSSL, CVE fixes)
- Many developers still prefer XAMPP for:
  - Local development
  - Teaching / training
  - Offline environments
  - Portable setups

This project:
- Keeps XAMPP usable
- Avoids Docker complexity
- Preserves classic workflow

---

### Design Principles

- **Minimal changes** to original XAMPP structure
- **No vendor lock-in**
- **No Docker, no virtualization**
- Transparent configuration
- Manual upgrade-friendly

---

### Intended Audience

- Developers maintaining legacy XAMPP projects
- WordPress developers on Windows
- Educators / students
- Power users who understand local server stacks

⚠️ **Not recommended for production environments**

---

### Disclaimer

This project:
- Is **unofficial**
- Is **not affiliated** with Apache Friends
- Comes **without warranty**

Use at your own risk.

---

### Status

✅ Stable for local development
🛠 Actively maintained by the community

---

### Setup Extras Included

To reduce common setup errors and save time, this repository **already includes essential supporting files** in the `setup/` directory:

- **`VC_redist.x64.exe`**  
  Microsoft Visual C++ Redistributable (2015–2022, x64).  
  Required for Apache, PHP, ImageMagick, and several native extensions to run correctly on Windows.

- **`server.crt`**  
  A ready-to-use self-signed SSL certificate for local HTTPS development.  
  Useful for WordPress, REST API, cURL, and modern browser testing.

These files are provided so users:
- Do not encounter missing VC++ runtime errors
- Can enable HTTPS immediately if needed

⚠️ The included certificate is intended for **local development only**, not for production use.

---

## 🇻🇳 Tiếng Việt

### Trạng thái

✅ Ổn định cho môi trường local
🛠 Đang được duy trì bởi cộng đồng

---

### Các tệp hỗ trợ đã được chuẩn bị sẵn

Để giảm lỗi khi cài đặt và giúp mọi người sử dụng nhanh hơn, repo này **đã chuẩn bị sẵn các tệp cần thiết** trong thư mục `setup/`:

- **`VC_redist.x64.exe`**  
  Microsoft Visual C++ Redistributable (2015–2022, x64).  
  Bắt buộc cho Apache, PHP, ImageMagick và nhiều extension native khác hoạt động đúng trên Windows.

- **`server.crt`**  
  Chứng chỉ SSL self-signed dùng sẵn cho HTTPS local.  
  Phù hợp cho WordPress, REST API, cURL và test trên trình duyệt hiện đại.

Việc chuẩn bị sẵn các tệp này giúp:
- Tránh lỗi thiếu VC++ Runtime
- Có thể bật HTTPS ngay khi cần

⚠️ Chứng chỉ đi kèm **chỉ dùng cho môi trường local**, không dùng cho production.
