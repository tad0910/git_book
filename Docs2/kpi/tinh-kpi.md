---
description: >-
  Chức năng này giúp Phòng Nhân sự/Quản trị viên tổng hợp số liệu từ các phân hệ
  con (Giảng dạy, NCKH, Giờ khác) để ra kết quả đánh giá cuối cùng.
---

# Tính KPI

## Tính KPI

#### 1. Truy cập và Xem Tổng quan (Dashboard)

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FywVdyllN6ptC2mBZrL4x%2Fimage.png?alt=media&#x26;token=45a3cfb1-e375-46ca-a104-26770a9e8ec5" alt=""><figcaption><p>Hình 1</p></figcaption></figure>

Khi chọn menu KPI ở thanh bên trái, màn hình Tổng quan sẽ hiện ra (_Hình 1_). Đây là nơi theo dõi sức khỏe KPI toàn trường.

* Bộ lọc thời gian: Chọn năm học hoặc kỳ đánh giá (Ví dụ: _01/04/2024 đến 31/03/2025_) để hệ thống lấy dữ liệu.
* Thực hiện tính toán: Nhấn nút Tính KPI (màu cam).
  * _Lưu ý:_ Chức năng này sẽ kích hoạt hệ thống quét lại toàn bộ dữ liệu giảng dạy, nghiên cứu khoa học và các giờ khác đã được nhập/duyệt để cập nhật trạng thái mới nhất cho tất cả giảng viên.
* Các chỉ số chính:
  * Biểu đồ tròn: Tỉ lệ hoàn thành của 3 mảng (Giảng dạy, NCKH, Nhiệm vụ khác).
  * Bảng thống kê: So sánh tổng "Số giờ định mức" (Target) và "Số giờ đã thực hiện" (Actual). Hệ thống tự động tính ra số giờ "Thiếu" hoặc "Dư" của toàn trường.

#### 2. Theo dõi Danh sách KPI Giảng viên

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2F0NNNq0zsuPDRHb5zGsNq%2Fimage.png?alt=media&#x26;token=3ed3a9f3-9c52-4d9b-b7d7-f90aa01a278a" alt=""><figcaption><p>Hình 2</p></figcaption></figure>

Chuyển sang tab Dữ liệu KPI giảng viên (_Hình 2_) để xem chi tiết từng người.

* Trạng thái ĐẠT/CHƯA ĐẠT: Cột "Kết quả" hiển thị nhanh trạng thái của giảng viên.
* Thanh tiến độ (Progress Bar):
  * Màu xanh lá: Đã hoàn thành hoặc vượt chỉ tiêu (100% trở lên).
  * Màu đỏ: Chưa hoàn thành hoặc mức độ hoàn thành thấp.
  * _Ví dụ trong hình:_ Giảng viên Lê Thị Thức đạt 100% giảng dạy, 95.64% NCKH nhưng vẫn "CHƯA ĐẠT" (có thể do thiếu giờ nhiệm vụ khác).
* Xuất báo cáo: Nhấn nút Tải xuống (Excel) màu xanh lá để trích xuất danh sách này phục vụ báo cáo.

#### 3. Xem chi tiết & Logic xét duyệt cá nhân

Để xem tại sao một giảng viên "CHƯA ĐẠT", hãy bấm vào tên của họ trong danh sách. Màn hình KPI cá nhân sẽ hiện ra (_Hình 3_).

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FNOCGoJnwzSg6d9nNQ9w7%2Fimage.png?alt=media&#x26;token=f1cc60ce-2449-495e-8756-e86a31c2e542" alt=""><figcaption><p>Hình 3</p></figcaption></figure>

**A. Khu vực Hồ sơ & Cảnh báo**

* Hiển thị ảnh đại diện, thông tin liên lạc.
* Thẻ trạng thái lớn (Màu đỏ/Xanh) cho biết kết quả cuối cùng.
* Các thẻ phần trăm bên phải cảnh báo mức độ hoàn thành từng mảng.

**B. Bảng kết quả xét (Quan trọng)**

Đây là bảng giải trình cách tính toán của hệ thống:

* Số giờ định mức: Chỉ tiêu nhà trường giao cho giảng viên.
* Số giờ đã thực hiện: Tổng số giờ giảng viên làm được thực tế.
* Số giờ hoàn thành sau bù trừ:
  * Hệ thống có logic "Bù trừ". Ví dụ: Nếu giờ Giảng dạy dư, có thể bù sang NCKH (tùy quy chế).
  * _Quan sát hình 3 (Lê Thị Thức):_
    * Giảng dạy: Thực hiện 497 (Định mức 310.5) -> Dư.
    * NCKH: Thực hiện 0 (Định mức 195) -> Thiếu.
    * Kết quả dòng NCKH có dấu (-) màu đỏ -> Bị đánh trượt tiêu chí này.
* Kết quả: Dấu tích xanh (Đạt) hoặc dấu trừ đỏ (Không đạt) cho từng mục.

**C. Lịch sử khai báo**

Phần cuối trang liệt kê danh sách "Giờ khác đã khai báo", giúp đối chiếu xem giảng viên đã nhập liệu những gì và trạng thái duyệt ra sao.
