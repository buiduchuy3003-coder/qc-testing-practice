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

Actual result:
- Password is required
- Đăng nhập không thành công

Status: Pass

Test case ID: TC_Checkout_01

Title: Nhập đúng thông tin checkout

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Nhập đúng First name
7. Nhập đúng Last name
8. Nhập đúng Zip code
9. Bấm continue

Expected result:
- Chuyển sang trang overview
- Hiển thị thông tin đơn hàng đúng

Status: Pass

Test case ID: TC_Checkout_02

Title: Bỏ trống first name

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Bỏ trống First name
7. Nhập đúng Last name
8. Nhập đúng Zip code
9. Bấm continue

Expected result:
- Không chuyển sang trang overview
- Hiển thị first name is required

Status: Pass

Test case ID: TC_Checkout_03

Title: Bỏ trống Last name

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Nhập đúng First name
7. Bỏ trống Last name
8. Nhập đúng Zip code
9. Bấm continue

Expected result:
- Không chuyển sang trang overview
- Hiển thị Last name is required

Status: Pass

Test case ID: TC_Checkout_04

Title: Bỏ trống Zip code

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Nhập đúng First name
7. Nhập đúng Last name
8. Bỏ trống Zip code
9. Bấm continue

Expected result:
- Không chuyển sang trang overview
- Hiển thị Postal code is required

Status: Pass

Test case ID: TC_Checkout_05

Title: Bỏ trống First name, Last name, Zip code

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Bỏ trống First name
7. Bỏ trống Last name
8. Bỏ trống Zip code
9. Bấm continue

Expected result:
- Không chuyển sang trang overview
- Hiển thị First name is required

Status: Pass

Test case ID: TC_Checkout_06

Title: Kết thúc quá trình mua hàng.

Pre condition:
- User đã đăng nhập thành công
- Có ít nhất 1 sản phẩm trong giỏ hàng

Test steps:
1. Mở trang Swag Labs
2. Đăng nhập tài khoản hợp lệ
3. Chọn 1 món hàng tùy ý
4. Bấm cart
5. Chọn checkout
6. Nhập đúng First name
7. Nhập đúng Last name
8. Nhấm đúng Zip code
9. Bấm continue
10. Bấm finish

Expected result:
- Thông tin trang overview chính xác
- Chuyển sang trang checkout: Complete (finish)

Status: Pass

Test case ID: TC_Checkout_07

Title: Không chọn sản phẩm vẫn checkout được

Pre condition:
- User đã đăng nhập thành công
- Giỏ hàng trống

Test steps:
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

Status: Fail



