# Tanuki-keyboard
# Các bước tiến hành phần cứng
Hình ảnh sơ lược mặt sau:
<img src="https://i.imgur.com/ebwRzg7.jpg">
Bước 1: Hàn diode “1N4148” vào PCB. Chú ý hướng lỗ trên PCB từ tròn qua vuông với mọi diode. Xem hình để chú ý hàn không sai (1 Switch tương ứng với 1 diode).
<img src= "https://i.imgur.com/GZ275kG.jpg">
Bước 2: Hàn “HotSwap” chân giả vào PCB. Chú ý hàn không được bít miệng lỗ này (sản phẩm hotswap này có 3 kích cỡ phù hợp với nhiều chân switch khác nhau, thông thường shop chỉ sử dụng loại 1,2mm nên sẽ là loại này được giao)."Liên hệ để thay đổi chân kích cỡ khác nếu muốn"
<img src= "https://i.imgur.com/F12cctS.jpg">
Bước 3: Hàn chân “Reset” và “Điện trở” vào PCB. Với điện trở cần có để sáng led, nếu khó hàn có thể hàn nối 2 điểm lại nên dùng điện trở để đảm bảo tuổi thọ led bạn nhé.
<img src= "https://i.imgur.com/Bt5iDG3.jpg">
<img src= "https://i.imgur.com/vs4g9g9.jpg">
Bước 4: Hàn “Atmega32u4” vào PCB. (Chú ý: nên tính toán cẩn thận để tránh hàn sai, chênh mạch đoạn này sửa lại rất mất thời gian).
<img src= "https://i.imgur.com/VoFa7gl.jpg">
Bước 5: Hàn cố định cổng kết nối Type C cái ngõ ra vào PCB và tiếp tục hàn dây 4 lõi nối tiếp vào đầu đực để cắm vào “Atmega32u4”. (Đây là 1 đoạn nối dài từ “Atmega32u4” ra ngoài, xem thao tác thêm tại video).
<img src= "https://i.imgur.com/6z75f27.jpg">
Bước 6: Nếu có sử dụng Led hàn 4 chân vào vị trí đúng theo nguyên tác. Để led hoạt động hàn điện trở vào vị trí ký hiệu trên mạch.
<img src= "https://i.imgur.com/gPyoFrz.jpg">
Bước 7: Tiến hành lắp Switch, Stab, Keycap vào plate và vào PCB.
Bước 8: Ghép các mảnh Mica còn lại và cố định bằng ốc. Hoàn thiện sản phẩm.
# Các bước tiến hành phần mềm
Tải tại thư mục phía trên hoặc bất cứ đâu
Tải QMK toolbox.exe và file .hex
Mở QMK tool chọn đường dẫn đến file .hex kia và tick ô auto flash, tiếp đó cắm vào bàn phím nhấn nút reset đã hàn. mạch tự nạp và sẽ sáng đèn nếu thành công
<img src= "https://i.imgur.com/IACbN81.png">
<img src= "https://i.imgur.com/COUEOaN.png">
