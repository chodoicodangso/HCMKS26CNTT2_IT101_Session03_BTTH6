1\. Bẫy dữ liệu & Ràng buộc  
Mở file ẩn .env: Trên Windows tích chọn Hidden items trong tab View (trên Linux dùng lệnh ls \-a). Để bảo mật mã API, em thêm .env vào file .gitignore để không bị lộ lên GitHub.  
Tính dung lượng: 1KB x 1.000.000 \= 1000000KB \= 1000MB (khoảng 1GB/Ngày).Phần cứng SoC cần chip nhớ có tốc độ ghi cao để k bị nghẽn dữ liệu.  
2\. 4 tầng DIKW của MoMo-Lite  
Data: Bản ghi giao dịch thô lưu vào máy  
Information: Tổng hợp dữ liệu thô thành báo cáo tháng  
Knowledge: Đối chiếu thông tin với hạn mức để đưa ra cảnh báo  
Wisdom: Đưa ra giải pháp hành động cụ thể để tiết kiệm  
3\. Module Kiến trúc  
Input: Đọc file .env lấy mã API và nhận dữ liệu giao dịch đầu vào.  
Process: Phân loại danh mục, tính toán tổng chi tiêu và so sánh hạn mức   
Output: Hiển thị biểu đồ chi tiêu và gửi thông báo cảnh báo/lời khuyên lên màn hình.