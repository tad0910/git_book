# Giờ giảng dạy

## Giờ giảng dạy

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2F11wtcKzb0FR5tniVvgdj%2Fimage.png?alt=media&#x26;token=3bb4e5ac-2be4-4fba-8285-44fb91f046d4" alt=""><figcaption></figcaption></figure>

#### Tổng quan

**Giờ giảng dạy** là module quản lý khối lượng giảng dạy của giảng viên, bao gồm:

* Đồng bộ dữ liệu giờ giảng từ hệ thống của trường qua API
* Xem chi tiết giờ giảng theo từng học kỳ, môn học
* Liên kết với kết quả đánh giá của sinh viên
* Thống kê tổng số giờ và số tiết thực tế
* Báo cáo theo đơn vị, theo giảng viên

***

#### 1. Xem danh sách Dữ liệu Giờ giảng dạy

**Bước 1:** Truy cập menu **Giờ giảng dạy** trên thanh menu bên trái

**Bước 2:** Chọn **Dữ liệu** trong submenu

**Bước 3:** Chọn kế hoạch tổng hợp cần xem:

* Click vào dropdown **"Tổng hợp khối lượng từ ngày 01/04/2024 đến 31/03/2025"**
* Chọn chu kỳ tính KPI tương ứng

**Bước 4:** Danh sách hiển thị với các thông tin:

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FYyhpe1djjTAOY4yCffb5%2Fimage.png?alt=media&#x26;token=44824fb7-cc03-4b38-993c-51f89144b9b5" alt=""><figcaption></figcaption></figure>

**Ví dụ dữ liệu:**

* Nguyễn Thị Ngọc Thúy (Mã: 10063) - Tổng: 374.84 giờ / 351 tiết
* Phạm Ngọc Diệp (Mã: 10008) - Tổng: 573.54 giờ / 546 tiết

***

#### 2. Đồng bộ Giờ giảng dạy từ hệ thống trường

**Cách 1: Đồng bộ tự động qua API**

**Bước 1:** Click nút **"Đồng bộ dữ liệu"** (màu đỏ cam) trên thanh công cụ

**Bước 2:** Hệ thống tự động:

* Kết nối API với hệ thống quản lý giảng dạy của trường
* Lấy dữ liệu giờ giảng của tất cả giảng viên
* Link với kết quả đánh giá sinh viên (nếu có)

**Bước 3:** Chờ quá trình đồng bộ hoàn tất

**Bước 4:** Kiểm tra dữ liệu vừa được cập nhật:

* Xem tổng số bản ghi
* So sánh với danh sách giảng viên hiện có
* Kiểm tra các trường hợp bất thường

**Lưu ý:**

* Đồng bộ định kỳ theo lịch: sau mỗi học kỳ, cuối tháng, cuối kỳ
* Dữ liệu đồng bộ sẽ ghi đè lên dữ liệu cũ
* Không thể đồng bộ nếu API của trường chưa được cấu hình

**Cách 2: Tải lên từ file Excel**

**Bước 1:** Click nút **"Tải lên"** trên thanh công cụ

**Bước 2:** Tải file mẫu Excel về (nếu cần)

**Bước 3:** Điền thông tin vào file Excel:

* Cột A: Đơn vị
* Cột B: Mã giảng viên
* Cột C: Họ và đệm
* Cột D: Tên
* Cột E: Tổng số giờ (giờ chuẩn)
* Cột F: Tổng số tiết (tiết thực tế)
* Cột G: Link đánh giá (nếu có)

**Bước 4:** Upload file và chờ xử lý

**Bước 5:** Kiểm tra kết quả import và xử lý lỗi (nếu có)

***

#### 3. Xem và chỉnh sửa chi tiết Điểm đánh giá

**Bước 1:** Tìm giảng viên cần xem chi tiết

**Bước 2:** Click vào link **"Đánh giá"** (màu xanh) ở cột **"Link đánh giá"**

**Bước 3:** Popup **"Điểm đánh giá \[Tên giảng viên]"** hiển thị với các thông tin:

**3.1. Thông tin trong popup**

**Tiêu đề:** "Điểm đánh giá Nguyễn Thị Ngọc Thúy" (ví dụ)

