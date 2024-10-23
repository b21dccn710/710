# Chủ đề : Crawl dữ liệu trên web nghe nhạc để lấy thông tin về bảng xếp hạng các bài hát hot nhất trong tuần / tháng
# Thành viên nhóm - Mã sinh viên : Trương Vĩnh Tiến - B21DCCN710
# Mô tả dự án : 
## Mục tiêu của dự án:
   - Lấy dữ liệu bảng xếp hạng hàng tuần : Dữ liệu cần lấy bao gồm tên bài hát, nghệ sĩ, vị trí xếp hạng, tuần có mặt trên bảng xếp hạng, và các thông tin liên quan khác (ví dụ như số lượt nghe, điểm số).
   - Phân tích dữ liệu : Dữ liệu này có thể được sử dụng để phân tích xu hướng âm nhạc, theo dõi sự thay đổi thứ hạng của các ca khúc theo thời gian, hoặc tìm ra những bài hát mới nổi.
## Công nghệ sử dụng:
   - Python làm ngôn ngữ chính.
   - Requests : Dùng để gửi yêu cầu HTTP tới trang web để lấy nội dung HTML.
   - BeautifulSoup : Phân tích HTML và trích xuất thông tin từ các thẻ cụ thể trong trang web.
   - Selenium : Nếu trang web tải dữ liệu qua JavaScript, Selenium sẽ được dùng để giả lập người dùng tải trang và tương tác với nội dung động.
   - Pandas : Để xử lý dữ liệu sau khi thu thập, có thể dùng Pandas để tạo bảng xếp hạng và lưu dưới dạng CSV hoặc Excel.
