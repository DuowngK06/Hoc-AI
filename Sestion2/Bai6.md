1. Câu hỏi gửi cho AI

Prompt:
“Viết một đoạn code kiểm tra số nguyên tố bằng ngôn ngữ bạn chọn (C/C++, Python, Java…).”

2. Đoạn code AI tạo ra (ví dụ từ ChatGPT)

Giả sử AI chọn Python và trả về:
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, n):
        if n % i == 0:
            return False
    return True

num = int(input("Nhập số cần kiểm tra: "))
if is_prime(num):
    print(num, "là số nguyên tố")
else:
    print(num, "không phải số nguyên tố")
3. Chạy thử code bằng IDE/Compiler

Công cụ sử dụng: VS Code + Python 3.10
Test thử các giá trị:

Nhập: 2 → đúng

Nhập: 7 → đúng

Nhập: 12 → đúng

Nhập: 1 → đúng

Kết quả:
→ Chương trình chạy đúng, không có lỗi runtime, logic cũng ổn.

4. Kiểm chứng như thế nào?

Chạy thử với nhiều test case, bao gồm số nhỏ, số lớn và số biên (0, 1, 2).

So sánh với kết quả từ trang kiểm tra số nguyên tố online.

Phân tích xem thuật toán có đúng về mặt lý thuyết (vòng lặp từ 2 → n-1, trả về đúng giá trị).

5. Trường hợp mô phỏng nếu AI viết sai (ví dụ thường gặp)

Nhiều AI đôi khi tạo ra đoạn code sai như:

for i in range(2, n//2):


→ Sai vì range(n//2) không kiểm tra đủ các ước, dẫn đến sai với các số như 9 (nửa trên bị bỏ qua).

Cách sửa đúng:

for i in range(2, int(n**0.5) + 1):


Vì sao AI sai?

AI đôi khi nhầm lẫn giữa kiểm tra đến n/2 và kiểm tra “tối ưu” đến sqrt(n), dẫn đến logic thiếu.

Đây là lỗi phổ biến do AI “suy diễn sai” (hallucination).

6. Kết luận
Bài học rút ra

AI có thể tạo ra code đúng, nhưng không được tin tuyệt đối.

Tự chạy test và phân tích logic là bước bắt buộc.

Không có kiểm chứng → rất dễ mắc lỗi ngầm, đặc biệt trong thuật toán.

Làm gì để không lệ thuộc?

Luôn đọc hiểu code thay vì copy-paste.

Kiểm tra bằng test case đa dạng (biên, lớn, nhỏ, bất thường).

Học nguyên lý thuật toán để tự phát hiện lỗi AI.

Dùng AI như “người hỗ trợ”, không phải “người làm thay”.