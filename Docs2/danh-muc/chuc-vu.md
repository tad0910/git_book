---
description: >-
  Thêm, xóa, sửa, import excel , đồng bộ dữ liệu thông qua API (nhà trường cung
  cấp) các loại chức vụ cho từng loại đơn vị (ví dụ trưởng, phó khoa, thư ký,
  v.v)
---

# Chức vụ

## Chức vụ

Truy cập Menu **Danh mục chung -> Chức vụ**

<figure><img src="https://1687372792-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLxY8DN2hParqOioLhps1%2Fuploads%2FInsdz3Ccd2c6cLDvPbE1%2Fimage.png?alt=media&#x26;token=982f3e09-e55f-41bb-bf5e-4fbfb2bc53a2" alt=""><figcaption></figcaption></figure>

#### 1. Thêm chức vụ mới

**Cách 1: Thêm thủ công**

**Bước 1:** Truy cập menu **Danh mục chung** > **Chức vụ** trên thanh menu bên trái

**Bước 2:** Click nút **"+ Thêm"** ở góc trên bên trái của bảng danh sách

**Bước 3:** Điền thông tin chức vụ trong form xuất hiện:

* **Ký hiệu**: Nhập mã viết tắt của chức vụ (ví dụ: HT, HP, TT, TP...)
* **Tên**: Nhập tên đầy đủ của chức vụ (ví dụ: Hiệu trưởng, Phó Hiệu trưởng, Thư ký Hội đồng trường...)
* **Dị chuyển**: Kéo thả để sắp xếp thứ tự ưu tiên của chức vụ (nếu cần)

**Bước 4:** Click **"Lưu"** để hoàn tất

**Cách 2: Đồng bộ từ API của nhà trường (nếu có)**

**Bước 1:** Click nút **"Đồng bộ"** (màu đỏ cam) trên thanh công cụ

**Bước 2:** Hệ thống sẽ tự động kết nối API và đồng bộ dữ liệu chức vụ từ hệ thống trung tâm của nhà trường

**Bước 3:** Kiểm tra danh sách chức vụ vừa được đồng bộ

**Cách 3: Tải lên từ file Excel**

**Bước 1:** Chuẩn bị file Excel với các cột:

* Cột A: Ký hiệu chức vụ
* Cột B: Tên chức vụ
* Cột C: Thứ tự ưu tiên (nếu có)

**Bước 2:** Click nút import/upload (nếu có trên giao diện)

**Bước 3:** Chọn file và xác nhận tải lên

***

#### 2. Sắp xếp thứ tự chức vụ

**Bước 1:** Click vào icon **6 chấm (⋮⋮)** ở cột **"Di chuyển"** bên trái mỗi dòng

**Bước 2:** Giữ chuột và kéo dòng lên/xuống để sắp xếp thứ tự mong muốn

**Bước 3:** Thả chuột để hoàn tất. Hệ thống tự động lưu thứ tự mới

**Ứng dụng:** Thứ tự này ảnh hưởng đến:

* Cách hiển thị trong dropdown chọn chức vụ
* Thứ tự ưu tiên khi tính miễn giảm giờ định mức
* Báo cáo và thống kê theo cấp bậc

***

#### 3. Sửa thông tin chức vụ

**Bước 1:** Tìm chức vụ cần sửa trong danh sách (có thể dùng chức năng tìm kiếm)

**Bước 2:** Click vào icon **bút chì (✏️)** màu xanh ở cột **"Thao tác"** bên phải

**Bước 3:** Cập nhật thông tin cần thay đổi:

* Sửa ký hiệu chức vụ
* Cập nhật tên chức vụ
* Thay đổi thứ tự ưu tiên

**Bước 4:** Click **"Lưu"** để cập nhật thay đổi

***

#### 4. Xóa chức vụ

**Xóa từng chức vụ**

**Bước 1:** Tìm chức vụ cần xóa trong danh sách

**Bước 2:** Click vào icon **thùng rác (🗑️)** màu đỏ ở cột **"Thao tác"**

**Bước 3:** Xác nhận xóa trong hộp thoại cảnh báo xuất hiện

**Lưu ý:** Hệ thống sẽ kiểm tra xem có giảng viên/cán bộ nào đang giữ chức vụ này không. Nếu có, cần gỡ chức vụ của họ trước khi xóa.

**Xóa nhiều chức vụ cùng lúc**

**Bước 1:** Tick vào checkbox ở đầu mỗi dòng để chọn các chức vụ cần xóa

**Bước 2:** Click nút **"Xóa"** trên thanh công cụ (nếu có)

**Bước 3:** Xác nhận xóa hàng loạt

***

#### 5. Các chức năng hỗ trợ khác

**Tìm kiếm chức vụ**

* Click vào icon **kính lúp (🔍)** ở góc phải
* Nhập ký hiệu hoặc tên chức vụ cần tìm
* Kết quả hiển thị ngay lập tức

**Lọc danh sách**

* Click vào icon **phễu (🔽)** để mở bộ lọc
* Chọn tiêu chí lọc (theo loại chức vụ, đơn vị áp dụng...)
* Áp dụng bộ lọc

**Làm mới dữ liệu**

* Click icon **vòng tròn (🔄)** để tải lại danh sách mới nhất từ hệ thống

**Chế độ xem toàn màn hình**

* Click icon **mở rộng (⛶)** ở góc phải để xem ở chế độ toàn màn hình

***

#### Phân loại chức vụ trong hệ thống

**1. Chức vụ cấp trường**

* **HT** - Hiệu trưởng
* **HP** - Phó Hiệu trưởng
* **TT** - Thư ký Hội đồng trường

**2. Chức vụ cấp phòng ban**

* **TP** - Trưởng phòng
* **PP** - Phó trưởng phòng

**3. Chức vụ cấp khoa**

* **TK** - Trưởng khoa
* **PK** - Phó Trưởng khoa

**4. Chức vụ giảng viên đặc thù**

* **GV\_CTĐT** - Giảng viên phụ trách CTĐT
* **GV\_BM** - Giảng viên phụ trách các nhóm môn thuộc khối kiến thức chung và khối kiến thức theo lĩnh vực

**5. Chức vụ khác**

* **TS** - Tập sự

***

#### Lưu ý quan trọng

⚠️ **Trước khi xóa chức vụ:**

* Kiểm tra không còn giảng viên/cán bộ nào đang giữ chức vụ đó
* Xem xét ảnh hưởng đến lịch sử dữ liệu KPI
* Cân nhắc "vô hiệu hóa" thay vì xóa để giữ tính liên tục của dữ liệu

✅ **Quyền thực hiện:**

* Chỉ **Quản trị viên** mới có quyền thêm/sửa/xóa chức vụ
* Các vai trò khác chỉ có quyền xem danh sách

🔄 **Đồng bộ dữ liệu:**

* Nên sử dụng tính năng "**Đồng bộ**" để đồng bộ định kỳ từ hệ thống trường
* Đảm bảo danh sách chức vụ luôn đồng nhất với cơ cấu tổ chức thực tế

📊 **Liên quan đến tính KPI:**

* Mỗi chức vụ có mức miễn giảm giờ định mức riêng (thiết lập ở phần Cài đặt/Kế hoạch)
* Thứ tự sắp xếp ảnh hưởng đến cách tính toán khi một người giữ nhiều chức vụ
* Chức vụ là yếu tố quan trọng trong báo cáo KPI theo cấp quản lý
