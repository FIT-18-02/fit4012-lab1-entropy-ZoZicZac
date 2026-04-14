# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa | 0 | 8 |aaaa: Chỉ có 1 ký tự lặp lại → không có độ bất định → entropy = 0, dư thừa rất cao.|
| abcd | 2 | 6 |abcd: Các ký tự khác nhau hoàn toàn → entropy cao hơn → ít dư thừa hơn.|
| hello world | 2.84535 | 5.15465 |hello world: Phân bố ký tự không đều → entropy trung bình → vẫn còn dư thừa nhưng thấp hơn “aaaa”.

|

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | Không tồn tại |

## 4. Kết luận
Qua bài lab, em hiểu rõ hơn về entropy và vai trò của nó trong việc đo độ ngẫu nhiên của dữ liệu. Đồng thời, em nắm được cách tính nghịch đảo modulo và điều kiện để nó tồn tại (hai số phải nguyên tố cùng nhau). Khó khăn lớn nhất là thao tác chạy chương trình và xử lý lỗi môi trường. Sau khi thực hành nhiều test case, em hiểu rõ hơn bản chất của entropy và ứng dụng của modulo inverse trong mật mã học.