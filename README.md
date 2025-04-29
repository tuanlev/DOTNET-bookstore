📚 DOTNET Bookstore
Ứng dụng quản lý sách được xây dựng với ASP.NET Core MVC, giúp quản lý danh mục sách, đơn hàng và người dùng một cách hiệu quả.​
GitHub


🚀 Tính năng chính
Quản lý sách: Thêm, sửa, xóa sách với thông tin chi tiết như tiêu đề, tác giả, giá và mô tả.

Quản lý danh mục: Phân loại sách theo danh mục để dễ dàng tìm kiếm và quản lý.

Quản lý người dùng: Đăng ký, đăng nhập, phân quyền người dùng (Admin, Khách hàng).

Giỏ hàng và đơn hàng: Thêm sách vào giỏ hàng, tạo đơn hàng và theo dõi trạng thái đơn hàng.

Tìm kiếm và lọc: Tìm kiếm sách theo tiêu đề, tác giả hoặc danh mục.

Giao diện thân thiện: Giao diện người dùng trực quan, dễ sử dụng.​

🛠️ Công nghệ sử dụng
Backend: ASP.NET Core MVC (.NET 6)

Frontend: Razor Pages, HTML, CSS, JavaScript

Cơ sở dữ liệu: SQL Server

ORM: Entity Framework Core

Xác thực & Phân quyền: ASP.NET Identity

Thanh toán: Tích hợp Stripe (nếu có)

Triển khai: Azure hoặc IIS​
GitHub
GitHub
GitHub
+3
GitHub
+3
GitHub
+3

📂 Cấu trúc thư mục
Sao chép
Chỉnh sửa
DOTNET-bookstore/
├── Controllers/
├── Models/
├── Views/
├── wwwroot/
├── Data/
├── Services/
├── Program.cs
└── Startup.cs
⚙️ Cài đặt và chạy dự án
Yêu cầu
.NET 6 SDK

SQL Server

Visual Studio 2022 hoặc Visual Studio Code​
GitHub

Các bước thực hiện
Clone repository:

bash
Sao chép
Chỉnh sửa
git clone https://github.com/tuanlev/DOTNET-bookstore.git
cd DOTNET-bookstore
Cập nhật chuỗi kết nối cơ sở dữ liệu trong appsettings.json.​

Áp dụng migration và tạo cơ sở dữ liệu:

bash
Sao chép
Chỉnh sửa
dotnet ef database update
Chạy ứng dụng:

bash
Sao chép
Chỉnh sửa
dotnet run
Truy cập ứng dụng tại https://localhost:5001.​
GitHub

🧪 Tài khoản mẫu
Admin

Email: admin@example.com

Mật khẩu: Admin@123

Khách hàng

Email: user@example.com

Mật khẩu: User@123​
my tech ramblings
+7
GitHub
+7
GitHub
+7
my tech ramblings
+5
GitHub
+5
GitHub
+5
GitHub

