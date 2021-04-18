Cách đổi tên Username, Home Folder Path trong Ubuntu:  

1, Sửa thông tin hiển thị:  

Click vào góc phải màn hình > Settings > Users  

Tại đây, bạn có thể Sửa tên hiển thị, cùng với Avatar người dùng.  

2, Sửa Username kèm Homefolder path:  

=> Dùng usermod  

`sudo usermod -l newusername -d /home/userfolder -m oldusername`  

Khá đơn giản phải không, bạn chú ý dùng `sudo mv /home/oldfolder /home/newfolder` để sửa cái folder nhé.  

Note: Nên tạo 1 user tạm thời với quyền Administrator để test, tránh trường hợp gõ sai hoặc lỗi => không đăng nhập được !
