ĐỀ CƯƠNG ĐỀ TÀI CUỐI KỲ: ỨNG DỤNG CHƠI CARO QUA MẠNG (CLIENT – SERVER)
🧩 1. Tên đề tài
Xây dựng ứng dụng “Caro Online” sử dụng mô hình Client – Server

🧠 2. Mục tiêu đề tài
Xây dựng ứng dụng trò chơi Caro (Cờ ca-rô) cho phép hai người chơi đấu với nhau qua mạng LAN.
Áp dụng mô hình Client–Server để truyền dữ liệu giữa hai người chơi.
Hiểu cách sử dụng Socket TCP/IP để thiết lập kết nối và gửi/nhận dữ liệu trong mạng.
Rèn luyện kỹ năng lập trình mạng và giao diện người dùng (WinForms).

⚙️ 3. Công cụ và công nghệ sử dụng
Ngôn ngữ: C#
IDE: Visual Studio
Thư viện: System.Net, System.Net.Sockets, System.Threading, System.Drawing
Giao thức: TCP (hoặc UDP nếu muốn thử thách)

🧱 4. Mô tả hệ thống
Ứng dụng gồm 2 phần chính:
Server:
oQuản lý kết nối từ 2 Client.
oXử lý và gửi trạng thái bàn cờ đến các Client.
oThông báo kết quả thắng/thua/hòa.
Client:
oKết nối đến Server bằng IP và Port.
oHiển thị bàn cờ (WinForms).
oGửi nước đi của người chơi đến Server.
oNhận và hiển thị nước đi của đối thủ.

🔁 5. Quy trình hoạt động
1.Server khởi động, chờ 2 client kết nối.
2.Mỗi client nhập IP server → kết nối.
3.Khi đủ 2 người, server tạo bàn cờ và gửi dữ liệu ban đầu.
4.Người chơi lần lượt đánh, client gửi vị trí đến server.
5.Server cập nhật trạng thái và gửi nước đi đó đến người còn lại.
6.Khi có người thắng hoặc hòa, server thông báo kết quả.
7.Người chơi có thể chọn chơi lại hoặc thoát.

🧩 6. Phạm vi thực hiện
Hỗ trợ 2 người chơi qua mạng LAN.
Giao diện WinForms trực quan.
Không cần cơ sở dữ liệu.
(Tùy chọn nâng cao) Thêm tính năng chat hoặc tính điểm.

📈 7. Kết quả dự kiến
Ứng dụng chạy ổn định trên môi trường mạng nội bộ.
Trò chơi có thể kết nối 2 máy thật hoặc 2 cửa sổ khác nhau trên 1 máy (localhost).
Hiểu rõ quy trình lập trình socket và luồng (thread)
