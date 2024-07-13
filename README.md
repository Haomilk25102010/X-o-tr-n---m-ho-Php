# Xáo trộn mã nguồn php
bảo vệ mã nguồn của bạn tránh bị thay bản quyền mã nguồn
Đây là 1 trình mã hoá xáo trộn mã nguồn php gồm 7 mặt mã nguồn được ghi đè lên nhau chúng tạo ra 1 chuỗi random và được đánh dấu là vô nghĩa để tăng dung lượng tệp tin sau đó liên tục tạo ra và ghi đè lên các mặt còn lại và nén chúng bằng gzcompress, gzencode và sử dụng eval để thực thi đoạn mã bị mã hoá , kết quả sẽ được lưu thêm vào gz để rút gọn dung lượng nhất có thể khi chia sẻ cho người khác
