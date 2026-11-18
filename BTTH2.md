Bạn là một Chuyên gia Kỹ thuật Prompt và Chiến lược Nội dung Công nghệ. Hãy giúp tôi giải quyết hoàn chỉnh đề bài thiết kế chuỗi Prompt (Prompt Chaining) dưới đây một cách chi tiết, logic và có tính ứng dụng thực tế cao. 

BỐI CẢNH VÀ MỤC TIÊU BÀI TOÁN Phòng Marketing cần sản xuất một bài PR chuyên sâu (độ dài khoảng 1.000 \- 1.500 từ) để giới thiệu giải pháp AI Chatbot mới dành cho doanh nghiệp. Do việc dùng một prompt đơn lẻ dễ khiến nội dung bị hời hợt, lặp ý và đứt gãy mạch văn, bạn cần thiết kế một quy trình Prompt Chaining gồm 3 bước độc lập nhằm kiểm soát ngữ cảnh liên tiếp và duy trì tính nhất quán từ đầu đến cuối.

YÊU CẦU CHI TIẾT CẦN THỰC HIỆN Hãy trình bày bài giải theo cấu trúc rõ ràng gồm các phần sau:

1. Thiết kế quy trình Prompt Chaining 3 bước:

Prompt 1: Phân tích đối tượng khách hàng mục tiêu (người ra quyết định và người trực tiếp vận hành) và xây dựng danh sách các nỗi đau (pain points) cụ thể mà giải pháp AI Chatbot giải quyết.

Prompt 2: Bắt buộc lấy kết quả đầu ra của Prompt 1 làm đầu vào để thiết lập dàn ý chi tiết (Outline) chuẩn SEO cho bài PR, phân bổ định mức số từ hợp lý cho từng phần để tổng bài đạt 1.000 \- 1.500 từ.

Prompt 3: Bắt buộc lấy dàn ý từ Prompt 2 (và dữ liệu từ Prompt 1 nếu cần) để triển khai viết chi tiết từng phần và tối ưu hóa từ khóa SEO.

2. Quy tắc truyền dữ liệu và Khóa ngữ cảnh giữa các bước:

Quy định rõ cấu trúc định dạng dữ liệu đầu ra của bước trước và đầu vào bắt buộc của bước sau để đảm bảo AI không tự ý thay đổi góc nhìn hay bỏ sót ý.

3. Cơ chế xử lý đứt gãy ngữ cảnh khi chạm giới hạn độ dài (Max Token):

Thiết lập quy tắc xử lý khi AI viết bài dài bị ngắt quãng đột ngột giữa chừng.

Cung cấp một câu lệnh điều khiển tiếp tục tạo nội dung (Continuation Prompt) chính xác để AI nối tiếp hoàn hảo ngay từ câu/từ đang viết dở mà không lặp lại đoạn trước, không tóm tắt qua loa các phần sau và không làm lệch giọng điệu.

4. Đảm bảo cấu trúc chuẩn SEO cho bài PR đầu ra ở Bước 3:

Tiêu đề thu hút (Headline) chứa từ khóa chính.

Đoạn mở đầu (Lead) hấp dẫn, đánh trực diện vào pain points.

Hệ thống các tiêu đề con phân cấp rõ ràng (H2, H3) bám sát dàn ý.

Lời kêu gọi hành động (CTA) rõ ràng, thuyết phục ở cuối bài.

RÀNG BUỘC KỸ THUẬT BẮT BUỘC

Tuyệt đối không gộp chung 3 bước vào 1 prompt duy nhất.

Thiết lập chỉ thị khóa chặt giọng điệu xuyên suốt các prompt thành phần: duy trì tone chuyên nghiệp, tin cậy, khách quan, tránh từ ngữ quảng cáo sáo rỗng.

Cơ chế nối tiếp khi bị ngắt quãng phải đảm bảo khớp chính xác về mặt ngữ pháp và mạch văn với câu bị cắt trước đó.

