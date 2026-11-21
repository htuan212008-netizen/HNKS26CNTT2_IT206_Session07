1. Prompt xử lý từng phần tài liệu
```
Bạn là trợ lý HR tổng hợp tài liệu nội bộ Công ty ABC Technology.
Chỉ sử dụng đúng nội dung trong [PHẦN TÀI LIỆU ĐƯỢC CUNG CẤP]. Tuyệt đối không suy đoán, không thêm thông tin ngoài tài liệu.
Hãy tóm tắt phần này theo cấu trúc:
1. Mục tiêu & phạm vi chương
2. Các quy định chính (giữ nguyên số liệu, thời hạn, tỷ lệ, điều kiện)
3. Trường hợp ngoại lệ
4. Thông tin quan trọng cần lưu giữ cho bước tổng hợp
Nếu mục nào không có trong phần này, ghi rõ "Không đề cập trong phần này".
[PHẦN TÀI LIỆU ĐƯỢC CUNG CẤP]: <dán nội dung từng chương/phần>
```
2. Prompt tổng hợp các phần
```
Bạn là trợ lý HR tổng hợp tài liệu quy định nhân sự (5 chương, 120 trang) của Công ty ABC Technology.
Chỉ sử dụng đúng các bản tóm tắt từng phần đã cung cấp. Tuyệt đối không suy đoán hoặc tự bịa quy định.
Hãy thực hiện:
1. Lập bảng tổng hợp gồm đúng 4 cột: Chủ đề | Quy định chính | Điều kiện áp dụng | Ngoại lệ.
2. Viết bản tóm tắt hoàn chỉnh dài khoảng 1.000–1.500 từ, bám sát số liệu, thời hạn, tỷ lệ, điều kiện và ngoại lệ.
3. Chỉ ra các liên kết/mối liên hệ giữa các chương và kiểm tra thông tin có thể bị bỏ sót.
4. Phân biệt rõ: [Có trong tài liệu] và [Chưa được đề cập / Chưa có trong phần đã xử lý].
[CÁC BẢN TÓM TẮT TỪNG PHẦN]: <dán bản tóm tắt các phần>
```
3. Bảng tổng hợp

| Chủ đề | Quy định chính | Điều kiện áp dụng | Ngoại lệ |
| :--- | :--- | :--- | :--- |
| Nội quy lao động | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] |
| Quy định nghỉ phép | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] |
| Chính sách làm thêm giờ | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] |
| Quy định đánh giá nhân viên | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] |
| Chính sách khen thưởng và kỷ luật | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] | [Chưa được đề cập — điền từ tài liệu gốc] |
4. Bản tóm tắt hoàn chỉnh (~1.000–1.500 từ)
```
Tài liệu quy định nhân sự nội bộ của Công ty ABC Technology gồm 5 chương, tổng cộng 120 trang, phục vụ chuẩn bị cho buổi hướng dẫn nhân viên mới. Tài liệu gồm 5 mảng: Nội quy lao động, Quy định nghỉ phép, Chính sách làm thêm giờ, Quy định đánh giá nhân viên, và Chính sách khen thưởng và kỷ luật. Vì vượt quá Context Window nếu xử lý một lần, tài liệu cần được chia theo phần logic, xử lý riêng từng chương, giữ nguyên con số, thời hạn, tỷ lệ, điều kiện, ngoại lệ, không suy đoán và phân biệt rõ [Có trong tài liệu] với [Chưa được đề cập].

Chương 1 – Nội quy lao động: [Có trong tài liệu: tên chủ đề và phạm vi chương 1]. Chi tiết quy định, điều kiện áp dụng và ngoại lệ: [Chưa được đề cập trong đề bài — điền từ file 120 trang].

Chương 2 – Quy định nghỉ phép: [Có trong tài liệu: tên chủ đề và phạm vi chương 2]. Chi tiết số ngày, thời hạn, tỷ lệ, điều kiện áp dụng và ngoại lệ: [Chưa được đề cập trong đề bài — điền từ file 120 trang].

Chương 3 – Chính sách làm thêm giờ: [Có trong tài liệu: tên chủ đề và phạm vi chương 3]. Chi tiết giới hạn giờ, tỷ lệ, điều kiện áp dụng và ngoại lệ: [Chưa được đề cập trong đề bài — điền từ file 120 trang].

Chương 4 – Quy định đánh giá nhân viên: [Có trong tài liệu: tên chủ đề và phạm vi chương 4]. Chi tiết chu kỳ, tiêu chí, điều kiện áp dụng và ngoại lệ: [Chưa được đề cập trong đề bài — điền từ file 120 trang].

Chương 5 – Chính sách khen thưởng và kỷ luật: [Có trong tài liệu: tên chủ đề và phạm vi chương 5]. Chi tiết hình thức, mức độ, điều kiện áp dụng và ngoại lệ: [Chưa được đề cập trong đề bài — điền từ file 120 trang].

Liên kết giữa các chương: các quy định cùng áp dụng cho nhân sự công ty và liên quan lẫn nhau trong vận hành, theo dõi công/hiệu suất, đánh giá và khen thưởng/kỷ luật (chi tiết cụ thể: [Chưa được đề cập trong đề bài]). Kiểm tra bỏ sót: cần rà soát đủ số liệu, thời hạn, tỷ lệ, điều kiện và ngoại lệ ở từng chương khi chạy trên file 120 trang; toàn bộ chi tiết cụ thể bên trong 5 chương hiện [Chưa được đề cập] trong nội dung đề bài.
```
5. Câu hỏi kiểm tra thông tin
Tài liệu của ABC Technology có mấy chương và tổng cộng bao nhiêu trang?

Trả lời: 5 chương, tổng cộng 120 trang.

Vị trí: Phần 1. Bối cảnh vấn đề.

5 nội dung được quy định trong tài liệu gồm những gì?

Trả lời: Nội quy lao động; Quy định nghỉ phép; Chính sách làm thêm giờ; Quy định đánh giá nhân viên; Chính sách khen thưởng và kỷ luật.

Vị trí: Phần 1. Bối cảnh vấn đề.

Yêu cầu đầu vào và nguyên tắc xử lý dữ liệu là gì?

Trả lời: 01 file PDF hoặc DOCX tối thiểu 50 trang; không suy đoán quy định ngoài tài liệu; xử lý riêng từng chương; giữ nguyên con số, thời hạn, tỷ lệ, điều kiện; không bỏ qua ngoại lệ; phân biệt rõ thông tin có trong tài liệu và chưa được đề cập.

Vị trí: Phần 2. Ràng buộc dữ liệu.

Chi tiết cụ thể về quy định, điều kiện và ngoại lệ của 5 chương đã có trong đề bài chưa?

Trả lời: Chưa được đề cập trong đề bài; cần trích từ tài liệu gốc 120 trang khi xử lý từng phần.

Vị trí: Phần 1. Bối cảnh vấn đề & Phần 2. Ràng buộc dữ liệu.

Những bước nghiệp vụ nào cần thực hiện với AI?

Trả lời: Chia tài liệu thành phần logic; tóm tắt từng phần theo cấu trúc thống nhất; lưu thông tin quan trọng sau mỗi lần xử lý; tổng hợp thành tài liệu hoàn chỉnh; phát hiện liên kết giữa các chương; kiểm tra thông tin bị bỏ sót.

Vị trí: Phần 3. Yêu cầu nghiệp vụ.
