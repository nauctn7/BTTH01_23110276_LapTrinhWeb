# Bài thực hành 01 – Lập trình Web

Họ tên: Cáp Thanh Nhàn
MSSV: 23110276

# 📖 Giới thiệu

Đây là bài thực hành số 01 của môn Lập trình Web, triển khai ứng dụng Java Servlet/JSP để thực hiện chức năng đăng nhập, quản lý phiên làm việc (Session) và đăng xuất.

# ✨ Nội dung chính

Login.html: Form đăng nhập (POST /login)

LoginServlet: Xử lý đăng nhập, tạo session, chuyển hướng đến profile

Profile: Trang hiển thị thông tin người dùng từ session; nếu chưa đăng nhập thì quay về login

Logout: Huỷ session và trở lại trang login

Cấu hình dự án bằng Maven với dependency Jakarta Servlet API 6.1.0
