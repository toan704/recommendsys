# The MovieGEEK - Hướng dẫn cài đặt
CÀI ĐẶT DOCKER
### Tải về mã nguồn đã được tinh chỉnh
   [MovieGEEK custom on GitHub](https://github.com/toan704/recommendsys)
### Tải và cài đặt Docker
   [Docker](https://www.docker.com)
Phiên bản khuyên nghị: Window - AMD64
### Đăng kí tài khoản và cấu hình API
•	Truy cập https://www.themoviedb.org/account/signup
•	Đăng ký
•	Đăng nhập, vào cài đặt tài khoản/API. Điền các thông tin cần thiết và tạo API. Lưu dữ lại API_Key
### Thiết lập ban đầu
•	Giải nén .prs.zip ra thư mục gốc của project
•	Mở file .prs và điền API_Key của bạn
### Cài đặt thư viện
```shell script
docker-compose build web
### Khởi chạy
```shell script
docker-compose up web
```
(để đóng lại bằng cách dừng tiến trình (Cltr+C))


