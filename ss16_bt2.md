# Bản thiết kế phân quyền:
| Đối tượng | Mức quyền đúng | Phạm vi chia sẻ | Lý do |
| :---: | :---: | :---: | :---: |
| **Trưởng phòng Nhân sự** | **Owner** | Người sở hữu duy nhất | Để thu hồi quyền của người khác |
| **Các Trưởng bộ phận** | **Commenter** | **Restricted - chỉ mail từng trưởng bộ phận** | Chỉ được nhận xét, không được sửa gốc.  |
| **Nhân viên HR thường** | **Viewer** | **Restricted** | Chỉ xem, không sửa, không share tiếp |
| **Ứng viên bên ngoài** | **No access** | **Remove ngay lập tức** | Tuyệt đối không cho người ngoài xem danh sách CV |

# Kịch bản khi gặp sự cố

Bước 1. Thu hồi quyền hạn của người đó ngay lập tức
Bước 2. Kiểm tra xem họ đã làm gì, khắc phục và báo cáo cho owner ngay lập tức

Bước 3. Báo cáo và xử lý

