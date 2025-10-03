---
layout: post
title: Luyện tập với dịch ngược firmware
---

Trong bài viết này, sẽ đề cập đến Work shop firmware reversing mà tôi luyện tập tại đây [workshop_firmware_reverse_engineering](https://github.com/emproof-com/workshop_firmware_reverse_engineering)<br>
Cảm ơn tác giả: Tim Blazytko đã tạo ra 1 repo bổ ích.<br>


Bài: keygenning_1<br>
B1. Kiểm tra cấu trúc file:<br>
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/checkfile.png)<br>
Kiến trúc AArch64, file executable ELF64<br>


B2. Dịch ngược<br>
Hàm Main<br>
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/re_checklicense.png)<br>
Hàm kiểm tra license<br>
![_config.yml]({{ site.baseurl }}/images/Work-Shop-Firmware-Reversing/re_verify.png)<br>


Như vậy nếu username là: procracker thì serial sẽ là: kitxizxp~i<br>
