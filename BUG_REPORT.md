# qc-testing-practice
Manual testing practice – SauceDemo

Bug ID: Bug_Navigation_01

Title: Đăng nhập thành công nhưng không chuyển sang trang chủ

Environment: 
- Windows 11
- Google Chrome
- URL: (https://www.saucedemo.com/)

Pre condition:
- User có tài khoản hợp lệ

Steps to reproduce: 
1. Mở trang Swag Labs
2. Nhập đúng username
3. Nhập đúng password
4. Bấm login
5. Bấm logout
6. Tắt trang mở lại
7. Thực hiện lại bước 1 - 4

Expected result:
- Đăng nhập thành công
- Chuyển sang trang chủ

Actual result:
- Đăng nhập thành công
- Không chuyển sang trang chủ

Severity: Major

Priority: High

Bug ID: Bug_checkout_01

Title: Checkout form chấp nhận dữ liệu không hợp lệ ở các trường First Name / Last Name / Zip Code

Environment:
- Windows 11
- Google Chrome
- URL: (https://www.saucedemo.com/)

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Steps to reproduce:
1. Mở trang Swag Labs
2. Đăng nhập bằng tài khoản hợp lệ
3. Thêm 1 sản phẩm bất kỳ vào giỏ hàng
4. Mở cart
5. Bấm checkout
7. Nhập ký tự không hợp lệ vào first name (Ví dụ: @@@)
8. Nhập ký tự không hợp lệ vào last name (Ví dụ: ###)
9. Nhập ký tự không hợp lệ vào zip code (Ví dụ: %%%)
10. Bấm continue

Expected result:
- Hệ thống không cho phép tiếp tục
- Hiển thị thông báo dữ liệu không hợp lệ cho từng trường

Actual result:
- Hệ thống cho phép tiếp tục sang bước tiếp theo
- Không hiển thị thông báo lỗi

Severity: Major

Priority: High

Bug ID: Bug_Checkout_02

Title: Không chọn sản phẩm vẫn checkout được

Environment:
- Windows 11
- Google Chrome
- URL: (https://www.saucedemo.com/)

Pre condition:
- User đã đăng nhập thành công
- Giỏ hàng trống

Steps to reproduce:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Bấm vào biểu tượng giỏ hàng
4. Bấm checkout
5. Nhập đúng First name
6. Nhập đúng Last name
7. Nhập đúng Zip code
8. Bấm continue
9. Bấm finish

Expected result:
- Không chuyển sang trang checkout: Complete
- Màn hình hiển thị thông báo: Product is required

Actual result:
- Chuyển sang trang checkout: Complete

Severity: Critical

Priority: High




