# The MovieGEEK - Hướng dẫn cài đặt

Hướng dẫn này cung cấp các bước cài đặt phiên bản tinh chỉnh của The MovieGEEK để triển khai nhanh chóng và dễ dàng hơn

## Yêu cầu

- Mã nguồn: Tải tại [MovieGEEK Custom](https://github.com/toan704/recommendsys)
- Docker: Cài đặt từ [Docker](https://www.docker.com) (Khuyến nghị: Windows - AMD64). Đảm bảo đã đăng nhập và truy cập vào Docker

## Cấu hình API

1. Truy cập [Themoviedb](https://www.themoviedb.org/account/signup) và đăng ký tài khoản.
2. Đăng nhập, vào Settings > API, tạo API Key và lưu lại API Key.

## Thiết lập ban đầu

1. Giải nén file `moviegeek_config.zip` vào thư mục gốc của dự án.
2. Mở file `.prs` và nhập API Key đã nhận
3. Kiểm tra ở thư mục gốc đảm bảo xuất hiện 2 files: `.prs` và `db.sqlite3`

## Cài đặt và khởi chạy

1. Xây dựng ứng dụng cùng các thư viện:

```bash
docker-compose build web
```
2. Khởi chạy:
```bash
docker-compose up web
```
Để dừng, hãy ấn `Ctrl+C`

## Nguồn
https://github.com/practical-recommender-systems/moviegeek