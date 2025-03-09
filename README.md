# PHPLaravel
Tuần 1:

+) tìm hiểu php-laravel-mô hình MVC
  
    -> Model (Mô hình)
  
    -> View (Giao diện)
  
    -> Controller (Bộ điều khiển)
  
 - https://www.geeksforgeeks.org/introduction-to-laravel-and-mvc-framework/

+) Tìm hiểu cấu trúc của 1 dự án Laravel

 -> app/
    
    │── Console/        # Các lệnh Artisan tùy chỉnh
    
    │── Exceptions/     # Xử lý ngoại lệ (Exceptions)
    
    │── Http/
    
    │   │── Controllers/  # Chứa các Controller (Xử lý logic ứng dụng)
    
    │   │── Middleware/   # Chứa các Middleware (Lọc request)
    
    │── Models/         # Chứa các Model (Tương tác với Database)
    
    │── Providers/      # Chứa các Service Providers (Cấu hình ứng dụng)
 
 -> config/
    
    │── app.php       # Cấu hình chung (timezone, locale, name)
    
    │── database.php  # Cấu hình database
    
    │── mail.php      # Cấu hình email
    
    │── queue.php     # Cấu hình hệ thống hàng đợi (Queue)
    
    │── session.php   # Cấu hình session
    
    │── view.php      # Cấu hình views
 
 -> database/
    
    │── factories/     # Chứa các factory dùng để tạo dữ liệu giả
    
    │── migrations/    # Chứa các file migration để tạo bảng DB
    
    │── seeders/       # Chứa các file seeder để tạo dữ liệu mẫu
 
 -> public/
    
    │── index.php   # Điểm vào chính của Laravel (entry point)
    
    │── css/        # Chứa file CSS (nếu có)
    
    │── js/         # Chứa file JavaScript (nếu có)
    
    │── storage/    # Liên kết với storage (chứa ảnh, file)
 
 -> resources/
    
    │── views/  # Chứa các file giao diện (Blade template)
    
    │── lang/   # Chứa file dịch đa ngôn ngữ
    
    │── css/    # Chứa file CSS (nếu không dùng frontend framework)
    
    │── js/     # Chứa file JS (nếu không dùng frontend framework)
 
 -> routes/
    
    │── web.php       # Chứa các route cho giao diện web
    
    │── api.php       # Chứa các route API
    
    │── console.php   # Chứa các lệnh artisan tùy chỉnh
 
 -> storage/
    
    │── app/         # Chứa file do ứng dụng tạo ra
    
    │── framework/   # Chứa cache và session
    
    │── logs/        # Chứa file log của Laravel

    https://hocwebchuan.com/tutorial/laravel/laravel_project_structure.php

+) tìm hiểu route/middleware

-> route: https://viblo.asia/p/tim-hieu-ve-route-trong-laravel-V3m5W1pwZO7

-> middleware: https://topdev.vn/blog/middleware-la-gi/

+) Làm quen với Laravel bằng cách clone 1 dự án lên github

-> Đăng nhập vào github:
  
    -> Tìm New repository, tạo kho lưu trữ.

-> đẩy dự án mình tạo lên:
 
    -> Khởi tạo Git trong thư mục dự án: git init
 
    -> Thêm tất cả các tệp vào Git: git add .
 
    -> Kiểm tra trạng thái: git status
 
    -> Thêm địa chỉ repository GitHub: git remote add origin https://github.com/your-username/your-repository.git
 
    -> Commit các thay đổi: git commit -m "Initial commit"
   
    -> Đẩy dự án lên GitHub: git branch -M main, git push -u origin main
   
    -> clone dự án có sẵn về máy: git clone https://github.com/be1tui/PHPLaravel
  
+) Xây dựng project mẫu với form thêm/sửa/xóa 1 sinh viên

+) Tìm hiểu cách hoạt động của request
  
    https://chungnguyen.xyz/posts/laravel-request-lifecycle-laravel-hoat-dong-nhu-the-nao-ban-biet-chua
