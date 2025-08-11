# CHUYÊN ĐỀ ASP.NET
## Đề tài: "Xây dựng website bán LaptoM"
Giáo viên hướng dẫn: **ThS. Đoàn Phước Mởền.**  
Quản lý học tập: **Trần Thị Khánh Linh.**  
Sinh viên thực hiện: **Nông Hồng Hải.**    
                - MSSV: 170123694  
                - Lớp: DK23TTG12  
                - SĐT: 0964437879  
                - Email: nhh.7879@gmail.com  
## Hướng dẫn cài đặt Project:  
1. Hệ điều hành: Windows 10 64bit hoặc Ưindows 11 64bit
2. Các phần mềm cần cài đặt:  
    - SQL Server 2022: File ".\setup\SQL2022-SSEI-Expr.exe"  
    - SQL Server Management Studio: File ".\setup\vs_SSMS.exe"  
    - Visual Studio 2022: File ".\setup\VisualStudioSetup.exe"  
3. Mở file ".\setup\scriptLAPTOPTV.sql" bằng SQL Server Management Studio sau đó nhấn "Execute" để tạo CSDL.  
4. Mở file ".\src\WebsiteBanHang.sln" bằng Visual Studio 2022  
5. Ở cửa số chương trình Visual Studio 2022 hiện lên:
    - Mở file "Web.config" và tìm đến thẻ <connectionString>  
    - Ở phần chuỗi kết nối "connectionString" (dòng 12 và 13), sửa trường Tên máy chủ SQL ("Server") bằng tên máy chủ của mình (phần Server name ở chương trình SQL Server Management Studio). Như file mẫu hiện tại đang là "Server=DESKTOP-4RK2QUL\SQLEXPRESS" (trường "DESKTOP-4RK2QUL\SQLEXPRESS" là tên máy chủ SQL).  
    - Tiến hành Buil Solution: Bấm tổ hợp phím Ctrl+Shift+B  
    - Chạy Project bằng cách bấm vào "IIS Express" trên thanh công cụ.  
6. Tài khoản đăng nhập trang quản trị:
    user: "admin"
    mật khẩu: "123"