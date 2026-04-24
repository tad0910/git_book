---
description: >-
  Thêm, xóa, sửa, import excel, đồng bộ dữ liệu thông qua API (nhà trường cung
  cấp) thông tin sơ bộ về giảng viên (mã giảng viên, ngày ký hợp đồng, loại hình
  hợp đồng, định mức giờ đăng ký, thuộc đơn
---

# Giảng viên

## Giảng viên

Truy cập Menu Danh mục chung -> Giảng viên

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FV2rjWkzhrlUgfeVHfMrS%2Fimage.png?alt=media&#x26;token=7a3a3341-9613-46a4-9311-206a1f5354c9" alt=""><figcaption></figcaption></figure>

***

#### 1. Thêm giảng viên mới

**Cách 1: Thêm thủ công**

**Bước 1:** Truy cập menu **Danh mục chung** > **Giảng viên** trên thanh menu bên trái

**Bước 2:** Click nút **"+ Thêm"** ở góc trên bên trái

**Bước 3:** Điền thông tin cơ bản của giảng viên trong form **"Chỉnh sửa Cán bộ Giảng viên"**:

**Thông tin cá nhân**

* **Mã quản lý**\* (bắt buộc): Nhập mã số giảng viên (ví dụ: 10038, 10054...)
* **Họ và tên**\* (bắt buộc): Nhập họ tên đầy đủ
* **Email**: Nhập địa chỉ email liên hệ
* **SĐT**: Số điện thoại
* **Ngày sinh**: Chọn ngày/tháng/năm sinh từ lịch
* **Giới tính**: Chọn Nam/Nữ/Khác

**Thông tin học vấn**

* **Học hàm**: Chọn từ danh sách (Giáo sư, Phó Giáo sư...)
* **Học vị**: Chọn trình độ (Thạc sĩ, Tiến sĩ, Cử nhân...)
* **Quốc tịch**: Nhập quốc tịch

**Thông tin công tác**

* **Loại đối tượng**: Chọn loại (Giảng viên, Chuyên viên, Cán sự, Giảng viên kiêm nhiệm, Giảng viên thỉnh giảng, Kế toán viên)
* **Loại GV**: Chọn phân loại (Giảng viên mời, Giảng viên cơ hữu, Giảng viên thỉnh giảng)
* **Trạng thái**: Chọn trạng thái (Đang làm việc, Đẫ nghỉ việc, Đã nghỉ hưu)

**Bước 4:** Thêm đơn vị quản lý và chức vụ

Trong bảng **"Tên đơn vị"** và **"Chức vụ"**:

* Click **"+ Thêm đơn vị quản lý"**
* Chọn đơn vị từ dropdown (ví dụ: Khoa Mỹ thuật và Thiết kế)
* Chọn chức vụ tương ứng (ví dụ: Giảng viên phụ trách CTĐT)
* Click icon **bút chì (✏️)** để chỉnh sửa hoặc **thùng rác (🗑️)** để xóa

**Lưu ý:** Một giảng viên có thể thuộc nhiều đơn vị và giữ nhiều chức vụ khác nhau

**Bước 5:** Click nút **"✓ Xác nhận"** màu xanh để hoàn tất

**Bước 6:** Click nút **"Hủy"** nếu muốn hủy bỏ thao tác

**Cách 2: Tải lên từ file Excel**

**Bước 1:** Click nút **"Tải lên"** trên thanh công cụ

**Bước 2:** Tải file mẫu Excel về (nếu cần) bằng cách click vào link "Tải file mẫu"

**Bước 3:** Điền thông tin giảng viên vào file Excel theo đúng định dạng:

* Cột A: Mã quản lý
* Cột B: Họ và tên
* Cột C: Email
* Cột D: SĐT
* Cột E: Ngày sinh
* Cột F: Giới tính
* Cột G: Học hàm
* Cột H: Học vị
* Cột I: Đơn vị quản lý
* Cột J: Loại đối tượng
* Cột K: Loại GV
* Cột L: Trạng thái

**Bước 4:** Chọn file Excel đã chuẩn bị

**Bước 5:** Click **"Tải lên"** và chờ hệ thống xử lý

**Bước 6:** Kiểm tra kết quả import và xử lý các lỗi (nếu có)

**Cách 3: Tải xuống từ hệ thống của trường**

**Bước 1:** Click nút **"Tải xuống"** (màu xanh lá) trên thanh công cụ

**Bước 2:** Hệ thống tự động kết nối API và đồng bộ dữ liệu giảng viên từ hệ thống trung tâm của nhà trường

**Bước 3:** Kiểm tra danh sách giảng viên vừa được đồng bộ

**Lưu ý:** Dữ liệu đồng bộ bao gồm:

* Thông tin cơ bản (mã GV, họ tên, ngày ký hợp đồng)
* Loại hình hợp đồng
* Định mức giờ đăng ký
* Đơn vị trực thuộc
* Chức vụ hành chính

***

#### 2. Sửa thông tin giảng viên

**Bước 1:** Tìm giảng viên cần sửa trong danh sách:

* Sử dụng thanh tìm kiếm để tìm theo mã quản lý hoặc họ tên
* Hoặc duyệt danh sách và sắp xếp theo cột

**Bước 2:** Click vào icon **bút chì (✏️)** màu xanh ở cột **"Thao tác"** bên phải

**Bước 3:** Form **"Chỉnh sửa Cán bộ Giảng viên"** hiển thị với đầy đủ thông tin hiện tại

**Bước 4:** Cập nhật các thông tin cần thay đổi:

* Thông tin cá nhân (email, SĐT, địa chỉ...)
* Thông tin học vấn (học hàm, học vị...)
* Thông tin công tác (loại GV, trạng thái...)
* Đơn vị và chức vụ

**Bước 5:** Để sửa đơn vị/chức vụ:

* Click icon **✏️** bên cạnh đơn vị/chức vụ cần sửa
* Hoặc xóa và thêm mới bằng nút **"+ Thêm đơn vị quản lý"**

**Bước 6:** Click **"✓ Xác nhận"** để lưu thay đổi

***

#### 3. Xóa giảng viên

**Xóa từng giảng viên**

**Bước 1:** Tìm giảng viên cần xóa trong danh sách

**Bước 2:** Click vào icon **thùng rác (🗑️)** màu đỏ ở cột **"Thao tác"**

**Bước 3:** Xác nhận xóa trong hộp thoại cảnh báo

**Lưu ý:**

* Hệ thống sẽ kiểm tra xem giảng viên có dữ liệu KPI liên quan không
* Nếu có dữ liệu, cân nhắc "vô hiệu hóa" bằng cách đổi trạng thái thành "Nghỉ việc" thay vì xóa

**Xóa nhiều giảng viên cùng lúc**

**Bước 1:** Tick vào checkbox ở đầu mỗi dòng để chọn các giảng viên cần xóa

**Bước 2:** Click nút **"Xóa"** trên thanh công cụ

**Bước 3:** Xác nhận xóa hàng loạt

***

#### 4. Đồng bộ Cán bộ - Giảng viên

**Chức năng đặc biệt:** Nút **"Đồng bộ CBGV"** (màu cam)

**Mục đích:** Đồng bộ thông tin giảng viên với các hệ thống khác của trường:

* Hệ thống quản lý nhân sự HRM

**Cách sử dụng:**

**Bước 1:** Click nút **"Đồng bộ CBGV"**

**Bước 2:** Chọn loại đồng bộ:

* Đồng bộ toàn bộ
* Đồng bộ theo đơn vị
* Đồng bộ giảng viên mới

**Bước 3:** Hệ thống xử lý và hiển thị kết quả đồng bộ

**Bước 4:** Kiểm tra log đồng bộ và xử lý các trường hợp lỗi

***

#### 5. Các chức năng hỗ trợ

**Tìm kiếm giảng viên**

* Sử dụng thanh tìm kiếm ở góc phải
* Tìm theo: Mã quản lý, Họ tên, Đơn vị, Email...
* Kết quả hiển thị ngay khi gõ

**Lọc danh sách**

* Click icon **phễu (🔽)** để mở bộ lọc
* Lọc theo:
  * Đơn vị quản lý
  * Trạng thái (Đang làm việc, Nghỉ việc...)
  * Loại đối tượng (Giảng viên, Chuyên viên)
  * Loại GV (Giảng viên mới, Giảng viên cơ hữu...)
  * Học hàm, Học vị
* Click **"Áp dụng"** để xem kết quả

**Sắp xếp dữ liệu**

* Click vào tiêu đề cột có icon **⇅** để sắp xếp
* Sắp xếp tăng dần/giảm dần theo:
  * Mã quản lý
  * Họ và tên
  * Đơn vị quản lý
  * Trạng thái...

**Làm mới dữ liệu**

* Click icon **vòng tròn (🔄)** để tải lại danh sách mới nhất

**Chế độ xem**

* Click icon **danh sách (☰)** để ẩn/hiện các cột thông tin
* Click icon **toàn màn hình (⛶)** để xem ở chế độ toàn màn hình

**Hiển thị số dòng**

* Ở góc dưới bên trái, chọn số dòng hiển thị mỗi trang: 20, 50, 100...
* Sử dụng nút **< >** để chuyển trang
* Hiển thị tổng số: "1-20 trên tổng số 462"

***

#### 6. Phân loại giảng viên

**Theo Loại đối tượng:**

* **Giảng viên**: Giảng viên chính thức
* **Chuyên viên**: Cán bộ hành chính, quản lý

**Theo Loại GV:**

* **Giảng viên mời**
* **Giảng viên cơ hữu**: Giảng viên chính thức, hợp đồng dài hạn
* **Giảng viên thỉnh giảng**: Giảng viên kiêm nhiệm từ bên ngoài

**Theo Trạng thái:**

* **Đang làm việc**: Đang công tác tại trường
* **Đã nghỉ việc**: Đã nghỉ việc, thôi việc
* **Đẫ nghỉ hưu**

***

#### 7. Quản lý Đơn vị và Chức vụ của Giảng viên

**Thêm đơn vị quản lý mới cho giảng viên**

**Bước 1:** Mở form chỉnh sửa giảng viên

**Bước 2:** Trong bảng đơn vị/chức vụ, click **"+ Thêm đơn vị quản lý"**

**Bước 3:** Chọn đơn vị từ dropdown

**Bước 4:** Chọn chức vụ tương ứng tại đơn vị đó

**Bước 5:** Click vào vùng trống bên ngoài để lưu

**Sửa đơn vị/chức vụ**

**Bước 1:** Click icon **✏️** bên cạnh dòng cần sửa

**Bước 2:** Thay đổi đơn vị hoặc chức vụ

**Bước 3:** Click vào vùng trống để lưu

**Xóa đơn vị/chức vụ**

**Bước 1:** Click icon **🗑️** bên cạnh dòng cần xóa

**Bước 2:** Xác nhận xóa

**Lưu ý:** Giảng viên phải có ít nhất 1 đơn vị quản lý

***

#### Lưu ý quan trọng

⚠️ **Trước khi xóa giảng viên:**

* Kiểm tra dữ liệu KPI đã được ghi nhận
* Xem xét dữ liệu giờ giảng dạy, giờ NCKH, giờ khác
* Cân nhắc đổi trạng thái thành "Nghỉ việc" thay vì xóa để giữ lịch sử

✅ **Quyền thực hiện:**

* **Super Admin** và **Quản trị viên**: Thêm/sửa/xóa tất cả giảng viên
* **Trưởng/Phó đơn vị**: Chỉ xem và sửa giảng viên thuộc đơn vị mình
* **Giảng viên**: Chỉ xem và cập nhật thông tin cá nhân

🔄 **Đồng bộ dữ liệu:**

* Nên đồng bộ định kỳ từ hệ thống trường (hàng tuần/tháng)
* Sau khi import Excel, kiểm tra kỹ dữ liệu trùng lặp
* Sử dụng chức năng "Đồng bộ CBGV" để đảm bảo nhất quán với các hệ thống khác

📊 **Liên quan đến tính KPI:**

* Thông tin giảng viên là cơ sở để tính toán KPI
* Định mức giờ đăng ký được sử dụng làm chuẩn để so sánh
* Chức vụ ảnh hưởng đến mức miễn giảm giờ định mức
* Loại hợp đồng quyết định yêu cầu KPI cụ thể

🎯 **Chú ý:**

* Cập nhật thông tin giảng viên ngay khi có thay đổi
* Đảm bảo mã quản lý không trùng lặp
* Điền đầy đủ email và không trùng lặp
* Gắn đúng đơn vị và chức vụ để báo cáo chính xác
