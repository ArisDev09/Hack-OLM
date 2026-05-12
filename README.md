1. Giới thiệu
Script này có chức năng:

Lấy đáp án tự động từ các bài tập trắc nghiệm, điền khuyết, bài luận trên OLM.vn.

Hiển thị đáp án dưới dạng nổi (floating panel) có thể kéo/thả, thay đổi kích thước.

Tải đáp án về máy dưới dạng file Word (.docx).

Tìm kiếm và làm nổi bật nội dung câu hỏi trên trang (khi click vào đáp án).

2. Cài đặt
Yêu cầu:
Trình duyệt: Chrome, Firefox, Edge,...

Cài tiện ích Tampermonkey (khuyến nghị) hoặc Greasemonkey.

Các bước cài:
Tạo một script mới trong Tampermonkey.

Dán toàn bộ code bạn đã cung cấp vào.

Lưu lại (Ctrl+S).

Script sẽ tự động kích hoạt khi bạn truy cập bất kỳ trang nào thuộc *.olm.vn.

3. Cách sử dụng cơ bản
Hiển thị bảng đáp án
Khi bạn vào một bài tập (trắc nghiệm, điền khuyết, tự luận,...), bảng đáp án sẽ tự động xuất hiện ở góc phải màn hình.

Nếu chưa thấy, hãy nhấn phím Shift bên phải để bật/tắt bảng.

Tương tác với bảng đáp án
Thao tác	Mô tả
Kéo thả	Giữ chuột lên thanh tiêu đề (màu trắng mờ) để di chuyển bảng.
Thay đổi kích thước	Kéo góc dưới bên phải bảng (có biểu tượng \) để co giãn.
Ẩn/Hiện bảng	Nhấn Shift phải hoặc nhấn vào nút tròn nhỏ ở góc dưới màn hình (👀 / 🎃).
Tải đáp án Word	Nhấn nút "Tải đáp án (Word)" ở cuối bảng.
Tìm câu hỏi tương ứng với đáp án
Trong bảng đáp án, click vào bất kỳ nội dung nào có màu xanh hoặc dạng văn bản (thường là đáp án).

Script sẽ tự tìm và cuộn đến câu hỏi tương ứng trên trang, đồng thời làm nổi bật khung màu vàng trong 3 giây.

4. Giải thích các thành phần trong bảng đáp án
Thành phần	Ý nghĩa
Câu 1, Câu 2,...	Số thứ tự câu hỏi (theo thứ tự script bắt được).
Nội dung in đậm màu xanh	Đáp án chính xác (được làm nổi bật).
Ô có nền gradient xanh lá - xanh dương	Đáp án quan trọng hoặc cần chú ý.
Chữ "Không có dữ liệu"	Chưa có đáp án nào được tải về.
Nút "Tải đáp án (Word)"	Xuất toàn bộ đáp án hiện có ra file .docx.
5. Lưu ý quan trọng
⚠ Giới hạn của script:

Chỉ hoạt động trên OLM.vn (các đường dẫn có chứa olm.vn).

Cần tương tác với bài tập (mở câu hỏi, xem đề) thì script mới có thể bắt được đáp án.

Không thể lấy đáp án nếu OLM thay đổi cấu trúc truyền dữ liệu.

File Word tải về có thể không đẹp mắt do OLM sinh ra tự động.

✅ Mẹo sử dụng hiệu quả:

Mở trước một bài tập bất kỳ (trắc nghiệm hoặc điền khuyết) để script kích hoạt.

Nếu bảng đáp án trống, hãy tải lại trang hoặc nhấn F5.

Khi dùng trên điện thoại, bảng đáp án sẽ tự động co lại và hiển thị ở giữa màn hình (dễ thao tác).

6. Xử lý lỗi thường gặp
Lỗi	Nguyên nhân	Cách khắc phục
Bảng đáp án không hiện	Chưa vào đúng bài tập OLM	Vào trang có câu hỏi trắc nghiệm/điền khuyết.
Nhấn tải Word báo lỗi	Không tìm thấy ID chủ đề	Đảm bảo URL có dạng .../ten-bai-12345 (số cuối).
Đáp án hiển thị sai	OLM thay đổi API	Chờ cập nhật script mới.
Không click vào đáp án để tìm được câu hỏi	Nội dung câu hỏi quá ngắn hoặc đặc biệt	Script chỉ tìm được với câu dài >3 ký tự.
7. Tác giả & cập nhật
Script tự động cập nhật qua URL update.greasyfork.org.

Nếu muốn tắt cập nhật, xóa 2 dòng @downloadURL và @updateURL trong code.

8. Tuyên bố miễn trách
Script chỉ mang tính tham khảo và học tập. Việc sử dụng để gian lận trong thi cử là vi phạm quy chế của OLM và các cơ sở giáo dục. Hãy dùng đáp án để đối chiếu, kiểm tra kết quả sau khi tự làm bài.

Chúc bạn học tập hiệu quả! 📚✨

