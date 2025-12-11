💡 Phân Tích Prompt Chưa Hiệu Quả
Prompt sai: “Viết giúp tôi một đoạn code xử lý chuỗi.”

Kết quả trả về không hiệu quả (chỉ in chuỗi, không xử lý cụ thể) vì những lý do sau:

Thiếu Mục tiêu Xử lý Cụ thể: Cụm từ “xử lý chuỗi” là quá rộng. AI không biết chính xác thao tác nào được yêu cầu (ví dụ: cần đảo ngược chuỗi? chuyển đổi sang chữ hoa? trích xuất dữ liệu? kiểm tra đối xứng?). Khi thiếu mục tiêu, AI thường chọn đoạn code đơn giản và chung chung nhất.

Thiếu Ngữ cảnh về Ngôn ngữ Lập trình và Trình độ: AI không được chỉ dẫn nên dùng ngôn ngữ nào (Python, Java, JavaScript, C++...) và code đó nên phức tạp đến mức nào (dùng hàm có sẵn hay tự viết thuật toán cơ bản). Điều này dẫn đến việc trả về code không phù hợp với khóa học hoặc trình độ người học.

Những gì còn thiếu trong Prompt:
Vai trò của AI: (Ví dụ: Chuyên gia lập trình Python).

Ngôn ngữ Lập trình: (Ví dụ: Python, JavaScript).

Mục tiêu Xử lý Cụ thể: (Ví dụ: kiểm tra chuỗi palindrome).

Ngữ cảnh/Trình độ: (Ví dụ: Dành cho sinh viên mới học, cần giải thích thuật toán).

Định dạng: (Ví dụ: Cần ví dụ minh họa đầu vào/đầu ra, code phải nằm trong khối code).

📝 Viết Lại Prompt Mới (Mục tiêu: Kiểm tra Palindrome)
Tôi sẽ chọn mục tiêu Kiểm tra Palindrome (chuỗi đối xứng) và ngôn ngữ Python để xây dựng lại prompt rõ ràng.

Prompt Mới Hiệu Quả:
Vai trò: Bạn là trợ giảng lập trình Python.

Mục tiêu Xử lý: Hãy viết một hàm bằng ngôn ngữ Python để kiểm tra xem một chuỗi bất kỳ có phải là chuỗi Palindrome (chuỗi đối xứng) hay không (chuỗi đọc xuôi và đọc ngược giống nhau).

Ngữ cảnh: Đoạn code này dành cho sinh viên mới bắt đầu học lập trình, vì vậy, hãy sử dụng cách kiểm tra cơ bản nhất, không dùng các hàm thư viện phức tạp. Đồng thời, giải thích ngắn gọn thuật toán được sử dụng.

Yêu cầu Định dạng:

Trình bày code trong khối code Python.

Cung cấp một ví dụ minh họa với đầu vào là "radar" và đầu ra tương ứng.

Phân tích Prompt Mới:
Vai trò: (Trợ giảng lập trình Python) -> Định hướng AI trả lời bằng kiến thức chuyên môn và có tính hướng dẫn.

Ngôn ngữ: (Python) -> Cụ thể hóa công cụ.

Mục tiêu rõ: (Kiểm tra Palindrome) -> Cung cấp thao tác xử lý chuỗi cụ thể.

Ngữ cảnh: (Sinh viên mới, dùng cách kiểm tra cơ bản, cần giải thích thuật toán) -> Đảm bảo độ phức tạp phù hợp.

Định dạng: (Khối code Python, ví dụ minh họa) -> Giúp kết quả dễ đọc và dễ kiểm chứng.