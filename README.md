# XuLyNgonNguTuNhien
Xây dựng Website tìm kiếm và hiển thị các nội dung tương đồng với một văn bản cần kiểm tra bằng Google.
BT1
Viết chương trình bằng ngôn ngữ Python, sử dụng Regular expression, để trích xuất danh sách các email, địa chỉ website, số điện thoại từ văn bản. Chỉ sử dụng thư viện re, KHÔNG SỬ DỤNG CÁC THƯ VIỆN XỬ LÝ NGÔN NGỮ KHÁC.
Input: file văn bản, định dạng .txt
Output: list các tuple có dạng (vị trí bắt đầu, độ dài, email/website/số điện thoại)
BT2
Cho một văn bản tiếng Việt, rút trích các từ khóa (keyword) đại diện cho văn bản đó.
Gợi ý: tập tin đính kèm chứa các minh họa cho việc rút trích keyword cho một văn bản tiếng Anh.
Các bạn có thể tham khảo một trong 3 hướng tiếp cận LSA, LDA, NMF trong các minh họa để thực hiện tương tự cho tiếng Việt.

Lưu ý:
- Các bạn chỉ cần cài đặt 1 hướng tiếp cận duy nhất trong chương trình, theo thứ tự ưu tiên LSA > LDA, NMF, Phương pháp Khác (Tức là LSA là bắt buộc, các phương pháp LDA, NMF và Phương pháp khác nếu các bạn làm sẽ được cộng điểm).
- Nộp: file nén .zip chứa mã nguồn chương trình và data thực nghiệm

Quy tắc viết chương trình:
- Chương trình viết dưới dạng dòng lệnh, hỗ trợ 2 tham số bắt buộc là input_file và result, tên tập tin chạy là keyword_extraction.py.
Ví dụ:
python keyword_extraction.py --input_file text.txt --result output.txt
Trong đó: text.txt là văn bản đầu vào (cần trích từ khóa), output chứa các từ khóa kết quả
BT3
Xây dựng mô hình phân loại cảm xúc người dùng. Sử dụng bộ dữ liệu Vietnamese Students’ Feedback Corpus (UIT-VSFC). Trong tập tin tải xuống có đính kèm file README.md hướng dẫn sử dụng dữ liệu.

Link download: https://drive.google.com/file/d/1TRsg7W5veQrHgaiHSbGu7-wto5VCo7zK/view?usp=sharing

Yêu cầu đầu vào: cho một câu phản hồi của dựa trên dữ liệu đã huấn luyện.

Yêu cầu đầu ra: đánh giá cảm xúc của câu đó theo 3 loại: tiêu cực (0), trung tính (1), tích cực (2)

Quy tắc viết chương trình:
- Chương trình viết dưới dạng dòng lệnh, hỗ trợ 2 tham số bắt buộc là input (câu đầu vào) và result (file kết quả). Tên tập tin chạy là sentiment_analysis.py.
Ví dụ:
python sentiment_analysis.py --input "Môn học rất bổ ích" --result sentiment.txt
Trong đó: --input "Môn học rất bổ ích" là câu đầu vào, sentiment.txt chứa cảm xúc, kết quả là 0 hoặc 1 hoặc 2

Chú ý:

- Sử dụng ngôn ngữ Python;

- Được sử dụng các thư viện hỗ trợ trong quá trình xây dựng. Tuy nhiên không được sử dụng các hàm có sẵn trong các thư viện, nghĩa là phải tự xây dựng một mô hình do bản thân làm.
