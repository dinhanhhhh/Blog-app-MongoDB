# Blog‑app‑MongoDB

Blog-app-MongoDB là một ứng dụng blog đơn giản được xây dựng bằng MongoDB, Node.js và Express.js. Ứng dụng này cho phép người dùng tạo, quản lý bài viết, bình luận và tìm kiếm nội dung.

## 📖 Mục Lục

- [Giới Thiệu](#-giới-thiệu)  
- [Tính Năng](#-tính-năng)  
- [Cài Đặt](#-cài-đặt)  
- [Sử Dụng](#-sử-dụng)  
- [Cấu Trúc Thư Mục](#-cấu-trúc-thư-mục)  
- [Công Nghệ](#-công-nghệ)  
- [Đóng Góp](#-đóng-góp)  

## 📌 Giới Thiệu

Blog‑app‑MongoDB là một ứng dụng web mẫu cho phép:

- Tạo, đọc, sửa, xóa (CRUD) bài viết.  
- Hiển thị flash messages.  
- Hỗ trợ PUT/DELETE qua form với method-override.  

## 🚀 Tính Năng

Các tính năng chính
Quản lý bài viết: Tạo, đọc, cập nhật và xóa các bài viết blog.
Xác thực người dùng: Hỗ trợ đăng ký, đăng nhập và phân quyền.
Hệ thống bình luận: Người dùng có thể bình luận trên các bài viết.
Tìm kiếm: Tìm kiếm bài viết theo từ khóa.
## 💻 Cài Đặt
1. Clone repository:
   ```bash
   git clone https://github.com/dinhanhhhh/Blog-app-MongoDB.git
   cd Blog-app-MongoDB
2. Cài dependencies:
npm install

3. Tạo file .env ở gốc dự án:
MONGODB_URI=<Your MongoDB URI>
PORT=5000

4. Chạy ứng dụng:
npm start

5. Mở http://localhost:5000 trên trình duyệt.
   
🔍 Sử Dụng

Cách sử dụng

Đăng ký/Đăng nhập: Tạo tài khoản mới hoặc đăng nhập bằng tài khoản hiện có.

Quản lý bài viết: Tạo, chỉnh sửa hoặc xóa bài viết sau khi đăng nhập.

Bình luận: Thêm bình luận vào các bài viết.

Tìm kiếm: Sử dụng chức năng tìm kiếm để tìm bài viết theo từ khóa.

🛠️ Công Nghệ
Công nghệ sử dụng

Node.js: Nền tảng phía server.

Express.js: Framework web để xử lý các tuyến đường (routes) và yêu cầu HTTP.

MongoDB: Cơ sở dữ liệu NoSQL để lưu trữ dữ liệu.

Mongoose: Thư viện hỗ trợ tương tác với MongoDB.

JWT (JSON Web Token): Công cụ dùng để quản lý xác thực người dùng, cung cấp cách truyền thông tin an toàn giữa client và server.

Cấu trúc cơ sở dữ liệu
Dự án có sử dụng các schema MongoDB như sau:
-Post (Bài viết):
title: Tiêu đề bài viết (chuỗi).
content: Nội dung bài viết (chuỗi).
author: Tác giả (tham chiếu đến User).
createdAt: Ngày tạo (ngày giờ).
updatedAt: Ngày cập nhật (ngày giờ).
-User (Người dùng):
username: Tên đăng nhập (chuỗi).
password: Mật khẩu (chuỗi, mã hóa).
email: Địa chỉ email (chuỗi).

🤝 Đóng Góp
1. Fork repo này.
2. Tạo branch feature:
git checkout -b feature/TenTinhNang
3.Commit thay đổi:
git commit -m "Add TenTinhNang"
4.Push lên branch:
git push origin feature/TenTinhNang
5. Tạo Pull Request trên GitHub.
