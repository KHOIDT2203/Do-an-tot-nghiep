#  ĐỒ ÁN TỐT NGHIỆP
Đề tài: Thiết kế mạch IoT quản lý chất lượng nước hồ nuôi tôm cá
## CÁC ĐẶC ĐIỂM CHÍNH
- Mạch sử dụng ESP32 Wroom 32U làm bộ xử lý trung tâm
- Thiết kế 3 mode kết nối: WiFi, Ethernet, 4G
- Kết nối MQTT đẩy dữ liệu lên Thingsboard
- Ethernet sử dụng LAN8720 kết nối RMII với ESP32
- Module sim 4G A7680C
- Nguồn: mạch được thiết kế với dải điện áp nguồn vào rộng, từ 7-24 VDC; nguồn đầu ra 5VDC, 4VDC có dòng lớn nhất 3A
- Các cảm biến, LCD, hệ thống nút nhấn kết nối với ESP32 bằng I2C nhằm tối ưu hóa mạch