**Các cột dữ liệu:**

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FAgEuWzqmIgAYAvGcUMze%2Fimage.png?alt=media&#x26;token=f70dbf23-1b7a-4759-b405-e8cf7bddc626" alt=""><figcaption></figcaption></figure>

**Ví dụ:**

* Học kỳ 1 - Điểm số: 0 - Link: (trống)

**3.2. Thêm điểm đánh giá mới**

**Bước 1:** Trong popup, click nút **"+ Thêm"**

**Bước 2:** Nhập thông tin:

* **Học kỳ**: Chọn hoặc nhập số học kỳ (1, 2, 3...)
* **Điểm số**: Nhập điểm trung bình (0-10)
* **Link minh chứng**: Dán link đến trang đánh giá chi tiết

**Bước 3:** Click icon **lưu (💾)** để hoàn tất

**3.3. Sửa điểm đánh giá**

**Bước 1:** Click icon **bút chì (✏️)** bên cạnh học kỳ cần sửa

**Bước 2:** Cập nhật thông tin:

* Sửa điểm số
* Thay đổi link minh chứng

**Bước 3:** Click **"Lưu"** hoặc click ra ngoài để lưu tự động

**3.4. Xóa điểm đánh giá**

**Bước 1:** Click icon **xóa (⊗)** màu đỏ bên cạnh học kỳ cần xóa

**Bước 2:** Xác nhận xóa

**Bước 3:** Dữ liệu được xóa khỏi hệ thống

**3.5. Đóng popup**

Click nút **"X"** ở góc phải trên hoặc click ra ngoài popup để đóng

***

#### 4. Thêm dữ liệu Giờ giảng dạy thủ công

**Bước 1:** Click nút **"+ Thêm"** ở góc trên bên trái

**Bước 2:** Điền thông tin trong form:

* **Đơn vị**: Chọn đơn vị trực thuộc
* **Mã GV**: Nhập hoặc chọn mã giảng viên
* **Họ và đệm**: Tự động điền (hoặc nhập nếu chưa có)
* **Tên**: Tự động điền (hoặc nhập nếu chưa có)
* **Tổng số giờ**: Nhập tổng giờ chuẩn
* **Tổng số tiết**: Nhập tổng tiết thực tế

**Bước 3:** Click **"Lưu"** để hoàn tất

**Lưu ý:** Chức năng này chỉ dùng trong trường hợp:

* Cần bổ sung dữ liệu thủ công
* API chưa có dữ liệu của giảng viên mới
* Điều chỉnh số liệu đặc biệt

***

#### 5. Sửa dữ liệu Giờ giảng dạy

**Bước 1:** Tìm giảng viên cần sửa trong danh sách

**Bước 2:** Click icon **bút chì (✏️)** màu xanh ở cột **"Thao tác"**

**Bước 3:** Cập nhật thông tin cần thay đổi:

* Sửa tổng số giờ
* Sửa tổng số tiết
* Cập nhật link đánh giá

**Bước 4:** Click **"Lưu"** để cập nhật

**Cảnh báo:**

* Không nên sửa dữ liệu đã đồng bộ từ hệ thống trường
* Nếu sửa, dữ liệu sẽ bị ghi đè khi đồng bộ lần sau
* Nên ghi chú lý do sửa để theo dõi

***

#### 6. Xóa dữ liệu Giờ giảng dạy

**Bước 1:** Tìm giảng viên cần xóa

**Bước 2:** Click icon **thùng rác (🗑️)** màu đỏ ở cột **"Thao tác"**

**Bước 3:** Xác nhận xóa trong hộp thoại cảnh báo

**Lưu ý:**

* Xóa dữ liệu sẽ ảnh hưởng đến báo cáo KPI
* Không thể khôi phục sau khi xóa
* Cân nhắc đồng bộ lại thay vì xóa

***

#### 7. Tìm kiếm và lọc dữ liệu

**Tìm kiếm**

**Bước 1:** Click icon **kính lúp (🔍)** ở góc phải

**Bước 2:** Nhập từ khóa tìm kiếm:

* Mã giảng viên
* Họ tên giảng viên
* Tên đơn vị

**Bước 3:** Kết quả hiển thị ngay lập tức

**Lọc dữ liệu**

