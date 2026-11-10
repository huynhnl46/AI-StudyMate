
# FUNCTIONAL REQUIREMENTS — AI STUDYMATE

## 1. Tổng quan

AI StudyMate là ứng dụng trợ lý học tập thông minh, hỗ trợ sinh viên quản lý tài liệu, học tập và cá nhân hóa quá trình ôn luyện bằng AI.

## 2. Các tác nhân (Actors)

- Guest: Người chưa đăng nhập.
- Student: Sinh viên đã đăng nhập.
- AI Service: Dịch vụ AI xử lý câu hỏi, tài liệu và nội dung học tập.

## 3. Danh sách chức năng

| ID | Chức năng | Mô tả | Ưu tiên |
|---|---|---|---|
| FR01 | Register | Đăng ký tài khoản | High |
| FR02 | Login | Đăng nhập | High |
| FR03 | Logout | Đăng xuất | High |
| FR04 | Upload PDF | Tải tài liệu PDF lên | High |
| FR05 | Extract Text | Trích xuất văn bản từ PDF | High |
| FR06 | PDF Question Answering | Đặt câu hỏi về nội dung PDF | High |
| FR07 | Source Citation | Hiển thị nguồn và số trang tham chiếu | High |
| FR08 | AI Summary | Tóm tắt tài liệu bằng AI | High |
| FR09 | AI Quiz | Tạo câu hỏi trắc nghiệm từ tài liệu | Medium |
| FR10 | Flashcards | Tạo và quản lý thẻ ghi nhớ | Medium |
| FR11 | Study Planner | Tạo và quản lý lịch học | Medium |
| FR12 | Progress Tracking | Theo dõi tiến độ học tập | Medium |
| FR13 | Chat History | Xem lại lịch sử trò chuyện | Medium |
| FR14 | Profile Management | Quản lý thông tin cá nhân | Low |

## 4. Chi tiết các chức năng chính

### 4.1. Authentication
- Người dùng có thể đăng ký tài khoản.
- Người dùng có thể đăng nhập và đăng xuất.
- Hệ thống xác thực người dùng trước khi truy cập dữ liệu cá nhân.

### 4.2. PDF Assistant
- Sinh viên tải tài liệu PDF lên.
- Hệ thống trích xuất nội dung văn bản.
- Hệ thống chia văn bản thành các đoạn nhỏ (chunks).
- Sinh viên đặt câu hỏi dựa trên tài liệu.
- AI trả lời dựa trên nội dung được truy xuất.
- Câu trả lời hiển thị nguồn tham chiếu và số trang khi có dữ liệu tương ứng.

### 4.3. AI Summary
- Sinh viên chọn tài liệu cần tóm tắt.
- AI phân tích nội dung tài liệu.
- Hệ thống trả về bản tóm tắt dễ hiểu.

### 4.4. AI Quiz
- Sinh viên chọn tài liệu.
- AI tạo câu hỏi trắc nghiệm.
- Sinh viên làm bài và nhận kết quả.

### 4.5. Flashcards
- Sinh viên tạo bộ flashcards.
- Mỗi flashcard gồm câu hỏi và câu trả lời.
- Sinh viên có thể xem và ôn tập flashcards.

### 4.6. Study Planner
- Sinh viên tạo nhiệm vụ học tập.
- Sinh viên đặt thời hạn và trạng thái hoàn thành.
- Hệ thống hiển thị danh sách nhiệm vụ.

### 4.7. Progress Tracking
- Hệ thống ghi nhận hoạt động học tập.
- Hiển thị số lượng tài liệu, nhiệm vụ và bài kiểm tra.
- Thống kê tiến độ học tập của sinh viên.

## 5. Phạm vi phiên bản MVP

Phiên bản đầu tiên ưu tiên:
1. Đăng ký và đăng nhập.
2. Tải và quản lý PDF.
3. Hỏi đáp PDF bằng AI có trích dẫn nguồn.
4. Tóm tắt tài liệu.
5. Tạo Quiz cơ bản.
6. Quản lý Study Planner.

Flashcards và Progress Tracking sẽ được tích hợp sau khi các chức năng cốt lõi hoạt động ổn định.

## 6. Tiêu chí nghiệm thu

- Người dùng có thể đăng ký và đăng nhập.
- Người dùng có thể tải PDF và xem tài liệu đã tải.
- Hệ thống trích xuất được nội dung PDF có văn bản.
- AI có thể trả lời câu hỏi dựa trên tài liệu đã tải.
- Câu trả lời có nguồn tham chiếu phù hợp.
- Người dùng có thể tạo bản tóm tắt và bài Quiz.
- Người dùng có thể tạo và cập nhật nhiệm vụ học tập.
