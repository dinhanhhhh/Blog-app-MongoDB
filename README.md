# Blog‑app‑MongoDB

> Ứng dụng Blog đơn giản sử dụng Node.js, Express, EJS và MongoDB- CRUD

## 📖 Mục Lục

- [Giới Thiệu](#-giới-thiệu)  
- [Tính Năng](#-tính-năng)  
- [Cài Đặt](#-cài-đặt)  
- [Sử Dụng](#-sử-dụng)  
- [Cấu Trúc Thư Mục](#-cấu-trúc-thư-mục)  
- [Công Nghệ](#-công-nghệ)  
- [Đóng Góp](#-đóng-góp)  
- [Giấy Phép](#-giấy-phép)  

## 📌 Giới Thiệu

Blog‑app‑MongoDB là một ứng dụng web mẫu cho phép:

- Tạo, đọc, sửa, xóa (CRUD) bài viết.  
- Hiển thị flash messages.  
- Hỗ trợ PUT/DELETE qua form với method-override.  

## 🚀 Tính Năng

- **CRUD Posts**  
- **Flash Messages** (success/error)  
- **Responsive** với CSS Grid/Flex  
- **Search** (nếu đã triển khai)  

## 💻 Cài Đặt

1. Clone repository:
   ```bash
   git clone https://github.com/dinhanhhhh/Blog-app-MongoDB.git
   cd Blog-app-MongoDB
2. Cài dependencies:
npm install
3.Tạo file .env ở gốc dự án:
MONGODB_URI=<Your MongoDB URI>
PORT=5000
4.Chạy ứng dụng:
npm start
5. Mở http://localhost:5000 trên trình duyệt.
🔍 Sử Dụng
Trang chủ: GET /

Tạo bài viết: GET /posts/new & POST /posts

Xem chi tiết: GET /posts/:id

Chỉnh sửa: GET /posts/:id/edit & PUT /posts/:id

Xóa: DELETE /posts/:id
🗂️ Cấu Trúc Thư Mục
Blog-app-MongoDB/
├─ .env
├─ .gitignore
├─ app.js
├─ package.json
├─ models/
│  └─ post.js
├─ routes/
│  ├─ index.js
│  └─ posts.js
├─ views/
│  ├─ partials/
│  │  ├─ header.ejs
│  │  └─ footer.ejs
│  ├─ index.ejs
│  ├─ new.ejs
│  ├─ show.ejs
│  └─ edit.ejs
└─ public/
   └─ css/
      └─ style.css
🛠️ Công Nghệ
Node.js
Express
EJS
MongoDB (Atlas / Local)
Mongoose
body-parser, method-override, express-session, connect-flash
🤝 Đóng Góp
1. Fork repo này.
2. Tạo branch feature:
git checkout -b feature/TenTinhNang
3.Commit thay đổi:
git commit -m "Add TenTinhNang"
4.Push lên branch:
git push origin feature/TenTinhNang
5. Tạo Pull Request trên GitHub.
