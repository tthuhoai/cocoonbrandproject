# The Cocoon - Website Mỹ Phẩm Thuần Chay

Website giới thiệu thương hiệu mỹ phẩm thuần chay Cocoon - Original Vietnam.

## Cấu trúc thư mục

```
hoai-project/
├── media/                  # Thư mục chứa ảnh
│   ├── coconutlogo.png     # Logo lớn (footer)
│   ├── coconutlogo1.png    # Logo nhỏ (header)
│   ├── sanphamsumary.png   # Ảnh banner trang chủ
│   ├── voucherdesign.png   # Ảnh banner voucher
│   ├── cafedaklak.png      # Sản phẩm: Cà phê Đắk Lắk
│   ├── toner.png           # Sản phẩm: Toner sen Hậu Giang
│   ├── matna.png           # Sản phẩm: Mặt nạ nghệ Hưng Yên
│   ├── gelruamatcafe.png   # Sản phẩm: Gel rửa mặt cà phê
│   ├── sapduongam.png      # Sản phẩm: Sáp dưỡng ẩm đa năng
│   ├── srmnghe.png         # Sản phẩm: Sữa rửa mặt nghệ
│   ├── xitkhoangnghe.png   # Sản phẩm: Xịt khoáng nghệ
│   ├── suachongnang.png    # Sản phẩm: Sữa chống nắng bí đao
│   ├── taydachetcafe.png   # Sản phẩm: Tẩy da chết cà phê
│   ├── coxanh.png          # Icon: 100% Thuần chay
│   ├── contho.png          # Icon: Không thử nghiệm động vật
│   └── cafe.png            # Icon: Nguyên liệu thuần Việt
│
├── source/                 # Thư mục chứa code
│   ├── index.html          # Trang chủ
│   ├── product.html        # Trang tất cả sản phẩm
│   ├── blog.html           # Trang bài viết
│   ├── login.html          # Trang đăng nhập
│   ├── register.html       # Trang đăng kí
│   ├── style.css           # CSS chung (header, footer, trang chủ)
│   ├── product.css         # CSS riêng trang sản phẩm
│   ├── blog.css            # CSS riêng trang bài viết
│   └── auth.css            # CSS riêng trang đăng nhập/đăng kí
│
└── README.md
```

## Các trang

| Trang | File | Mô tả |
|-------|------|-------|
| Trang chủ | `index.html` | Banner, sản phẩm nổi bật, slogan, voucher |
| Sản phẩm | `product.html` | Grid 3x3 hiển thị 9 sản phẩm |
| Bài viết | `blog.html` | Bài viết nổi bật + chuyên mục Làm đẹp, Cocoon |
| Đăng nhập | `login.html` | Form đăng nhập (email, mật khẩu) |
| Đăng kí | `register.html` | Form đăng kí (họ tên, email, SĐT, mật khẩu) |

## Cách chạy

Mở file `source/index.html` trực tiếp bằng trình duyệt.

## Công nghệ

- HTML5 / CSS3
- Google Fonts: Playfair Display, Roboto
- Responsive (hỗ trợ tablet và mobile)
