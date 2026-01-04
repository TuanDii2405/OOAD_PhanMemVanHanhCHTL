# ĐỀ TÀI
XÂY DỰNG PHẦN MỀM Quản lý vận hành Cửa hàng tiện lợi
<br>Công nghệ sử dụng: Java Swing, JDBC, POI Apache, iText API
<br>Công cụ sử dụng: IntelliJ, NetBeans, MSSQL, Draw.io (vẽ ERD)

## Hướng dẫn cài đặt
**Bước 1: **Thiết lập Cơ sở dữ liệu (SQL Server)
- Khởi tạo tài khoản: Đảm bảo SQL Server của bạn đã được cấu hình tài khoản Login với thông tin:
+ User: sa
+ Password: 123
- Khởi tạo Database:
- Mở công cụ SQL Server Management Studio (SSMS) 2022.
- Tìm đến đường dẫn resource/sql trong thư mục dự án.
- Mở và thực thi (Execute) file GenerateScripts(new).sql để tự động khởi tạo cấu trúc cơ sở dữ liệu.

**Bước 2:** Cấu hình Dự án (Project Structure)
Mở dự án trên IDE và thực hiện các thiết lập trong mục Project Structure (phím tắt Ctrl + Alt + Shift + S):

Import Module: Vào Modules > Add > Import Module. Chọn file Mini-Store-Manager.iml (bỏ qua nếu dự án đã nhận diện được cấu hình).

Thiết lập Output: Cấu hình đường dẫn Compiler Output trỏ về thư mục out của dự án.

Quản lý Thư viện (Libraries): Thêm các thư viện cần thiết trong thư mục lib. Đảm bảo đã include đầy đủ:

iTextPDF (phiên bản 5.5)

POI Apache (Xử lý Excel)

JDBC (Kết nối SQL Server)

Cấu hình SDK: Chọn phiên bản JDK phù hợp cho dự án tại mục Project.

Định vị Source Code: Tại tab Modules, kiểm tra thư mục src. Nếu chưa có màu xanh, hãy chuột phải vào src và chọn Sources.

**Bước 3:** Khởi chạy Chương trình
Sau khi hoàn tất cấu hình, tìm đến file thực thi chính theo đường dẫn: src/_Entry/EntryMain.java

Chuột phải vào file và chọn Run 'EntryMain' để bắt đầu sử dụng ứng dụng.
 
  
