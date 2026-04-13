PHẦN 1: NỀN TẢNG HẠ TẦNG (INFRASTRUCTURE)

Phần này tập trung vào không gian lưu trữ và môi trường vật lý để duy trì sự tồn tại của một website trên internet.
1. Datacenter (Trung tâm dữ liệu)
Định nghĩa: Là "Trụ sở" khổng lồ chứa hàng nghìn máy chủ. Đây là môi trường vật lý được thiết kế đặc biệt để bảo vệ máy tính khỏi mọi tác động bên ngoài.
Các thành phần thiết yếu:
Nguồn điện: Phải có điện lưới, bộ lưu điện (UPS) và máy phát điện dự phòng để máy chủ không bao giờ tắt.
Làm mát: Hệ thống máy lạnh công suất lớn giữ nhiệt độ ổn định (20-24°C) để máy không bị quá nhiệt.
An ninh: Camera 24/7, khóa từ, chống cháy bằng khí (không dùng nước để tránh hỏng thiết bị).
Tiêu chuẩn: Thường được đánh giá qua các cấp độ (Tier). Tier 3 là tiêu chuẩn phổ biến nhất tại Việt Nam, đảm bảo hoạt động liên tục 99.982%.
3. Server (Máy chủ vật lý)
Định nghĩa: Là một chiếc máy tính có cấu hình cực mạnh, được thiết kế để chạy liên tục năm này qua năm khác.
Vai trò: Là "Cái tủ" chứa toàn bộ mã nguồn, hình ảnh và cơ sở dữ liệu của website.
Đặc điểm: Không có màn hình hay bàn phím đi kèm như máy tính bàn (PC), mọi thao tác đều thực hiện từ xa qua mạng.
4. VPS (Virtual Private Server - Máy chủ ảo)
Định nghĩa: Là một phần của máy chủ vật lý được chia ra bằng công nghệ ảo hóa.
Đặc điểm: * Mỗi VPS có hệ điều hành, CPU và RAM riêng biệt, không dùng chung với ai.
Ưu điểm: Bảo mật cao, hiệu suất ổn định, toàn quyền cài đặt phần mềm (như aaPanel).
Đối tượng: Phù hợp cho website bán hàng, doanh nghiệp hoặc người cần cài đặt ứng dụng riêng.
5. Hosting (Lưu trữ dùng chung)
Định nghĩa: Là hình thức chia một máy chủ thành rất nhiều ngăn nhỏ để cho thuê.
Đặc điểm:
Nhiều website cùng chạy trên một tài nguyên máy chủ (dùng chung CPU, RAM).
Ưu điểm: Giá rẻ nhất, dễ sử dụng vì nhà cung cấp đã cài sẵn mọi thứ.
Hạn chế: Nếu một website trên cùng server bị tấn công hoặc quá tải, website của bạn có thể bị chậm theo.
Đối tượng: Phù hợp cho blog cá nhân, website giới thiệu nhỏ.


PHẦN 2: PHẦN CỨNG MÁY CHỦ (HARDWARE)
Phần này giúp bạn hiểu về sức mạnh nội lực bên trong của một Server hoặc VPS.
1. CPU (Central Processing Unit - Bộ vi xử lý)
Định nghĩa: Là "Bộ não" trung tâm, nơi tiếp nhận và xử lý mọi yêu cầu (request) từ người dùng gửi đến website.
Các chỉ số cần lưu ý:
Số Nhân (Cores/vCPU): Càng nhiều nhân, máy chủ càng làm được nhiều việc cùng lúc. Giống như một siêu thị có nhiều quầy thanh toán thì khách không phải chờ lâu.
Xung nhịp (Clock Speed - GHz): Tốc độ xử lý của từng nhân. Xung nhịp càng cao, việc xử lý một lệnh phức tạp càng nhanh.
CPU Máy chủ (Xeon/EPYC): Khác với CPU máy tính thường, CPU server được thiết kế để chạy 24/7 mà không cần tắt máy, chịu được nhiệt độ cao và áp lực công việc liên tục.
2. RAM (Random Access Memory - Bộ nhớ tạm)
Định nghĩa: Là "Mặt bàn làm việc" của CPU. Mọi dữ liệu đang xử lý đều phải đặt lên RAM.
RAM ECC (Error Correction Code): Đây là loại RAM chuyên dụng cho máy chủ.
Tính năng: Tự động phát hiện và sửa các lỗi dữ liệu phát sinh.
Lợi ích: Ngăn chặn tình trạng treo máy (crash) hoặc lỗi màn hình xanh, giúp hệ thống hoạt động cực kỳ ổn định.
Dung lượng RAM: Website càng nặng (như web bán hàng, diễn đàn) thì càng cần nhiều RAM để không bị lag khi có nhiều khách truy cập cùng lúc.


