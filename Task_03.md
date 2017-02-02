# Task 3.

> Tên tài liệu: Kết nối database

> Thực hiện: Nguyễn Minh Nhật.

> Cập nhật lần cuối: 02/02/2017.

## Mục lục.

[1. Kết nối Database](#database)

## Nội dung.

<a name="database"></a>

- Ta có 1 CSDL MySQL tên là : `ds_thanh_vien` 

- CSDL này có 1 table tên là: `thanh_vien`.

-  Table này có 3 cột `stt`, `user`, `pass`.

![image](http://imageshack.com/a/img922/2561/8IO46Z.png)

### Các bước để kết nối với CSDL.

- **B1**: Khai báo các thông số

- `$servername="localhost"`: `$servername` của chúng ta mặc định là `localhost`.

- `$username="root"`: `$username` để mặc định là `root`.

- `$passwork=""`: mặc định `passwork` là không có.

- `$database="ds_thanh_vien"`: tên database muốn `connect` tới, ở đây database của chúng ta tên `ds_thanh_vien`.

![a](http://imageshack.com/a/img922/7839/qy06Yd.png)

- *Lưu ý*: 2 biến `$passwork` và `$username` có thể thay đổi trong setting của `XAMPP`.

- **B2**: Sử dụng function `mysqli_connect()` để kết nối với CSDL.

- Tuyền các thông số `$servername`, `$username`, `passwork`, `$database`.

![image](http://imageshack.com/a/img924/9287/TVgOZ0.png)

- **B3**: Kiểm tra kết nối.

- Sử dụng câu lệnh `if else` để check và function `die` để thông báo lỗi.

![image](http://imageshack.com/a/img924/8546/LzgPuy.png)
 
 - **B4**: Chạy thử trên trình duyệt và kiểm tra.
 
 ![image](http://imageshack.com/a/img924/8229/8in9Le.png)

- Kết nối thành công !

*Thanks you for watching !*





