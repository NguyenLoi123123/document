## Mục đích

- Đã cấu hình sẵn làm cho mỗi tuần, nếu muốn thêm kế hoạch tháng hay năm thì năm thêm board khác

## Cài đặt

- Link liên kết bảng: [Trello](https://trello.com/invite/b/NW5LlZr0/ATTI9b56f17ab4d173d971db984f67d57bbe50C6F077/studyplan)
- Sau khi liên kết mình cần vào cài đặt và copy nó thành bảng mới
- Vào tự động hóa/rules/ => set all (enable on this board) 

## Chức năng

- Mỗi ngày sẽ tự động có email nhắc nhở setup công việc mỗi ngày

- Khi tạo từ **Mục tiêu tuần** sẽ tư động set ngày bắt đầu (hôm nay) và ngày kết thúc  (6 ngày tiếp theo) và tag thẻ **Cần làm**

- Từ thứ 2 đến chủ nhật chỉ chỉnh lại thời gian bắt đầu công việc, và tag thẻ **đang làm**

- **Card Button** `Completed` xóa hết `label` cũ, tự động di chuyển đến **Đã hoàn thành**, check đã hoàn thành đúng thời hạn, xóa thành viên ra, và **post comment** "Đã hoàn thành công việc vào lúc {time.now()}"

- **Card Button** `Start Again` tự động di chuyển đến **Mục tiêu tuần**, **uncheck** đã hoàn thành đúng thời hạn, xóa thành viên ra, và **post comment** "Đã bắt đầu lại vào lúc time.now()". Và **Title card** thay đổi thành "{current_name} forcus"

  