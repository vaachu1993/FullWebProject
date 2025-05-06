# 🌾 Website Ẩm Thực Ba Miền – THE FOODS
## 👥 Thành viên thực hiện

| Họ và Tên          | MSSV       | Vai trò                         |
|--------------------|------------|----------------------------------|
| Nguyễn Hoàng Minh Trí | 2280603364 | Backend & Frontend(40%) | 
| Trần Hoài Nam | 2280602037 | Frontend(40%) | 
| Nguyễn Thành Đô | 2280606483 | Report(20%) | 

## 🏗️ Công nghệ sử dụng

### Backend:
- ASP.NET Core 8 Web API
- Entity Framework Core (Code-First)
- ASP.NET Core Identity (JWT Authentication)

### Frontend:
- ReactJS
- Bootstrap + React Icons
- CKEditor 5 (Editor nội dung bài viết)


### Database:
- SQL Server

---

## ⚙️ Các tính năng chính

### 🧑‍🍳 Cho người dùng:
- Xem bài viết món ăn theo vùng miền
- Xem chi tiết bài viết kèm ảnh, nguyên liệu, video hướng dẫn
- Tìm kiếm món ăn theo tên
- Bình luận, trả lời, like/dislike bình luận
- Đăng ký, đăng nhập (JWT)
- Viết bài: CKEditor hỗ trợ hình ảnh + gắn tag + chọn vùng miền
- Lưu bài nháp và chỉnh sửa
- Trang cá nhân với danh sách bài viết (duyệt, chờ, nháp)

### 🛠️ Cho Admin:
- Duyệt bài viết người dùng đăng
- Quản lý vùng miền, tag
- Quản lý bình luận
- Quản lý người dùng

---

## 📊 Cơ sở dữ liệu

- Bao gồm các bảng:
  - `Posts`, `Comments`, `Tags`, `Regions`, `AspNetUsers`, `CommentReactions`, `PostTags`, …
- Sử dụng Identity mặc định, có phân quyền Admin/User

## ✅ Hướng dẫn chạy project
Chạy Backend(WebAmThucDoAnCoSo):
dotnet ef database update

Chạy Frontend(fereactjs):
npm install
npm start




