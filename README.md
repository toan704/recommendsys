# The MovieGEEK - Hướng dẫn cài đặt

Hướng dẫn này cung cấp các bước cài đặt phiên bản tinh chỉnh của The MovieGEEK để triển khai nhanh chóng và hiệu quả.

## Yêu cầu

- Mã nguồn: Tải tại [MovieGEEK Custom](https://github.com/toan704/recommendsys)
- Docker: Cài đặt từ [Docker](https://www.docker.com) (Khuyến nghị: Windows - AMD64)

## Cấu hình API

1. Truy cập [The Movie Database](https://www.themoviedb.org/account/signup) và đăng ký tài khoản.
2. Đăng nhập, vào Settings > API, tạo API Key và lưu lại API Key.

## Thiết lập ban đầu

1. Giải nén file `.prs.zip` vào thư mục gốc của dự án.
2. Mở file `.prs` và nhập API Key đã nhận.

## Cài đặt và khởi chạy

1. Xây dựng ứng dụng cùng các thư viện:

```bash
docker-compose build web
```
2. Khởi chạy:
```bash
docker-compose up web
```
Để dừng, hãy ấn Ctrl+C