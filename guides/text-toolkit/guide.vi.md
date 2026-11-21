---
title: Đếm từ: Text Toolkit
name: Text Toolkit
tagline: Đếm từ, đổi kiểu chữ, làm sạch, sắp xếp, so sánh văn bản offline ngay trên máy.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## What it does

Text Toolkit chỉ có một màn hình với chín công cụ xử lý văn bản. Bạn gõ hoặc dán văn bản vào ô ở trên cùng, chọn một công cụ, rồi sao chép hoặc chia sẻ kết quả. Ứng dụng đếm từ, đổi kiểu chữ hoa/thường, dọn khoảng trắng, sắp xếp dòng, tìm và thay thế, đảo ngược, mã hóa, định dạng JSON và so sánh hai văn bản.

- Mọi công cụ đều chạy ngay trên máy và không cần internet.
- Không cần tài khoản. Văn bản của bạn không bao giờ bị tải lên, và ứng dụng không dùng camera, ảnh, danh bạ hay vị trí của bạn.
- Văn bản không được lưu lại. Khi bạn đóng ứng dụng, văn bản sẽ mất.
- Miễn phí. Một quảng cáo biểu ngữ có thể hiện ở cuối màn hình.

## Get started

1. Mở Text Toolkit. Ô **YOUR TEXT** có sẵn một đoạn văn mẫu ngắn để bạn thử từng công cụ.
2. Chạm **Clear** rồi gõ văn bản của bạn, hoặc chạm **Paste** để thay nội dung bằng văn bản bạn vừa sao chép từ ứng dụng khác. **Sample** sẽ đưa đoạn văn mẫu trở lại.
3. Chọn một công cụ ở hàng bên dưới ô: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** hoặc **Diff**. Vuốt hàng này sang ngang để xem hết.

![Màn hình chính: ô YOUR TEXT với Paste, Sample và Clear, hàng công cụ và các số liệu của Counter](shots/01-home.png)

Ứng dụng dùng ngôn ngữ của điện thoại bạn. Ứng dụng có 11 ngôn ngữ: tiếng Anh, Tây Ban Nha, Bồ Đào Nha, Đức, Pháp, Hindi, Indonesia, Ả Rập, Ý, Nga và Thổ Nhĩ Kỳ.

## Đếm từ và ký tự

1. Chạm **Counter**.
2. Xem các số liệu: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** và **Reading time**.
3. Xem mục **TOP WORDS** bên dưới để biết những từ bạn dùng nhiều nhất, tối đa tám từ, kèm số lần xuất hiện.

Các số thay đổi ngay khi bạn gõ. Thời gian đọc được tính theo 200 từ mỗi phút.

## Đổi kiểu chữ hoa/thường

1. Chạm **Case**.
2. Cuộn qua các thẻ. Mỗi thẻ hiển thị văn bản của bạn theo một kiểu khác: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** và **URL slug**.
3. Chạm **Copy** trên thẻ bạn muốn.

![Công cụ Case: các thẻ UPPERCASE, lowercase và Title Case, mỗi thẻ có Use input, Share và Copy](shots/02-case.png)

## Làm sạch văn bản

1. Chạm **Clean**.
2. Chạm một thao tác:
   - **Clean all**: xóa tab, khoảng trắng lặp, khoảng trắng ở cuối dòng, dòng trống và dòng trùng lặp chỉ trong một lần.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** hoặc **Remove tabs**: chỉ làm đúng một việc đó.
   - Nút xử lý ngắt dòng: xóa các ngắt dòng khỏi văn bản của bạn.
3. Xem kết quả ở mục **CLEANED RESULT**. Văn bản của bạn trong ô vẫn giữ nguyên.

![Công cụ Clean: các nút làm sạch và thẻ CLEANED RESULT](shots/03-clean.png)

## Sắp xếp hoặc đảo ngược

1. Chạm **Lines** để xử lý theo từng dòng: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** hoặc **Reverse characters**. Khi sắp xếp, ứng dụng bỏ qua chữ hoa và khoảng trắng ở đầu dòng.
2. Chạm **Reverse** để đảo văn bản: **Entire text**, **Each word**, **Word order**, **Line order** hoặc **Characters per line**.
3. Kết quả hiện trong thẻ bên dưới các nút.

## Tìm và thay thế

