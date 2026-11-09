# Bài 5 : Tối ưu quy trình hỗ trợ kỹ thuật nội bộ

## Phần 1 : Lập mẫu bug report template

- **Contex (Môi trường & ngữ cảnh)** :
      - HỆ điều hành 
      - Phiên bản và ứng dụng đang chạy
      - Thao tác vừa thực hiện được
- **Expected behavios**
      - Mô tả hành động đáng lý ra phải xảy ra
- **Actual behavios**
      - Mô tả sự cố thực tế xảy ra
-**LOG (Dấu vết kỹ thuật & Bằng chứng)**
      - *Dán chính xác thông báo lỗi từ Terminal/Console (không chụp ảnh màn hình mờ, ưu tiên text dạng code block):*

## Phần 2 : đề xuất quy trình (Gooling --> community search --> AI translation) trước khi nhờ hỗ trợ

- Bước 1: Googling (Bắt đúng dòng lỗi)

    _ Cách làm: Coppy đúng 1 dòng lỗi chính (bỏ qua đường dẫn dài dòng của máy cá nhân) rồi bọc trong dấu ngoặc kép "" kèm tên công nghệ.
    _ Ví dụ: "port is already allocated" docker
  
- Bước 2: Community Search (Xem cộng đồng sửa thế nào)

    _ GitHub Issues: Vào repo của thư viện/công cụ --> gõ lỗi --> tìm bình luận có nhiều nút 👍 (:+1:) hoặc do trưởng dự án (Maintainer) hướng dẫn.
  
    _ StackOverflow: Thêm site:stackoverflow.com vào Google. Ưu tiên câu trả lời mới, đúng hệ điều hành (Windows/macOS/Linux) đang dùng.
  
- Bước 3: AI Translation (Dịch log ra lệnh sửa)Cách làm:

    _ Quăng cả đoạn log cho AI và yêu cầu trả về lệnh xử lý ngắn gọn.
  
    _ Cú pháp gõ nhanh:"Tôi dùng [Hệ điều hành]. Bị lỗi này khi chạy [Lệnh]: [Dán log]. Yêu cầu dịch sang tiếng việt một cách dễ hiểu và chỉ cách sửa an toàn nhất ."
  
