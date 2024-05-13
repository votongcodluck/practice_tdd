# Thực hành TDD
## Yêu cầu
- Viết hàm giải phương trình bậc 3 (bạn có thể chọn giải phương trình bậc 2 hoặc 1 bài toán khác)
- Dạng phương trình: ax^3 + bx^2 + cx + d = 0
- Trả về nghiệm dạng mảng, trả về mảng rỗng nếu vô nghiệm
- Nếu a = 0 => trả về giải phương trình bậc 2: bx^2 + cx + d = 0; ...
## Cách thực hiện
- Tạo 1 repository trên github hoặc gitlab
- Mỗi vòng lặp (từ bước 2 - 6) tao 1 commit
- Điền link repository [vào đây](https://docs.google.com/spreadsheets/d/1VWgBO0Bsrb3QYxQGcmwyrjeiLwSBqgSG7lKdMTrs27M/edit?usp=sharing) để nộp bài

# Hướng dẫn thực hành TDD
## Bước 1: Xác định yêu cầu và tạo danh sách test case
1. Xác định chức năng hoặc tính năng mới mà bạn muốn thêm vào hệ thống.
2. Chia nhỏ chức năng thành các yêu cầu cụ thể và rõ ràng.
3. Tạo danh sách test case từ các yêu cầu đã xác định, bao gồm các trường hợp biên, dữ liệu đầu vào không hợp lệ và các tình huống không mong muốn.

## Bước 2: Viết test
1. Viết một test đơn giản mô tả một phần của chức năng bạn muốn thêm vào.
2. Test này sẽ thất bại ban đầu vì chức năng đó chưa được triển khai.

## Bước 3: Chạy test
1. Chạy test bạn đã viết. Đảm bảo nó thất bại vì chức năng đang chưa được triển khai.

## Bước 4: Triển khai mã nguồn
1. Viết mã nguồn cần thiết để làm cho test của bạn chạy qua mà không gặp lỗi.
2. Hãy tập trung vào việc làm cho test của bạn thông qua mà không quan tâm đến hiệu suất hoặc cấu trúc mã nguồn.

## Bước 5: Chạy lại test
1. Chạy lại test sau khi bạn triển khai mã nguồn.
2. Đảm bảo rằng test vẫn chạy qua mà không gặp lỗi.

## Bước 6: Tối ưu mã nguồn
1. Kiểm tra và cải thiện mã nguồn của bạn sau khi test đã chạy qua.
2. Đảm bảo mã nguồn của bạn là sạch sẽ, dễ đọc và dễ bảo trì.

## Lặp lại các bước 2-6
1. Lặp lại các bước viết test, triển khai mã nguồn, và tối ưu mã nguồn cho mỗi phần của chức năng bạn muốn thêm vào.
2. Mỗi lần lặp lại, hãy viết các test phức tạp hơn để kiểm tra các trường hợp biên khác nhau và các tình huống không mong muốn.
3. Luôn chạy test sau mỗi lần thay đổi mã nguồn.

## Lưu ý
- Luôn chạy test sau mỗi lần thay đổi mã nguồn.
- Viết test dựa trên các trường hợp biên, dữ liệu đầu vào không hợp lệ và các tình huống không mong muốn.
- Hãy tập trung vào việc viết test một cách tự động và minh bạch.
