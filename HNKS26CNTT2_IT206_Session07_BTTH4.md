# [Bài thực hành 4] Sử dụng Feynman Prompt để học kiến thức lập trình

## 1. Prompt thiết lập gia sư AI
Gia sư OOP Java theo phương pháp Feynman. Hỏi lần lượt 5 khái niệm: Class, Object, Attribute, Method, Constructor. Không giải thích trước, chỉ hỏi từng câu. Yêu cầu tôi tự giải thích đơn giản. Sau mỗi câu: đánh giá, chỉ lỗi, không đưa đáp án ngay nếu sai mà gợi ý ví dụ thực tế để tôi giải thích lại. Cuối buổi tổng kết phần đã hiểu và chưa hiểu.

## 2. Bản ghi cuộc hội thoại (5 câu hỏi – trả lời)
* **Class:** AI hỏi -> SV: file chứa code -> AI: chưa đúng, nghĩ bản vẽ nhà -> SV: bản thiết kế quy định có gì, làm gì -> AI: chuẩn.
* **Object:** AI hỏi -> SV: thực thể cụ thể tạo bằng `new` (nhà thật) -> AI: đúng.
* **Attribute:** AI hỏi -> SV: biến lưu đặc điểm/trạng thái (`color`) -> AI: đúng.
* **Method:** AI hỏi -> SV: hành động thực hiện được (`run()`) -> AI: đúng.
* **Constructor:** AI hỏi -> SV: hàm trùng tên Class, không kiểu trả về, tự chạy khi `new` để khởi tạo -> AI: tốt. Tổng kết: nắm 5 khái niệm, chú ý tránh nhầm biến cục bộ với Attribute.

## 3. Bảng đánh giá mức độ hiểu
| Khái niệm | Mức độ hiểu |
| :--- | :--- |
| Class | Đạt |
| Object | Tốt |
| Attribute | Tốt |
| Method | Tốt |
| Constructor | Tốt |

## 4. Ví dụ thực tế về Class và Object
* **Class (`Car`):** Bản thiết kế xe có `brand` và `drive()`.
* **Object (`myCar`):** Xe cụ thể `brand = "Toyota"`.

## 5. Tự giải thích lại OOP sau buổi học
**Class** là bản thiết kế gồm **Attribute** (đặc điểm) và **Method** (hành động); dùng `new` thì **Constructor** chạy để tạo ra **Object** cụ thể.
