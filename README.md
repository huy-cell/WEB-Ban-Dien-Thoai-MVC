## **Bắt Đầu**

### **Bước 1: Giải Nén Tập Tin**

### **Bước 2: Kết Nối Cơ Sở Dữ Liệu**
- Mở thư mục database và sao chép hai tập tin vào thư mục data của SQL SERVER.
   - Đường dẫn: `C:\Program Files\Microsoft SQL Server\MSSQL15.SQLEXPRESS\MSSQL\DATA`
- Mở SQL Server và đính kèm cơ sở dữ liệu.
- Khi hoàn thành, tiến hành bước tiếp theo.

### **Bước 3: Mở Dự Án với Visual Studio**
- Mở tệp `ictshop.sln` trong Visual Studio.
- Truy cập vào tệp `Web.config`.

### **Bước 4: Cấu Hình Kết Nối Cơ Sở Dữ Liệu**
- Trong thẻ `<connectionStrings>`, chỉnh sửa tên máy chủ, tên người dùng và mật khẩu để kết nối với SQL Server.
   - Cập nhật `data source` với tên máy chủ.
- Lưu các thay đổi, xây dựng ứng dụng và chạy nó.

### **Đăng Nhập:**
- Đối với tài khoản khách hàng:
   - Email: Khach@gmail.com
   - Mật khẩu: 12345678
- Đối với tài khoản quản trị:
   - Email: Admin@gmail.com
   - Mật khẩu: 12345678

### **Vai Trò Người Dùng**
- Ứng dụng có hai vai trò: quản trị viên và khách hàng.

### **Tính Năng**
- Thêm sản phẩm vào giỏ hàng: giỏ hàng sẽ được cập nhật với các sản phẩm đã chọn.
- Chỉnh sửa nội dung giỏ hàng.
- Đặt hàng.
- Nhấp vào hình ảnh sản phẩm để xem chi tiết.
- Quản trị viên có thể thêm, chỉnh sửa hoặc xóa sản phẩm và danh mục.
