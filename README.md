# 🐳 Docker Web Demo

Dự án nhỏ này được thực hiện nhằm mục đích báo cáo giữa kỳ, minh họa cách ứng dụng **Docker** để đóng gói một ứng dụng Web tĩnh sử dụng Nginx.

## 📌 Thông tin sinh viên
- **Họ và tên:** Lê Đức Anh
- **MSSV:** 49.01.104.002
- **Định hướng:** Junior DevOps / AI Engineer

## ⚙️ Kiến trúc hoạt động
- **Base Image:** `nginx:alpine` (Siêu nhẹ, tối ưu tài nguyên).
- Ứng dụng sẽ thay thế trang mặc định của Nginx bằng file `index.html` tự thiết kế.
- Publish port `8080` ở máy host và map vào port `80` của container.

## 🚀 Hướng dẫn chạy dự án (Run locally)

**Yêu cầu:** Máy tính đã cài đặt Docker.

1. Clone repository này về máy:
   ```bash
   git clone [https://github.com/Supzxjee/git-lab.git](https://github.com/Supzxjee/git-lab.git)
   cd git-lab/docker-demo
