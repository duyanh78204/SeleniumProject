Lê Duy Anh - BIT220011 - 22SE1

Bài tập kiểm thử tự động với Selenium
___

# OrangeLoginTest

## Giới thiệu
Dự án này sử dụng Selenium WebDriver và TestNG để kiểm thử chức năng đăng nhập của ứng dụng OrangeHRM.  
Mục tiêu là xác minh rằng khi người dùng nhập đúng tên đăng nhập và mật khẩu, họ sẽ được chuyển hướng đến trang "Dashboard".

## Công cụ và công nghệ
- **Ngôn ngữ lập trình:** Java
- **IDE:** IntelliJ IDEA
- **Thư viện:** 
  - Selenium WebDriver
  - TestNG
- **Trình duyệt:** Google Chrome
- **Ứng dụng web:** [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)

## Cấu trúc chính
### Các phương thức:
1. **`Setup`**  
   - Thiết lập môi trường kiểm thử.  
   - Mở trình duyệt Chrome, phóng to cửa sổ và điều hướng đến trang đăng nhập của OrangeHRM.

2. **`tearDown`**  
   - Đóng trình duyệt sau khi hoàn thành kiểm thử.

3. **`testLoginTestApplication`**  
   - Kiểm thử chức năng đăng nhập:
     - Nhập thông tin tên đăng nhập và mật khẩu.
     - Nhấn nút đăng nhập.
     - Xác minh rằng người dùng đã được chuyển hướng đến trang "Dashboard".

## Hướng dẫn chạy kiểm thử
### Yêu cầu:
- **JDK 8+** đã được cài đặt.
- **Google Chrome** đã được cài đặt.
- **ChromeDriver** tương thích với phiên bản Chrome của bạn.
- **TestNG** được tích hợp trong dự án.

### Các bước thực hiện:
1. Tải hoặc clone dự án này về máy.
2. Đảm bảo bạn đã cấu hình đường dẫn `chromedriver` trong hệ thống (nếu cần thiết).
3. Mở dự án trong IntelliJ IDEA hoặc IDE tương tự.
4. Chạy file `OrangeLoginTest` dưới dạng TestNG Test.

### Kết quả mong đợi:
- Kiểm thử sẽ tự động nhập tên đăng nhập và mật khẩu hợp lệ, sau đó xác minh rằng người dùng được chuyển hướng đến trang "Dashboard".  

### Kết quả thực tế: 
<img width="1382" alt="image" src="https://github.com/user-attachments/assets/30b4bfc9-d3f8-45c8-baf6-61c3b434ba8d" />

- Trang Login:
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/ec1e154b-c67f-464b-b64e-489cb143cd04" />

- Trang Dashboard:
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/623aa567-b764-4586-987c-3200a4d51a6b" />

### Tài liệu tham khảo:
https://chatgpt.com/share/67865516-cf94-8008-bd4d-42190aa6b5dc

