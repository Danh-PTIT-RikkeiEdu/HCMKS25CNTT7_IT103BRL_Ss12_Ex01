Phân tích lỗi & Lập bảng Test Cases
1. Phân tích lỗi
 Lỗi do từ ngày 3 đã chuyển về bản miễn phí do đoạn >= 3 thay thành > 3 là oke.
2. Test case
a. 
Trường hợp kiểm thử: Nợ cước đúng 3 ngày (Trong hạn)
Dữ liệu đầu vào: subscriptions.daysOverdue = 3
Kết quả sai thực tế: Bị hạ hạng xuông Free
Kết quả đúng mong đợi: vẫn giữ nguyên và status thay đổi

b. 
Trường hợp kiểm thử: Nợ cước 4 ngày (Đã quá hạn)
Dữ liệu đầu vào: subscriptions.daysOverdue = 4
Kết quả sai thực tế: ko sai thực tế do xét trên điều kiện >= 3 thì 4 vẫn đúng mong đợi.
Kết quả đúng mong đợi: Bị hạ xuống Free
