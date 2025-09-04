# The MovieGEEK - Hướng dẫn cài đặt
CÀI ĐẶT DOCKER
### Tải về mã nguồn đã được tinh chỉnh
   Tải xuống: [MovieGEEK custom](https://github.com/toan704/recommendsys),
### Tải và cài đặt Docker
   Tải xuống: [Docker](https://www.docker.com),
   Phiên bản khuyến nghị: Window - AMD64
### Đăng kí tài khoản và cấu hình API
   B1: Truy cập [Themoviedb](https://www.themoviedb.org/account/signup), 
   B2: Đăng ký
   B3: Đăng nhập, vào cài đặt tài khoản/API. Điền các thông tin cần thiết và tạo API. Lưu dữ lại API_Key
### Thiết lập ban đầu
   B1: Giải nén .prs.zip ra thư mục gốc của project
   B2: Mở file .prs và điền API_Key của bạn
### Cài đặt thư viện
```shell script
docker-compose build web
```
### Khởi chạy
```shell script
docker-compose up web
```
(để đóng lại bằng cách dừng tiến trình (Cltr+C))