1. Chạm **Replace**.
2. Gõ nội dung cần tìm vào **Find** và nội dung mới vào **Replace with**.
3. Chạm các tùy chọn để bật hoặc tắt: **Replace all** (tắt thì chỉ đổi kết quả khớp đầu tiên), **Case sensitive** và **Whole word**.
4. Xem số lần thay thế và mục **REPLACEMENT PREVIEW**. Cả hai cập nhật ngay khi bạn gõ.

![Công cụ Replace: các ô Find và Replace with, ba nút tùy chọn, số lần thay thế và phần xem trước](shots/04-replace.png)

Ứng dụng tìm đúng những gì bạn gõ. Ứng dụng không dùng mẫu tìm kiếm hay ký tự đại diện.

## Mã hóa, giải mã và định dạng

1. Chạm **Encode**, chọn **URL**, **Base64** hoặc **HTML Entities**, rồi chạm **Encode** hoặc **Decode**.
2. Chạm **Format** và chọn **Format JSON** để thụt lề JSON bằng hai dấu cách, **Minify JSON** để gộp JSON thành một dòng, hoặc **Strip Markdown** để chuyển Markdown thành văn bản thuần.
3. Nếu JSON có lỗi, một dòng gần đầu màn hình sẽ bắt đầu bằng "Invalid JSON" và cho biết lỗi ở đâu.

## So sánh hai văn bản

1. Đặt phiên bản thứ nhất vào **YOUR TEXT** rồi chạm **Diff**.
2. Gõ hoặc dán phiên bản thứ hai vào **COMPARE WITH**.
3. Xem **DIFF COMPARISON**. Các dòng chỉ có ở phiên bản thứ hai màu xanh lá, có dấu **+**. Các dòng chỉ có ở phiên bản thứ nhất màu đỏ, có dấu **-**. Các dòng giống nhau không có dấu.
4. Chạm **Copy Diff** để sao chép bản so sánh cùng các dấu + và -.

![Công cụ Diff: ô COMPARE WITH và thẻ DIFF COMPARISON với một dòng thêm màu xanh lá và một dòng xóa màu đỏ](shots/05-diff.png)

## Sao chép, chia sẻ hoặc làm tiếp

1. Chạm **Copy** trên thẻ kết quả để đưa vào bộ nhớ tạm.
2. Chạm **Share** để gửi sang ứng dụng khác.
3. Chạm **Use input** để chuyển kết quả vào **YOUR TEXT**, rồi dùng công cụ khác xử lý tiếp.

## Premium

Mọi công cụ đều miễn phí. Có một lần mua tùy chọn, trả một lần, để tắt quảng cáo. Bạn chỉ trả một lần, đây không phải gói đăng ký.

## Questions

**Ứng dụng có dùng được khi không có mạng không?**
Có. Cả chín công cụ đều chạy trên điện thoại của bạn. Chỉ quảng cáo và việc mua để tắt quảng cáo mới cần kết nối mạng.

**Văn bản của tôi có được lưu lại không?**
Không. Ứng dụng chỉ giữ văn bản khi đang mở. Hãy sao chép hoặc chia sẻ kết quả bạn muốn giữ.

**Sao kết quả bị trống sau khi tôi đổi công cụ?**
Clean, Lines, Reverse, Encode và Format dùng chung một thẻ kết quả, và thẻ này bị xóa khi bạn đổi công cụ. Hãy chạm lại thao tác. Làm tương tự sau khi bạn sửa văn bản. Counter, Case, Replace và Diff tự cập nhật.

**Ứng dụng có theo chế độ tối không?**
Có. Ứng dụng dùng giao diện sáng hoặc tối đã đặt trên điện thoại của bạn.

**Giấy phép nằm ở đâu?**
Cuộn xuống cuối và chạm **Open-source licenses**. **Privacy policy** nằm ngay cạnh.

## Privacy

Văn bản của bạn được xử lý ngay trên điện thoại và không bao giờ bị tải lên hay lưu lại. Ứng dụng có thể hiển thị quảng cáo từ Google AdMob. Ở nơi luật pháp yêu cầu, ứng dụng sẽ hỏi lựa chọn của bạn trước, và bạn có thể đổi bằng **Ad privacy choices** trên màn hình chính. Đọc toàn bộ [chính sách quyền riêng tư](https://varian1.github.io/text-toolkit/privacy.html).
