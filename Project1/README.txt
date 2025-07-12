-------------------------------------------------------------------
		Phần mềm VietClass 
Mô tả: Phần mềm VietClass là một ứng dụng đơn giản được thiết kế để lưu trữ, chỉnh sửa và quản lý thông tin điểm số của 1 học sinh trung học. Phần mềm hỗ trợ giáo viên, học sinh và phụ huynh trong việc theo dõi và quản lý kết quả học tập một cách hiệu quả.
-------------------------------------------------------------------
Thông tin chung:
- Tác giả: Huỳnh Tử Khiêm
- Ý tưởng: Phần mềm Vietschool, trang web tradiem.vn
- Ngày bắt đầu: 11/7/2025
- Ngày hoàn thành: 14/7/2025
- Thời gian thực hiện: 3 ngày, 14 tiếng lập trình
- Nguồn tham khảo: Chatbot AI, giáo trình nhập môn lập trình C của nhiều trường đại học: Bách khoa TPHCM, Công nghiệp TPHCM, Công nghệ thông tin TPHCM
- Đối tượng sử dụng: Học sinh trung học cơ sở và phổ thông; Giáo viên; Phụ huynh học sinh.
- Ngôn ngữ lập trình: C
- Phần mềm lập trình: DevC++
-------------------------------------------------------------------
Chức năng chính:
- Nhập và lưu trữ điểm: Cho phép người dùng nhập điểm số các môn học và lưu trữ vào file Excel.
- Xem điểm: Hiển thị điểm số theo môn học, học kỳ hoặc cả năm học.
- Tự tính điểm: Tự động tính điểm trung bình môn, trung bình học kỳ và trung bình cả năm.
- Cập nhật, chỉnh sửa điểm: Cho phép người dùng chỉnh sửa hoặc cập nhật điểm số.
- Tạo ghi chú: Cho phép người dùng tạo ghi chú cá nhân để ghi nhớ các thông tin quan trọng.
-------------------------------------------------------------------
Chức năng cụ thể:
- Nhập và lưu trữ điểm: Người dùng nhập điểm từng môn học (ví dụ: Toán, Lý, Hóa, Văn, v.v.) cho các loại điểm như thường kỳ, giữa kỳ, cuối kỳ. Điểm số được lưu trữ vào file Excel tại địa chỉ trong thư mục chung với phần mềm. File dữ liệu Excel này sẽ được sử dụng cho các chức năng khác như xem điểm, tính điểm trung bình và chỉnh sửa/cập nhât. Dữ liệu được tổ chức theo cấu trúc: STT, Họ và Tên, Mã HS, Điểm môn học (theo từng loại điểm), Trung bình môn, Trung bình học kỳ, Trung bình cả năm.
- Xem điểm: Xem điểm của một môn học cụ thể trong một học kỳ hoặc cả năm. Xem điểm trung bình của một học kỳ (học kỳ 1 hoặc học kỳ 2). Xem điểm trung bình cả năm học, bao gồm tất cả các môn. Giao diện hiển thị đơn giản cho phép lọc theo môn học hoặc học kỳ.
- Tự tính điểm: Tính điểm trung bình môn dựa trên công thức: (Điểm Thường Kỳ 1 + Điểm Thường Kỳ 2) / 2. Tính điểm trung bình học kỳ: (TB Thường Kỳ * 1 + Giữa Kỳ * 2 + Cuối Kỳ * 3) / 6. Tính điểm trung bình cả năm: Trung bình cộng của điểm trung bình hai học kỳ. Kết quả được cập nhật tự động vào file Excel.
-Cập nhật, chỉnh sửa điểm: Người dùng có thể chỉnh sửa điểm số của bất kỳ môn học hoặc loại điểm nào.Hệ thống kiểm tra tính hợp lệ của điểm (từ 0 đến 10) trước khi lưu. Mọi thay đổi được ghi lại vào file Excel và cập nhật các giá trị trung bình tương ứng.
- Ghi chú: Người dùng có thể tạo, chỉnh sửa và xóa ghi chú cá nhân. Ghi chú được lưu trong một sheet riêng trong file Excel (Notes). Mỗi ghi chú bao gồm tiêu đề, nội dung và ngày tạo, giúp học sinh hoặc giáo viên ghi nhớ các thông tin quan trọng (ví dụ: lịch kiểm tra, nhắc nhở học tập).
-------------------------------------------------------------------
Ưu điểm của chương trình:
- Tiện lợi: Thay vì phải tạo một file Excel với rất nhiều cột và dòng thì chỉ cần nhập điểm vào phần mềm này thì sẽ tự động tính toán.
- Dễ sử dụng: Giao diện đơn giản, phù hợp với cả giáo viên, học sinh và phụ huynh không chuyên về công nghệ.
- Tự động hóa: Tự động tính toán điểm trung bình, giảm thiểu sai sót trong việc quản lý điểm số.
- Linh hoạt: Hỗ trợ nhập, chỉnh sửa và xem điểm theo nhiều tiêu chí (môn học, học kỳ, cả năm).
- Lưu trữ bền vững: Dữ liệu được lưu trong file Excel, dễ dàng sao lưu và chia sẻ.
- Miễn phí và dễ tiếp cận: Không yêu cầu phần mềm phức tạp, chỉ cần Excel để vận hành.
-------------------------------------------------------------------
Nhược điểm của chương trình:
- Hạn chế về giao diện: Vì sử dụng ngôn ngữ lập trình C nên.
- Phụ thuộc vào Excel: Yêu cầu người dùng cài đặt Microsoft Excel hoặc phần mềm tương thích.
- Khả năng mở rộng hạn chế: Chỉ hỗ trợ cơ bản cho quản lý điểm số, chưa tích hợp các tính năng nâng cao như báo cáo thống kê hoặc phân tích dữ liệu.
- Bảo mật: Không có tính năng bảo mật nào nên có thể bị truy cập trái phép nếu không được bảo vệ đúng cách.
-------------------------------------------------------------------
Ý nghĩa đối với bản thân:
- Dự án Vietschool là dự án đầu tiên tôi thực hiện, đánh dấu bước khởi đầu trong hành trình học lập trình C một cách chuyên nghiệp của tôi. Thông qua dự án này, tôi đã nắm vững cách sử dụng những kiến thức cơ bản trong ngôn ngữ lập trình C để xử lý dữ liệu như struct, con trỏ,... Học được cách tổ chức dữ liệu một cách logic và hiệu quả.
- Có cái nhìn thực tế hơn về lập trình, từ việc lên ý tưởng, triển khai đến hoàn thiện một sản phẩm có tính ứng dụng cao. Tôi nhận ra để làm một dự án hoàn chỉnh yêu cầu rất nhiều kỹ năng, kiến thức, không dễ thực hiện nếu không có những lộ trình, phương pháp cụ thể.
-------------------------------------------------------------------