# Wifi-Checker-Beta

> Công cụ chuyên nghiệp để giám sát và phân tích mạng nội bộ (LAN) của bạn.

## Phiên bản Beta

Ứng dụng WiFi Checker hiện đang trong giai đoạn thử nghiệm.

Một số tính năng có thể chưa hoàn thiện hoặc gặp lỗi trong quá trình sử dụng. Mọi đóng góp của bạn đều giúp chúng tôi hoàn thiện sản phẩm.

## Giới thiệu

WiFi Checker được thiết kế để giúp người dùng phổ thông lẫn kỹ thuật viên có cái nhìn chi tiết về các thiết bị đang kết nối trong mạng, kiểm tra độ trễ và phát hiện các bất thường về kết nối.

## Màn hình chính

Giao diện chính cung cấp cái nhìn tổng quan về trạng thái mạng hiện tại của thiết bị.

Tại đây bạn có thể thấy:

- Tên WiFi đang kết nối (SSID)
- Địa chỉ IP nội bộ
- Cường độ tín hiệu

### Hình ảnh

![Màn hình chính của ứng dụng](https://6a8933a797833836f65581dd.imgix.net/sandbox/Screenshot_20260822_115835_Wifi%20Checker.jpg)

_Hình 1: Giao diện tổng quan và trạng thái kết nối._

## Terminal & Logs

Hệ thống Terminal tích hợp cho phép bạn theo dõi các hoạt động của ứng dụng theo thời gian thực.

Mỗi hành động quét hoặc kiểm tra đều được ghi lại với mã màu cụ thể:

- **Màu Trắng:** Thông tin hệ thống thông thường.
- **Màu Xanh:** Quá trình quét thành công hoặc thiết bị phản hồi.
- **Màu Vàng:** Cảnh báo hoặc thiết bị không phản hồi (Request Timeout).
- **Màu Đỏ:** Lỗi kết nối nghiêm trọng.

### Hình ảnh

![Giao diện Terminal logs](https://6a8933a797833836f65581dd.imgix.net/Screenshot_20260822_115835_Wifi%20Checker.jpg)

_Hình 2: Theo dõi quá trình xử lý qua Terminal._

## Quá trình quét LAN

Khi bắt đầu quét mạng (Scan), WiFi Checker sẽ gửi các gói tin ICMP đến dải IP trong mạng nội bộ của bạn.

Quá trình này giúp liệt kê tất cả các thiết bị như:

- Điện thoại
- Laptop
- Camera an ninh
- Các thiết bị IoT khác

> **Lưu ý:** Quá trình quét có thể mất từ 30 giây đến 2 phút tùy thuộc vào số lượng thiết bị và chất lượng đường truyền mạng.

## Cài đặt

Trong phần cài đặt, bạn có thể tùy chỉnh các thông số kỹ thuật để phù hợp với nhu cầu:

- **Timeout:** Thời gian chờ phản hồi từ thiết bị, mặc định `1000ms`.
- **Threads:** Số lượng luồng quét đồng thời. Tăng tốc độ quét nhưng tốn tài nguyên hơn.
- **Giao diện:** Chuyển đổi giữa chế độ Sáng (Light) và Tối (Dark).

## Hạn chế & Phản hồi

Do đang ở bản Beta, ứng dụng có một số hạn chế kỹ thuật:

- Chưa hỗ trợ quét các mạng con (Subnets) phức tạp.
- Một số thiết bị có tường lửa mạnh có thể không hiển thị tên (Hostname).

## Phản hồi

Bạn phát hiện lỗi?

Hãy gửi phản hồi cho Moon Studio tại:

**thienanaccphu12@gmail.com**

## Moon Studio

© 2024 Moon Studio. Tất cả các quyền được bảo lưu.

**Phiên bản tài liệu:** 0.9.2 (Beta)
