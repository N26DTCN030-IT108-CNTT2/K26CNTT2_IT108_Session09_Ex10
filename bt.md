# Phần 1: Phân tích & Đề xuất (Đa giải pháp)
## Phân tích yêu cầu bài toán (Input / Output)Đầu vào (Input):
Câu hỏi hoặc chủ đề cần AI giải đáp (ví dụ: khái niệm kỹ thuật) kèm theo đối tượng người dùng (sinh viên năm 1 chưa có nền tảng) và các ràng buộc về văn phong, độ dài.
Đầu ra (Output): Câu trả lời từ AI đạt độ chính xác cao, đúng trọng tâm, phù hợp với trình độ người nhận, dễ hiểu và không chứa quá nhiều thuật ngữ hàn lâm đánh đố.
2. Phân tích ưu điểm và nhược điểm của 2 chiến lượcChiến lược A (Văn xuôi thuần túy — Prompt của Lan):Ưu điểm: Gần gũi, tự nhiên như giao tiếp thông thường, nhanh chóng gõ ra mà không cần nhớ cú pháp ký hiệu đặc biệt. 
Tốn ít số lượng token ban đầu.Nhược điểm: Dễ bị lan man, thiếu cấu trúc phân tách rõ ràng khiến AI đôi khi bỏ sót các ràng buộc khắt khe (độ dài, đối tượng) khi câu hỏi dài hơn. Khó tái sử dụng cho các chủ đề khác mà phải viết lại từ đầu.Chiến lược B (Cấu trúc Markdown 3 phần — Prompt của Minh):
Ưu điểm: Cực kỳ rõ ràng, phân định rách bạch giữa bối cảnh, nội dung, yêu cầu và điều kiện loại trừ. Giúp AI hiểu chính xác ngữ cảnh và trả lời đúng trọng tâm tuyệt đối. Cấu trúc dạng mẫu (Template) dễ dàng sao chép và tái sử dụng linh hoạt.Nhược điểm: Tốn thêm một chút thời gian cấu trúc ký hiệu (##, -) và số lượng token đầu vào lớn hơn một chút so với văn xuôi đơn thuần.
Phần 2: So sánh & Lựa chọn3.
Bảng so sánh 4 tiêu chí nghiệp vụ
Tiêu chí nghiệp vụ
Chiến lược A (Văn xuôi)Chiến lược B (Markdown 3 phần)
1. Độ chính xácKhá (Dễ bị AI bỏ sót yêu cầu phụ nếu câu dài)
 Rất cao (Phân tách rõ ràng từng mục giúp AI bám sát 100%)
2. Tiêu thụ TokenThấp hơn (Ít ký tự cấu trúc phụ trợ)
   Cao hơn một chút (Do có thêm các thẻ Heading và danh sách)
3. Khả năng tái sử dụng
   Thấp (Mỗi lần hỏi phải soạn lại văn bản từ đầu)
   Rất cao (Chỉ cần thay đổi phần nội dung cốt lõi, giữ nguyên khung mẫu)
4. Dễ học cho người mới
   Cực kỳ dễ (Ai cũng có thể nhắn tin chat bình thường
   Cần làm quen với cấu trúc định dạng phân cấp Markdown
4. Chốt lựa chọn và lý giảiBối cảnh nên dùng Chiến lược A: Khi cần hỏi nhanh các câu hỏi ngắn gọn, tính chất tra cứu thông tin đơn giản hàng ngày, không yêu cầu quá nhiều ràng buộc phức tạp (ví dụ: "Thủ đô của Pháp là gì?").Bối cảnh nên dùng Chiến lược B: Khi học tập các môn chuyên ngành phức tạp, cần yêu cầu AI đóng vai gia sư, giới hạn độ dài, định dạng rõ ràng và kiểm soát kiến thức cho sinh viên năm 1.Lựa chọn tối ưu: Chiến lược B là lựa chọn chuyên nghiệp và hiệu quả lâu dài cho lập trình viên và sinh viên IT.
