# II. Ngôn ngữ Markdown

**1. Thẻ tiêu đề**

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dụng 1 đến 6 ký tự # liên tiếp. Mức độ tiêu đề giảm dần từ 1 --> 6.

Ví dụ:

``` sh
# 1. Tiêu đề cấp 1
```

# 1. Tiêu đề cấp 1

``` sh
## 2. Tiêu đề cấp 2
```

## 2. Tiêu đề cấp 2

``` sh
###### 6. Tiêu đề cấp 6
```

**2. Chèn link và hình ảnh**

Để chèn hyperlink bạn chỉ cần paste luôn link đó vào file .md

``` sh
https://github.com
```

<https://github.com>


Hoặc bạn cũng có thể dùng cú phát sau để thu ngắn đường link

``` sh
[Github](http://github.com)
```

Kết quả là:

Github

Để chèn hình ảnh bạn hãy sử dụng cú pháp sau

``` sh
<img src= "link_anh_cua_ban">
```

**3. Ký tự in đậm, in nghiêng**

* Để in đậm một đoạn text bạn chỉ cần làm như sau:

``` sh
**từ cần in đậm**
```

**từ cần in đậm**

* Để in nghiêng một đoạn text bạn chỉ cần làm như sau:

``` sh
*Từ cần in nghiêng*
```

*Từ cần in nghiêng*

**4. Trích dẫn, bo chữ**

Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:    

``` sh
`Đoạn cần bo`
```

Kết quả là:  `Đoạn cần bo`

Để làm nổi bật một đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp sau:
``` sh
\``` sh 
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
\```
```

Kết quả như sau:

``` sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```

**5. Gạch đầu dòng**

Để sử dụng gạch đầu dòng bạn cần sử dụng cú pháp sau:

``` sh
- Gạch đầu dòng thứ nhất

    - Thụt với đầu dòng 1

    - Thụt với đầu dòng 1

- Gạch đầu dòng thứ 2
    
    - Thụt với đầu dòng 2

    - Thụt với đầu dòng 2
```

- Gạch đầu dòng thứ nhất

    - Thụt với đầu dòng 1

    - Thụt với đầu dòng 1

- Gạch đầu dòng thứ 2
    
    - Thụt với đầu dòng 2

    - Thụt với đầu dòng 2

**6. Tạo bảng**

Bạn có thể sự dụng cú pháp sau để tạo bảng:

``` php
| Cột 1 Hàng 1 | Cột 2 | Cột 3 | Cột 4 |
|--------------|-------|-------|-------|
| Hàng 2 | 2 x 1| 2 x 2 | 2 x 3 | 2 x 4 |
```

Kết quả

| Cột 1 Hàng 1 | Cột 2 | Cột 3 | Cột 4 |
|--------------|-------|-------|-------|
| Hàng 2 | 2 x 1| 2 x 2 | 2 x 3 | 2 x 4 |

# III. Các thao tác với Git và Github

**1. Repo**

**Ba trạng thái của Repo**

<img src= "https://camo.githubusercontent.com/1cf44b45b66ba1fc99f931bb12df659abd09fd20ab900d8783ba86a598db61a0/687474703a2f2f692e696d6775722e636f6d2f716b6d644a53522e706e67">

{@youtube: https://www.youtube.com/watch?v=BKaQy_qAd0w}




