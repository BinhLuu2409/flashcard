MANDARIN MASTER — BẢN WEBSITE CẬP NHẬT ĐỌC JSON ONLINE

1. Giải nén ZIP, upload TOÀN BỘ nội dung thư mục này vào thư mục gốc GitHub repository (cùng cấp index.html).
2. GitHub Settings > Pages > Deploy from branch > main > /(root), nếu chưa bật.
3. Mở website: dữ liệu ở data/vocabulary.json được tải tự động khi mở trang.
4. File JSON trong bản này chỉ là tệp KHUNG, CHƯA chứa bộ 11.000 từ HSK. Nếu chưa thay thế, website dùng 30 từ mẫu tích hợp.
5. Để có hàng nghìn từ, tải bộ JSON HSK đã xác minh, thay thế data/vocabulary.json bằng dữ liệu thật, rồi Commit changes. Không cần sửa index.html.
6. JSON hỗ trợ dạng mảng từ hoặc {"words":[...]}. Mỗi từ nên có: hanzi, pinyin, meaning (nghĩa tiếng Việt), level (ví dụ HSK 1), topic, example, examplePinyin, translation.
7. Dữ liệu chỉ có nghĩa tiếng Anh sẽ được hiển thị theo tiếng Anh, KHÔNG tự dịch thành tiếng Việt. Nên chuẩn hóa trước khi phát hành.
8. Tiến độ cũ trên cùng trình duyệt được giữ trong localStorage; dữ liệu chưa đồng bộ đa thiết bị. Hãy xuất JSON sao lưu trước khi cập nhật.
9. Cài lên iPhone: mở bằng Safari > Chia sẻ > Thêm vào màn hình chính.

LƯU Ý: Đây là bản nâng cấp WEBSITE ĐỂ SẴN SÀNG NHẬN DỮ LIỆU LỚN, KHÔNG phải bản 11.000 từ đã tích hợp.
