---
title: 二维码条码扫描生成工具
name: QR & Barcode Toolkit
tagline: 扫描、生成二维码和条形码。本机处理，保护隐私，支持历史记录和导出。
project: QRBarcode and toolkit
package: com.varian1.qrtoolkit
version: 1.0.0
updated: 2026-11-21
privacy: https://varian1.github.io/qr-barcode-toolkit/privacy.html
---

## 功能简介

QR & Barcode Toolkit 可以用相机或照片扫描二维码和条形码，并在你操作之前先显示码中的内容。你也可以自己制作二维码和条形码，保存为图片或分享给别人。应用支持 21 种语言，并会跟随手机的语言设置。

- 所有码都在你的设备上读取，链接不会自动打开。
- 无需账号，历史记录只保存在你的手机里。
- 支持读取二维码和 12 种条形码，例如 EAN-13、UPC-A 和 Code 128。
- 免费使用，含广告。一次性购买 Premium 即可去除广告，并获得更多样式选项。

## 开始使用

1. 打开 QR & Barcode Toolkit。**Home** 页面有四个快捷入口：**Scan QR**、**Scan Barcode**、**Create QR** 和 **Create Barcode**。
2. 点击 **Scan QR**。首次使用时，点击 **Allow camera**，并在 Android 询问时允许使用相机。
3. 如果不想使用相机，点击 **Scan from an image instead**，然后选择一张照片。这样不需要访问你的整个相册。

![Home 页面，显示 Scan QR、Scan Barcode、Create QR 和 Create Barcode 快捷入口以及 Recent activity](shots/01-home.png)

## 扫描二维码或条形码

1. 点击底部的 **Scan**，或点击 **Home** 上的扫描快捷入口。
2. 在顶部选择 **QR Code** 或 **Barcode**。
3. 将相机对准要扫描的码。扫描条形码时，请让它保持在取景框内。
4. 光线较暗时，点击手电筒按钮。如果要从照片中读取，点击图片按钮并选择照片。
5. 读取成功后会打开 **Scan Result**，并显示内容类型，例如 **Website**、**Wi-Fi**、**Contact** 或 **Product**。
6. 点击 **Copy content** 或 **Share as text**；也可以点击 **Scan another** 回到相机。

![扫描界面，显示 QR Code 和 Barcode 切换开关、取景框以及图片和手电筒按钮](shots/06-scan.png)

## 打开链接前先检查

1. 扫描包含网址的码。结果页会显示网站名称和完整网址。
2. 如果有警告，请仔细阅读。应用会提示未加密（http）链接、短链接、纯 IP 地址、隐藏的登录信息以及外观相似的字符。
3. 只有在信任该网站时才点击 **Open link**，然后点击 **Open** 确认。

![网站的 Scan Result：Open link 按钮上方有两条警告](shots/03-link.png)

其他类型的码有各自的按钮：**Compose email**、**Call**、**Send message**、**Open in Maps** 或 **Search the web**。每个按钮在离开应用前都会先询问你。

## 读取 Wi-Fi 二维码

1. 扫描 Wi-Fi 二维码。结果页会显示 **Network**、**Security** 和 **Password**。
2. 点击眼睛图标可显示密码。
3. 点击密码旁边的复制图标。
4. 打开手机的 Wi-Fi 设置，用复制的密码加入该网络。应用不会替你连接网络。

![Wi-Fi 码的 Scan Result，显示网络名称、加密类型和隐藏的密码](shots/02-wifi.png)

## 生成二维码

1. 点击 **Create**，选择 **QR Code**。
2. 在 **Content type** 下选择 **Website**、**Text**、**Wi-Fi**、**Email**、**Phone**、**SMS**、**Contact** 或 **Location**。
3. 填写各项内容。信息有效后，二维码会立即出现。如果想在历史记录中给它起个名字，请填写 **Title (optional)**。
4. 在 **Style** 下选择模板：**Classic**、**Indigo** 或 **Forest**。你还可以更改 **Foreground** 和 **Background** 颜色以及 **Error correction** 级别。
5. 点击 **Save to history** 保存，点击 **Share** 发送图片，或点击 **Save image** 存入相册。

