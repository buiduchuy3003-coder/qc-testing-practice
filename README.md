# qc-testing-practice
Manual testing practice – SauceDemo

Test case ID: TC_Login_01

Title: Đăng nhập tài khoản thành công

Pre condition: 
- User đã có tài khoản

Test steps:
1. Mở trang Swag Labs
2. Nhập đúng username
3. Nhập đúng password
4. Bấm login

Expected result:
- Đăng nhập thành công
- Chuyển sang trang chủ

Actual result:
- Đăng nhập thành công
- Chuyển sang trang chủ

Status: Pass

Test case ID: TC_Login_02

Title: Bỏ trống Username

Pre condition:
- User có tài khoản

Test steps:
1. Mở trang Swag Labs
2. Bỏ trống username
3. Nhập đúng password
4. Bấm login

Expected result:
- Hiển thị thông báo lỗi "Username is required"
- Đăng nhập không thành công

Actual result:
- Hiển thị thông báo lỗi "Username is required"
- Đăng nhập không thành công

Status: Pass

Test case ID: TC_Login_03

Title: Nhập sai Username

Pre condition: 
- User đã có tài khoản

Test steps:
1. Mở trang Swag Labs
2. Nhập sai Username
3. Nhập đúng password
4. Bấm login

Expected result:
-  Username and password do not match any user in this service
-  Đăng nhập không thành công

Actual result:
-  Username and password do not match any user in this service
-  Đăng nhập không thành công

Status: Pass

Test case ID: TC_Login_04

Title: Nhập sai mật khẩu

Pre condition:
- User đã có tài khoản

Test steps:
1. Mở trang Swag Labs
2. Nhập đúng Username
3. Nhập sai password
4. Bấm login

Expected result:
-  Username and password do not match any user in this service
-  Đăng nhập không thành công

Actual result:
-  Username and password do not match any user in this service
-  Đăng nhập không thành công

Status: Pass

Test case ID: TC_Login_05

Title: Bỏ trống mật khẩu

Pre condition: 
- User đã có tài khoản

Test steps:
1. Mở trang Swag Labs
2. Nhập đúng Username
3. Bỏ trống password
4. Bấm login

Expected result:
- Password is required
- Đăng nhập không thành công

Test case ID: TC_Checkout_01

Title: 

Actual result:
- Password is required
- Đăng nhập không thành công
Status: Pass