**Bước 1:** Click icon **phễu (🔽)** để mở bộ lọc

**Bước 2:** Chọn tiêu chí lọc:

* **Theo đơn vị**: Chọn Khoa, Trung tâm cụ thể
* **Theo loại giảng viên, chức vụ**

**Bước 3:** Click **"Áp dụng"** để xem kết quả

**Bước 4:** Click **"Xóa bộ lọc"** để về danh sách đầy đủ

***

#### 8. Sắp xếp dữ liệu

**Cách sử dụng:**

* Click vào tiêu đề cột có icon **⇅** để sắp xếp
* Click lần 1: Sắp xếp tăng dần (A-Z, 0-9)
* Click lần 2: Sắp xếp giảm dần (Z-A, 9-0)
* Click lần 3: Về thứ tự mặc định

**Các cột có thể sắp xếp:**

* Đơn vị (A-Z)
* Mã GV (tăng/giảm dần)
* Họ và tên (A-Z)
* Tổng số giờ (tăng/giảm dần)
* Tổng số tiết (tăng/giảm dần)

**Ứng dụng:**

* Xem ai có giờ giảng nhiều nhất/ít nhất
* Sắp xếp theo đơn vị để báo cáo
* Tìm các trường hợp bất thường

***

#### 9. Làm mới và các chức năng khác

**Làm mới dữ liệu**

* Click icon **vòng tròn (🔄)** để tải lại danh sách mới nhất từ server

**Chế độ xem**

* Click icon **danh sách (☰)** để ẩn/hiện các cột thông tin
* Click icon **toàn màn hình (⛶)** để xem ở chế độ toàn màn hình

**Phân trang**

* Ở góc dưới bên trái, chọn số dòng hiển thị: 20, 50, 100, 200...
* Sử dụng các nút:
  * **|<** : Về trang đầu
  * **<** : Về trang trước
  * **>** : Sang trang sau
  * **>|** : Đến trang cuối
* Hiển thị: "1-20 trên tổng số 462 bản ghi"

***

#### 10. Liên kết với Link đánh giá của sinh viên

**Cách hoạt động**

Hệ thống liên kết với hệ thống đánh giá của **Phòng Đảm bảo Chất lượng (ĐBCL)**:

**Bước 1:** Phòng ĐBCL cung cấp link đánh giá cho từng giảng viên

**Bước 2:** Link được lưu trong cột **"Link đánh giá"**

**Bước 3:** Click vào link **"Đánh giá"** để xem chi tiết:

* Điểm đánh giá trung bình
* Nhận xét của sinh viên
* Kết quả theo từng học kỳ, môn học

**Bước 4:** Dữ liệu đánh giá ảnh hưởng đến:

* Xếp loại chất lượng giảng dạy
* Hệ số điều chỉnh KPI (nếu có)
* Quyết định bổ nhiệm, khen thưởng

***

#### Lưu ý quan trọng

⚠️ **Về dữ liệu đồng bộ:**

* Dữ liệu giờ giảng được đồng bộ từ hệ thống quản lý giảng dạy của trường
* Không nên sửa trực tiếp dữ liệu đã đồng bộ
* Nếu có sai sót, cần phản ánh về phòng Đào tạo để sửa ở hệ thống nguồn

✅ **Quyền thực hiện:**

* **Quản trị viên**: Xem tất cả, đồng bộ, sửa, xóa
* **Trưởng/Phó Khoa**: Xem giảng viên thuộc khoa mình
* **Giảng viên**: Chỉ xem dữ liệu cá nhân

🔄 **Chu kỳ đồng bộ:**

* **Cuối năm học**: Để tổng kết và đánh giá

🎯 **Liên kết với KPI:**

* Giờ giảng dạy là 1 trong 3 loại giờ tính KPI
* Được quy đổi với giờ NCKH và giờ khác theo công thức trong Kế hoạch Tổng hợp
* Ảnh hưởng trực tiếp đến mức cảnh báo (Xanh/Tím/Đỏ)

📞 **Hỗ trợ:**

* Lỗi đồng bộ API: Liên hệ Ban Quản trị hệ thống
* Sai số liệu giờ giảng: Liên hệ Phòng Đào tạo
* Vấn đề đánh giá SV: Liên hệ Phòng ĐBCL
