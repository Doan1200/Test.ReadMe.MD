1. Thẻ tiêu đề

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dụng 1 đến 6 ký tự # liên tiếp. Mức độ tiêu đề giảm dần từ 1 --> 6.
Ví dụ:
# 1. Tiêu đề cấp 1

## 2. Tiêu đề cấp 2

**2. Chèn link và hình ảnh**

Để chèn hyperlink bạn chỉ cần paste luôn link đó vào file .md

https://github.com

Hoặc bạn cũng có thể dùng cú phát sau để thu ngắn đường link

[Github](http://github.com)

Để chèn hình ảnh bạn hãy sử dụng cú pháp sau

<img src= "link_anh_cua_ban">

<img src= "https://cdn.pixabay.com/photo/2023/05/23/15/26/bengal-cat-8012976_640.jpg">

**3. Ký tự in đậm, in nghiêng**
* Để in đậm một đoạn text bạn chỉ cần làm như sau:
    `**từ cần in đậm**`
* Để in nghiêng một đoạn text bạn chỉ cần làm như sau:
    `*từ cần in nghiêng*`
**4. Trích dẫn, bo chữ**
Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:
    `đoạn cần bo`
Kết quả là `Đoạn cần bo`
Để làm nổi bật một đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp sau:
``` sh
```sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```
```

Kết quả như sau:

auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8