![Create 页面：Indigo 模板的二维码，下方是 Style 模板和颜色选项](shots/04-create.png)

带锁的选项属于 Premium。

## 生成条形码

1. 点击 **Create**，选择 **Barcode**。
2. 在 **Format** 下选择 **EAN-13**、**EAN-8**、**UPC-A**、**Code 128**、**Code 39** 或 **ITF-14**。
3. 输入 **Value**。输入框下方的文字会说明该格式接受的内容。对于商品条码，如果你没有输入校验位，应用会自动补上。
4. 如果想给它起个名字，请填写 **Title (optional)**。
5. 点击 **Save to history**、**Share** 或 **Save image**。

![EAN-13 条形码的 Create 页面，显示输入的值、条形码预览和自动添加的校验位](shots/05-barcode.png)

## 查找、重复使用和删除码

1. 点击 **History**，这里列出你扫描和生成过的码。
2. 在 **Search** 中输入关键词，或使用 **All**、**Scanned**、**Created**、**Favorites**、**Any type**、**QR** 和 **Barcode** 筛选。
3. 点击某一行的星标，可将其加入收藏。
4. 点击某一行打开 **Details**。你可以在这里点击 **Copy content**、**Share as text** 或 **Delete**。二维码以及应用可生成的条形码格式还会显示码图，并提供 **Share image** 和 **Edit / reuse**。
5. 要清空列表，点击顶部的垃圾桶图标，然后点击 **Clear**。收藏的内容会保留。

![History 页面，显示搜索框、筛选条件以及已扫描和已生成的码列表](shots/07-history.png)

## 更改设置

1. 点击 **Settings**。
2. 如果不想保留扫描记录，请关闭 **Save scans to history**。
3. 打开或关闭 **Haptic feedback**。
4. 只有在需要保存 Wi-Fi 密码时，才打开 **Keep Wi-Fi passwords in history**。该选项默认关闭。
5. 点击 **Language** 选择应用语言。默认情况下，应用会跟随手机的语言。
6. 点击 **Clear all history**，再点击 **Delete all**，即可删除所有扫描和已生成的码，包括收藏。

![Settings 页面，显示 Preferences、Privacy 和 About 分区](shots/08-settings.png)

## Premium

Premium 为一次性付费，不是订阅。打开 **Settings** 并点击 **Go Premium**，或在 **Home** 上点击 **See plans**。它包含：

- 无广告。
- 自定义颜色、高级模板，以及在二维码中加入 Logo。
- 不限数量的历史记录和收藏。
- 支持 1024 px 和 2048 px 导出。

未购买 Premium 时，点击带锁的模板、颜色或 **Add logo**，可能会出现 **Watch an ad** 选项，观看后可解锁这些样式选项，直到你关闭应用为止。如果你以前购买过 Premium，请在 **Settings** 中点击 **Restore purchases**。

## 常见问题

**应用会自动打开链接吗？**
不会。应用会先显示网址和相关警告。只有在你点击 **Open link** 并确认后，链接才会打开。

**可以读取哪些码？**
QR、EAN-13、EAN-8、UPC-A、UPC-E、Code 128、Code 39、Code 93、Codabar、ITF-14、PDF417、Data Matrix 和 Aztec。

**为什么历史记录里没有 Wi-Fi 密码？**
Wi-Fi 密码会在保存码之前被移除。如果想保留密码，请在扫描或生成码之前，先在 **Settings** 中打开 **Keep Wi-Fi passwords in history**。

**可以保存多少个码？**
免费版保留最近 100 条扫描记录和 100 个已生成的码，以及最多 10 个收藏。免费列表已满时，**History** 会提示你，新内容会替换最旧的内容。列表已满时，收藏不会被删除。Premium 没有数量限制。

**有深色模式吗？**
有。应用会跟随手机的浅色或深色主题。

## 隐私

所有码都在你的设备上读取，历史记录只保存在你的手机里。免费版会显示来自 Google AdMob 的广告。请阅读完整的[隐私政策](https://varian1.github.io/qr-barcode-toolkit/privacy.html)。
