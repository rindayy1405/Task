# Directory Lister

Script Python để liệt kê nội dung thư mục, lưu vào JSON/MySQL, và cung cấp API để truy vấn dữ liệu.

## Tính năng
- Liệt kê tệp/thư mục với kích thước, ngày sửa đổi, lọc định dạng.
- Lưu kết quả vào JSON (`output/directory_list.json`) và MySQL (`files` table).
- Chạy lệnh hệ thống (`dir` hoặc `ls -l`).
- API endpoint `/api/files` để lấy danh sách tệp/thư mục từ MySQL.
- Hỗ trợ kiểm thử với unittest và Postman.

## Cài đặt
1. Cài đặt Python 3.6+ và MySQL.
2. Tạo database trong MySQL Workbench:
   ```sql
   CREATE DATABASE directory_lister;#   T a s k  
 #   T a s k  
 