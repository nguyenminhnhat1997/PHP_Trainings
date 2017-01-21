# Task 02.

> Tên tài liệu: Task 02.

> Thực hiện: Nguyễn Minh Nhật.

> Cập nhật lần cuối: 22/01/2017.

## Mục lục:

[1.Git là gì ? Dùng làm gì ? ](#git)

[2.Cài đặt Git lên máy tính](#setting)

[3.Cách sử dụng Git trên cmd (terminal)](#using)

[4.Sử dụng Git để commit/push file `READM.md` lên github](#push)


## Nội dung:

<a name="git"></a>
### 1. Git là gì ? Dùng làm gì ?

-1.1 Git là gì ?

> Git là 1 ứng dụng quản lý file, lịch sử cập nhật file sẽ được lưu lại trong Git, chúng ta không cần copy trước file dùng để sao lưu có sẵn nên rất thuận tiện.

-1.2 Dùng làm gì ?

> Dùng để cập nhật, chỉnh sửa file mà không lo sợ nhầm lẫn file cũ với file mới cập nhật.
> Nhiều người cùng cập nhật mà không sợ bị ghi đè nội dung.
> file có thể được chia sẽ với nhiều người và cũng có thể chỉ 1 cá nhân đảm bảo tính bảo mật.

<a name="setting"></a>
### 2. Cài đặt Git lên máy tính.

2.1 Có thể down Git tại link này [https://git-scm.com/](https://git-scm.com/)

- Có thể tự cài đặt, sau khi cài đặt xuất hiện các ứng dụng như sau:

![a](http://imageshack.com/a/img923/4958/bvnQ7p.png)
<a name="using"></a>
<a name="push"></a>
### 3. Cách sử dụng Git trên Cmd (terminal).
### 4.Sử dụng Git để commit/push file `READM.md` lên github](#push).

#### 4.1 Ta chọn `Git CMD`.

> Kết quả: Sẽ hiện ra 1 cửa sổ, ta sẽ thao tác với cửa sổ này.

![a](http://imageshack.com/a/img923/5894/LbTEiT.png)

#### 4.2 Ta chuyển đến thư mục mà ta muốn lưu các file trên Github.


> Syntax: `cd (địa chỉ đến thư mục đó)`.

> *Ví dụ*: ở đây tôi muốn lưu các file trên Github vào trong thư mục `Test` nằm trong thư mục `Task_WEB` ở ngoài `Desktop`.

- Ta làm từng bước như sau.

![a](http://imageshack.com/a/img924/9873/3fREZx.png)

#### 4.3 Thực hiện thêm `tên` và `email`.

![a](http://imageshack.com/a/img922/6920/0AWANJ.png)

#### 4.4 Ở bên github vào repository Test ta đã tạo trước đó copy link HTTPS.

![a](http://imageshack.com/a/img924/3043/coQhBV.png)

> Ghi nhớ cái link đó để tí nữa ta sẽ thực hiện Clone(có nghĩa là ta sẽ sao chép toàn bộ nội dung từ Github về máy tính).

#### 4.5 Clone, Add, Commit, Push.

- Ta sẽ tiến hành Clone như sau: `git clone linke_lúc_nãy_ta_nhớ`.

![a](http://imageshack.com/a/img921/1958/e1Vg22.png)

> Clone thành công.

- Ta sẽ tạo 1 file tên READM.md trong thư mục `Test` có nội dung là `# Nguyen Van A bằng` bằng `Node pad`,`Sublime text`....

![a](http://imageshack.com/a/img921/3718/wEZJ0g.png)

- Ta tiến hành `add` file vừa tạo lên github bằng câu lệnh: `git add READM.md` or `git add .`, dấu `.` có nghĩa là tất cả các file.

![a](http://imageshack.com/a/img923/4737/MYpnNP.png)

> Nó không thông báo gì tức là đã add thành công.

- Tiếp theo ta sẽ `commit` có nghĩa là ta sẽ ghi lại việc ta `add` lúc nãy và có thể kèm thêm `ghi chú` cho file vừa add lên.

 Cú pháp là: `git commit -m "nội_dung_ghi_chú`.

![a](http://imageshack.com/a/img922/2640/WqLkZK.png)

- Tiếp theo ta sẽ upload nội dung mà hiện tại máy ta có (file `READM.md`) lên Github gọi là `push`.

> Cú pháp: `git push origin master`.

![a](http://imageshack.com/a/img923/3905/Rod5Yu.png)

- Thế là đã `push` lên thành công (nếu push lần đầu nó sẽ yêu cầu tài khoản và mật khẩu cứ nhập vào sẽ ok).
#### 4.6 Kiểm tra kết quả `push` trên web github.

![a](http://imageshack.com/a/img924/3931/3qy2Ai.png)

## Thank you for watching ^^!

























