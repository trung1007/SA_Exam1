# SA_Exam1
#### Sinh viên: Cao Thành Trung - 21020131 - K66CC
## `Docker`, `Docker-compose` là gì 
### `Docker` 
* `Docker` là một nền tảng mã nguồn mở cho việc tạo, triển khai và chạy các ứng dụng trong một môi trường cô lập gọi là container. Container là một phần tử chứa tất cả những thứ cần thiết để chạy một ứng dụng, bao gồm mã nguồn, các thư viện và các tài nguyên hệ thống cần thiết.
### `Docker-file` và `Docker-compose `
* `Docker file` được sử dụng để hỗ trợ tạo image hoặc nhiều image, đơn giản hóa quá trình tạo lập và cài đặt môi trường ảo theo nhu cầu sử dụng 
* `Docker compose` là công cụ thực hiện quản lý việc chạy các image thành container (image có thể do Docker file tạo ra). Ngoài ra Docker compose còn có thể quản lý volume (lưu trữ), network giữa các container hay biến môi trường
## `Linux` vs `Unix` vs `BSD` hay `*nix?` `MacOS` thuộc loại nào 
* `Unix` là OS gốc, bắt nguồn cho các OS khác như `Linux`, `BSD`. Tuy nhiên `Unix` là **close source**
* `BSD` (Berkeley Software Distribution) là 1 phiên bản của `Unix` (còn gọi là `unix-like` hay `*nix`). `BSD` ban đầu là **close source** tuy nhiên sau này xuất hiện `FreeBSD` là 1 phiên bản **open source** của `BSD`
* `Linux` là kernel có chức năng lấy cảm hứng từ `Unix`, được viết lại từ đầu bởi **Linus Tovarlds** và hoàn toàn **open source**. `Linux` không phải là 1 hệ điều hành hoàn chỉnh, nó chỉ là kernel (giống như động cơ xe ô tô). Linux kết hợp với `GNU` (GNU giống như các phần còn lại phụ tùng cho xe ô tô) tạo thành `GNU/Linux` mới được gọi là 1 OS hoàn chỉnh. Các OS như `Ubuntu`, `Debian`, `Fedora` là các **distribution** của `GNU/Linux`
* `Linux`, `BSD` hay các biến thể, distribution của 2 thứ này đều được gọi là `*nix` hay `unix-like`
* `macOS` là 1 nhánh của BSD
## `Alpine` vs `Ubuntu`
### Dependencies và kích thước
* Alpine sử dụng `musl-libc` và `busy-box` nên rất kích thước nhỏ gọn 
* Ubuntu sử dụng `glibc` và nhiều package khác nên kích thước lớn hơn rất nhiều so với Alpine
### Package mangaer
* Alpine sử dụng `apk`
* Ubuntu sử dụng `apt`
## `VNC`
* VNC (Virtual Network Computing) là công nghệ giúp điều khiển máy tính từ xa (tác dụng như TeamView). Có thể truy cập máy tính từ xa, chia sẻ màn hình, điều khiển chuột, bàn phím.
* VNC hoạt động trên một mô hình server / client. VNC Server được cài đặt trên máy tính bạn muốn điều khiển, VNC Viewer được cài đặt trên máy tính bạn muốn có quyền điều khiển.
## VNC Demo
![This is an alt text.](/img/Client.png "This is a sample image.")