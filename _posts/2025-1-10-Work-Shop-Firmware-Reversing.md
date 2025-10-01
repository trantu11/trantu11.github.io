---
layout: post
title: Luyện tập với dịch ngược firmware
---

Trong bài viết này, sẽ đề cập đến Work shop firmware reversing mà tôi luyện tập tại đây [workshop_firmware_reverse_engineering](https://github.com/emproof-com/workshop_firmware_reverse_engineering)  
Cảm ơn tác giả: Tim Blazytko đã tạo ra 1 repo bổ ích.  

Bài: keygenning_1  
1. Kiểm tra cấu trúc file:  
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/checkfile.png)  
Kiến trúc AArch64, file executable ELF64  
  
2. Dịch ngược  
Hàm Main  
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/re_checklicense.png)  
Hàm kiểm tra license  
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/re_verify.png)  
Như vậy nếu username là: procracker thì serial sẽ là: ,+;,);-};-(;,);-*;-(;-y;-.;,)  