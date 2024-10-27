# Hanafuda Auto Deposit

Thực hiện các giao dịch tự động dưới dạng tiền gửi ETH vào một số hợp đồng nhất định trên Mạng HANA.

## Đăng ký với HanaFuda (Mạng Hana)

- Đăng ký tại đây: https://hanafuda.hana.network
- 𝗨𝘀𝗲 𝗮𝗰𝗰𝗲𝘀𝘀 𝗰𝗼𝗱𝗲: V4EEV0
- Gửi $1-$2 vào mạng BASE để được phí gas thấp
- Vào bảng điều khiển
- Kiếm điểm thông qua Grow and Draw Hanafuda
- Thực hiện 5.000 giao dịch để kiếm 300/giờ (để mở khóa thẻ và nhận điểm).
- Thực hiện 10.000 giao dịch để kiếm 643 hộp Garden Rewards (để mở khóa thẻ sưu tập).

## Tính năng

- Tự động gửi giao dịch từ nhiều địa chỉ
- Theo dõi và cập nhật nonce cho từng khóa riêng để tránh xung đột khi gửi giao dịch.
- Bắt ngoại lệ khi giao dịch không thành công và xử lý lỗi liên quan đến nonce (ví dụ: nonce quá thấp).
- Cung cấp tùy chọn ngôn ngữ (tiếng Việt hoặc tiếng Anh) cho người dùng.
- Hiển thị thông báo trạng thái giao dịch (thành công hoặc thất bại) cùng với thông tin chi tiết.
- Tính toán và hiển thị thời gian hoàn thành của tất cả các giao dịch.

## Module:

- Python 3.7 trở lên
- `pip` (trình cài đặt gói Python)

## Cài đặt

1. **Sao chép kho lưu trữ này:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
git clone https://github.com/thog9/Hanafuda-testnet.git
```
```sh
cd Hanafuda-testnet
```
2. **Cài đặt Module:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
pip install -r requirements.txt
```
3. **Chạy:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
python bot.py
```