# Hướng dẫn cài đặt Safe Exam Browser trên Windows để thi online

Bạn được yêu cầu cài đặt trình duyệt Safe Exam Browser, viết tắt là SEB, lên máy tính của bạn để làm bài thi online.

Các bước cài đặt và chạy SEB trên Windows như sau:

**Bước 1. Kiểm tra thiết bị**

Máy tính cài đặt SEB để làm bài thi phải thỏa mãn các yêu cầu sau:\
• PC hoặc laptop có camera và microphone, kết nối Internet.\
• Là máy thật (physical machine), không phải máy ảo.\
• Hệ điều hành: <img src="https://live.itest.com.vn/docs/windows-apps-icon-14.jpg" alt="" data-size="line"> Windows 8.1, 10, 11.

**Bước 2. Download và cài đặt**

• Download bản cài đặt 👉 [SEB\_Win.zip](https://cmcuni.sharepoint.com/:f:/s/STintranet/EmpCVqLnnGNHiriDCt-vfiUBcUqUKrWriaVCUwPmuoeMqg?e=GmjzjM)\
• Kích phải chuột vào tệp SEB\_Setup.exe vừa tải rồi chọn "Run as administrator".\
• Tích chọn "I accept the terms in the License Agreement terms and conditions", rồi bấm nút "Install".\
• Bấm nút "Yes". Chờ chương trình cài đặt trong ít phút.\
• Bấm "Finish".

**Bước 3. Vào thi**

Nhấp đúp chuột vào tệp StartTest\_Win.seb đã tải về ở Bước 2.\
Hoặc kích phải chuột vào tệp StartTest\_Win.seb, chọn "Open with", rồi chọn "Safe Exam Browser".![](https://live.itest.com.vn/docs/start-test-win.png)

## **Xử lý các lỗi thường gặp**

### **Lỗi không cài được các thư viện, thành phần cần thiết**

![](https://live.itest.com.vn/docs/std-seb3.png)

**Nguyên nhân:**\
SEB yêu cầu các thành phần thư viện cần thiết như .NET Framework, WebView, ... Khi bạn cài đặt bằng gói cài đặt SEB Bundle và quá trình gặp lỗi do không download được các thành phần thư viện.\
Cách khắc phục\
• Kiểm tra lại kết nối mạng và đảm bảo có kết nối mạng rồi thực hiện cài lại bằng SEB Bundle.\
• Nếu khắc phục mạng rồi mà cài lại vẫn gặp lỗi này thì chuyển sang cài đặt các thư viện, thành phần cần thiết trước khi cài SEB bằng MSI như sau:\
• Download và cài đặt 👉 [.NET Framework 4.7.2 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net472)\
• Download và cài đặt 👉 [Microsoft Edge WebView2 Runtime](https://go.microsoft.com/fwlink/p/?LinkId=2124703)\
• Download và cài đặt 👉 [Visual C++ 2015-2019 Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### **Lỗi không nhận được màn hình chính**

![](https://live.itest.com.vn/docs/std-seb5.png)

**Nguyên nhân**\
SEB không nhận được màn hình hoặc có nhiều màn hình cùng nối vào máy tính (tùy số lượng màn hình được báo trong thông báo lỗi).\
Cách khắc phục\
Tháo bỏ kết nối đến màn hình thứ hai hoặc máy chiếu (nếu có).\
Chọn chế độ màn hình của Windows là “PC screen only”: Bấm đồng thời Windows + P, rồi chọn select "PC screen only".

### **Lỗi không gõ được tiếng Việt trong khi làm bài thi viết luận**

Nguyên nhân\
Thí sinh chưa bật chế độ gõ tiếng Việt hoặc sử dụng phần mềm gõ tiếng Việt phiên bản đã cũ.\
Cách khắc phục\
Thí sinh sử dụng UniKey 4.3 RC5 và để chế độ gõ Telex, bảng mã Unicode dựng sẵn, đồng thời chạy Unikey và bật chế độ gõ tiếng Việt TRƯỚC khi chạy SEB để vào làm bài thi. Tải UniKey 4.3 RC5 trên website chính thống\
&#x20;      👉 [UniKey 4.3 RC5, 64 bit, ZIP file: Build 200929 ](https://www.unikey.org/assets/release/unikey43RC5-200929-win64.zip).

### **Lỗi sai ngày tháng của chứng thực số trên máy của thí sinh**

Khi chạy SEB gặp lỗi màn hình hiện ra thông báo\
NET::ERR\_CERT\_DATE\_INVALID\
Nguyên nhân\
Có nhiều nguyên nhân dẫn đến sai ngày tháng của chứng thực như sai ngày tháng trên máy tính của thí sinh, kết nối wifi không an toàn, phần mềm độc hại làm hỏng chứng thực số.\
Cách khắc phục\
Lần lượt thực hiện các bước sau và kiểm tra còn lỗi trên hay không sau mỗi bước:\
1\. Đặt ngày tháng trên máy tính của thí sinh đúng ngày tháng hiện tại.\
2\. Thay đổi kết nối mạng sang mạng có dây hoặc mạng không dây khác vì có thể mạng kết nối wifi hiện tại không an toàn.\
3\. Quét virus trên máy tính của của bạn.
