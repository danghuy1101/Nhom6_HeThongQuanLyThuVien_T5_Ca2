# Nhom6_HeThongQuanLyThuVien_T5_Ca2
Giới thiệu đề tài:
- Hệ thống quản lý thư viện không chỉ giới hạn ở việc tổ chức và lưu trữ sách một cách cẩn thận, mà còn là bước tiến quan trọng trong việc tối ưu hóa trải nghiệm của người đọc và quản lý tài chính của thư viện. Thông qua giao diện người dùng thân thiện, độc giả có thể dễ dàng tìm kiếm sách theo tiêu chí như tên tác giả, chủ đề, hoặc mã số sách. Hệ thống tự động cập nhật số lượng sách còn trong kho và thông báo khi sách được mượn hoặc trả. Điều này giúp đảm bảo rằng sách luôn sẵn sàng cho người đọc và giảm thiểu việc mất mát hoặc làm hỏng sách do việc quản lý không hiệu quả.

- Ngoài ra, hệ thống quản lý thư viện còn theo dõi thông tin về người đọc, bao gồm tên, địa chỉ, thông tin liên hệ và lịch sử mượn sách. Khi người đọc mượn sách, hệ thống tự động ghi chép thông tin về sách đã mượn và ngày hạn trả. Hệ thống cũng có khả năng hiển thị số tiền mượn sách dựa trên quy định của thư viện và tính toán tự động phiếu nợ nếu sách bị trễ hạn. Điều này giúp thư viện duy trì sự minh bạch trong các giao dịch và giúp người đọc hiểu rõ về các khoản phí nếu có.

- Hơn nữa, hệ thống quản lý thư viện đáp ứng nhu cầu của cả thư viện nhỏ và lớn, giúp họ tiết kiệm thời gian và công sức trong việc quản lý sách và thông tin độc giả. Bằng cách này, nó không chỉ tạo điều kiện thuận lợi cho người đọc, mà còn giúp thư viện hoạt động một cách hiệu quả và chuyên nghiệp.

Giới thiệu nhóm:
- Nhóm 6 gồm 3 thành viên với các vai trò:
+ Đậu Đăng Huy: Developer
+ Nguyễn Tấn Lợi: Product Owner
+ Phan Thanh Vinh: Scrum Master

Giới thiệu công nghệ sử dụng:
- Hệ thống quản lý thư viện sử dụng công nghệ hiện đại bao gồm mô hình MVC (Model-View-Controller), Entity Framework và SQL Server Management Studio (SSMS) để cung cấp một trải nghiệm quản lý sách mượn linh hoạt và hiệu quả. Mô hình MVC giúp chia thành ba thành phần chính: Model, nơi lưu trữ dữ liệu sách, độc giả và thao tác với cơ sở dữ liệu; View, giao diện người dùng thân thiện để tìm kiếm và xem thông tin sách; và Controller, điều hướng các yêu cầu và tương tác với Model để truy xuất dữ liệu.

- Entity Framework, một ORM mạnh mẽ, cho phép ứng dụng tương tác với cơ sở dữ liệu SQL một cách dễ dàng và linh hoạt, giúp tạo, đọc, cập nhật và xóa dữ liệu một cách tự nhiên thông qua đối tượng. SQL Server Management Studio (SSMS) là công cụ quản lý cơ sở dữ liệu SQL Server, hỗ trợ thiết lập, tối ưu hóa và duy trì cơ sở dữ liệu một cách hiệu quả.

- Tổng hợp, việc sử dụng mô hình MVC, Entity Framework và SQL Management trong hệ thống quản lý thư viện không chỉ tối ưu hóa quy trình quản lý thông tin sách và độc giả, mà còn đảm bảo tính linh hoạt, dễ bảo trì và mở rộng của hệ thống, tạo điều kiện thuận lợi cho việc cung cấp dịch vụ thư viện đáng tin cậy và hiệu quả.

Hướng phát triển và những nội dung làm được:
Tối Ưu Hiệu Suất:
-Cơ sở Dữ Liệu Hiệu Quả: Tối ưu hóa cấu trúc cơ sở dữ liệu, sử dụng chỉ các truy vấn cần thiết để giảm thiểu thời gian truy vấn và tăng tốc độ xử lý dữ liệu.
-Tối ưu mã hóa và Ảnh Hưởng Giao Diện Người Dùng: Giảm bớt việc tải trang và tối ưu hóa các hình ảnh để cải thiện tốc độ tải trang.

 Trải Nghiệm Người Dùng:
- Giao Diện Thân Thiện: Xây dựng một giao diện người dùng đơn giản, dễ sử dụng, và dễ hiểu.
- Tương Tác Người Dùng: Sử dụng các yếu tố tương tác như thông báo đa hướng, tìm kiếm theo dõi và gợi ý để cải thiện trải nghiệm người dùng.
- 
Hỗ Trợ Đa Nền Tảng và Thiết Bị:
- Responsive Design: Xây dựng giao diện web có thể hiển thị tốt trên cả máy tính, điện thoại di động và tablet.
-Ứng Dụng Di Động: Phát triển ứng dụng di động cho cả hệ điều hành Android và iOS để cung cấp trải nghiệm tốt trên các thiết bị di động.

Khả Năng Mở Rộng và Tích Hợp:
-  API và Tích Hợp Dễ Dàng: Cung cấp API để cho phép tích hợp dễ dàng với các ứng dụng và dịch vụ khác.
- Tích Hợp Thư Viện và Framework: Sử dụng các thư viện và framework phổ biến để giảm thời gian phát triển và tăng khả năng mở rộng.

Nội dung làm được
- Quản lý Sách: Thêm, chỉnh sửa và xóa sách khỏi thư viện.
- Danh sách yêu thích: hiển thị danh sách sách yêu thích của người dùng
- Đăng nhập/ đăng ký: có phân quyền
- Đánh giá sao, comment: hiển thị comment và tính toán sao trung bình của người dùng sau khi đánh giá.
- Thẻ và Danh Mục: Tạo thẻ và danh mục để phân loại sách. 
- Tìm Kiếm Sách: Tìm kiếm sách dựa trên tiêu đề, tác giả hoặc từ khóa. 
- Mượn/Trả Sách: Ghi nhận thông tin mượn và trả sách cho từng người dùng. 
- Thống Kê: Hiển thị thông tin thống kê về tình trạng sách và hoạt động mượn sách.
