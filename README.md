Công nghệ sử dụng: Java Spring Boot RESTful API

Video demo: https://drive.google.com/file/d/1l7awairLr3iyl2XyYjSufESS6paBdkzQ/view?usp=sharing

Đề bài:
Mô tả
Hãy xây dựng một API để quản lý thông tin về các sách trong một thư viện. Mỗi sách bao gồm các thuộc tính như: ID, Tên sách, Tác giả, và Năm xuất bản.
Yêu Cầu
Thiết kế Cơ sở Dữ liệu (CSDL):
Tạo bảng để lưu trữ thông tin về sách.
Gán một ID duy nhất cho mỗi sách.
Triển khai API bằng Java Spring MVC:
Tạo một Controller để xử lý các yêu cầu CRUD (Create, Read, Update, Delete) cho sách.
Triển khai các phương thức để thêm mới sách, lấy danh sách tất cả sách, cập nhật thông tin sách, và xóa sách.
Sử dụng các phương thức HTTP thích hợp cho mỗi yêu cầu CRUD (POST, GET, PUT, DELETE).
Nâng cao
viết API thực hiện:
- Tìm sách theo Tên sách
- Liệt kê tất cả các sách của một Tác giả
- Tìm hiểu thêm (phần mở rộng
- Thực hiện phân trang cho các sách, API nhận thêm đầu vào là page_size và page_num. Kết quả trả về sẽ ở dạng các "trang" dữ liệu, mỗi trang có `page_size` bản ghi.
  Ví dụ:
 Có tất cả 100 cuốn sách trên hệ thống
 Gọi API: /books?page_size=10&page_num=1 sẽ trả về 10 bản ghi đầu tiên (trang thứ nhất: từ bản ghi số 0 tới bản ghi số 9)
 Gọi API: /books?page_size=10&page_num=2 sẽ trả về 10 bản ghi tiếp theo (trang thứ hai: từ bản ghi số 10 tới bản ghi số 19)
Yêu cầu phụ
- Sử dụng maven để khởi tạo dự án
- Sử dụng MySQL để lưu trữ dữ liệu
- Sử dụng công cụ Postman để kiểm tra tính đúng đắn của chương trình
