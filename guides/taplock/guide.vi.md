---
title: Khóa Màn Hình Một Chạm
name: TapLock
tagline: Khóa điện thoại chỉ với một chạm. Vân tay và mở khóa khuôn mặt vẫn dùng được.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Ứng dụng làm được gì

TapLock đặt một nút **Lock** lớn ngay trên màn hình. Chạm vào là điện thoại khóa ngay, giống như bấm nút nguồn. Rất tiện khi nút nguồn khó bấm, bị mòn hoặc bị hỏng.

- Với Accessibility lock, bạn vẫn mở khóa như bình thường bằng vân tay, khuôn mặt, mã PIN hoặc hình vẽ.
- Device Admin lock là cách khóa thứ hai, dùng được mà không cần Accessibility.
- Một màn hình, một nút. Không cần tài khoản, không cần đăng nhập.
- Miễn phí, có quảng cáo.

## Bắt đầu

1. Mở TapLock. Lần đầu, dòng chữ dưới nút **Lock** ghi "One-time setup needed (about a minute)."
2. Chạm **Set up TapLock**. Màn hình **Lock setup** sẽ mở ra.
3. Chọn một trong hai cách khóa:
   - **Accessibility lock** (nên dùng, cần Android 9 trở lên): khóa như nút nguồn, vân tay và mở khóa khuôn mặt vẫn dùng được.
   - **Device Admin lock**: dùng được mà không cần Accessibility. Lần mở khóa tiếp theo, Android sẽ hỏi mã PIN, hình vẽ hoặc mật khẩu của bạn.
4. Làm theo các bước bên dưới cho cách bạn chọn.

Bạn có thể mở lại **Lock setup** bất cứ lúc nào bằng biểu tượng cài đặt ở góc trên bên phải màn hình chính.

## Bật Accessibility lock

1. Trên **Lock setup**, ở thẻ **Accessibility lock**, chạm **Turn on Accessibility lock**.
2. Một hộp thoại hỏi **Allow TapLock to use Accessibility?** Hãy đọc cách TapLock sử dụng quyền này.
3. Chạm **Agree** để tiếp tục. Nếu chạm **Decline**, mọi thứ giữ nguyên và Accessibility lock vẫn tắt.
4. Cài đặt Accessibility của Android sẽ mở ra. Tìm TapLock, thường nằm trong mục "Downloaded apps".
5. Bật "Use TapLock", chạm **Allow**, rồi quay lại TapLock.
6. Thẻ lúc này hiện **On**, và dòng **You're all set** xuất hiện ở đầu màn hình. Chạm **Back to Lock**.

![Hộp thoại "Allow TapLock to use Accessibility?" với hai nút Decline và Agree](shots/04-accessibility-consent.png)

**Vì sao TapLock cần quyền Accessibility.** TapLock chỉ dùng Accessibility Service API để khóa màn hình khi bạn chạm nút **Lock**, giống hệt việc bấm nút nguồn. Nhờ vậy vân tay và mở khóa khuôn mặt vẫn dùng được. TapLock không đọc màn hình của bạn, không xem bạn gõ gì, và không thu thập, lưu trữ hay chia sẻ dữ liệu cá nhân nào qua quyền này. Bạn chọn **Agree** hoặc **Decline** trước khi cài đặt của Android mở ra, và có thể tắt quyền này bất cứ lúc nào.

Nếu thẻ hiện **Starting** quá vài giây, hãy tắt rồi bật lại TapLock trong cài đặt Accessibility. Nếu công tắc trong cài đặt của Android bị mờ, chạm **Switch greyed out?** trên **Lock setup** và làm theo gợi ý ở đó.

## Dùng Device Admin lock thay thế

1. Trên **Lock setup**, ở thẻ **Device Admin lock**, chạm **Enable Device Admin**.
2. Android yêu cầu bạn xác nhận. TapLock chỉ dùng quyền này để khóa màn hình khi bạn chạm nút **Lock**.
3. Thẻ lúc này hiện **On**.

![Màn hình Lock setup: thẻ Accessibility lock hiện On, thẻ Device Admin lock có nút Enable Device Admin](shots/02-setup.png)

Với cách khóa này, lần mở khóa tiếp theo Android sẽ hỏi mã PIN, hình vẽ hoặc mật khẩu thay vì vân tay hay khuôn mặt. Nếu cả hai cách đều đang bật, TapLock sẽ dùng Accessibility lock.

## Khóa màn hình

1. Mở TapLock. Dòng chữ dưới nút bắt đầu bằng "Ready."
2. Chạm **Lock**. Màn hình khóa ngay lập tức.
3. Mở khóa điện thoại như mọi khi.

![Màn hình chính với nút Lock hình tròn và dòng chữ "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Dùng chế độ tối

1. Bật giao diện tối trong cài đặt Android của điện thoại.
2. Mở TapLock. Ứng dụng theo máy của bạn và tự chuyển sang nền tối. Trong ứng dụng không có mục cài đặt riêng cho việc này.

![Màn hình chính của TapLock ở chế độ tối](shots/03-dark-mode.png)

## Đổi ngôn ngữ

1. Trên màn hình chính, chạm biểu tượng cài đặt để mở **Lock setup**.
2. Mở bộ chọn ngôn ngữ.
3. Chọn một trong 31 ngôn ngữ, hoặc giữ mặc định của hệ thống để TapLock theo ngôn ngữ của điện thoại.

![Bộ chọn ngôn ngữ với danh sách các ngôn ngữ](shots/06-language.png)

Tiếng Ả Rập, Urdu và Do Thái được hiển thị từ phải sang trái. Trên Android 13 trở lên, bạn cũng có thể đổi ngôn ngữ của TapLock trong phần cài đặt ngôn ngữ ứng dụng của Android.

## Tắt một cách khóa hoặc gỡ cài đặt

1. Trên màn hình chính, chạm biểu tượng cài đặt để mở **Lock setup**.
2. Để tắt Accessibility lock, chạm **Manage in Accessibility settings** và tắt TapLock ở đó.
3. Để tắt Device Admin lock, chạm **Turn off Device Admin**.
4. Hãy tắt Device Admin trước khi gỡ TapLock. Android không cho gỡ một ứng dụng đang là quản trị viên thiết bị.

![Lock setup với thẻ "You're all set" và nút tắt Device Admin](shots/05-device-admin-on.png)

## Câu hỏi thường gặp

**Vì sao TapLock cần quyền Accessibility?**
Chỉ để khóa màn hình khi bạn chạm **Lock**, giống như bấm nút nguồn. Ứng dụng không đọc màn hình và không xem bạn gõ gì. Nếu không muốn cấp quyền này, hãy dùng Device Admin lock.

**Sau khi khóa bằng TapLock, vân tay của tôi không dùng được. Tại sao?**
Bạn đang dùng Device Admin lock, nên Android sẽ hỏi mã PIN, hình vẽ hoặc mật khẩu một lần. Hãy bật Accessibility lock để vân tay và mở khóa khuôn mặt vẫn dùng được.

**Tôi không gỡ được TapLock. Phải làm sao?**
Mở **Lock setup**, chạm **Turn off Device Admin**, rồi gỡ ứng dụng.

**Tôi cần phiên bản Android nào?**
Accessibility lock cần Android 9 trở lên. Với phiên bản cũ hơn, hãy dùng Device Admin lock.

**Tôi có thể dùng TapLock bằng tiếng Việt không?**
Có. TapLock có 31 ngôn ngữ. Hãy chọn ngôn ngữ của bạn trên **Lock setup**, hoặc giữ mặc định của hệ thống.

## Quyền riêng tư

TapLock chỉ dùng quyền Accessibility và Device Admin để khóa màn hình, và không thu thập dữ liệu cá nhân qua các quyền này. Ứng dụng hiển thị quảng cáo từ Google AdMob; ở nơi có yêu cầu, bạn có thể thay đổi lựa chọn quảng cáo bằng **Privacy settings** trên **Lock setup**. Đọc toàn văn [chính sách quyền riêng tư](https://varian1.github.io/LockAppOnlyWeb/privacy.html).
