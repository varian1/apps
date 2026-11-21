---
title: 应用锁 AppLock：PIN、图案、指纹锁
name: AppLock
tagline: 用 PIN、图案、密码或指纹锁住任意应用，无需联网，也无需账号。
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## What it does

AppLock 会在你选定的应用前面加一道锁屏。有人打开被锁的应用时，必须先输入你的 PIN、图案或密码，或者验证你的指纹，才能看到应用内容。在应用内部，它的名称写作 "App Lock"。

- 无需账号。你的 PIN、已锁应用列表、安全日志和入侵者照片都只保存在手机上，不会上传。
- 有人连续输错密码时，它可以拍下对方的照片。
- 忘记 PIN 时，可以用恢复码重新进入。
- 免费，含广告。锁定应用始终免费。一次性购买 Premium 可去除广告并增加更多功能。

## Get started

1. 打开 AppLock，点按 **Get started**。
2. 在 **How do you want to unlock?** 下，选择 **PIN**、**Pattern** 或 **Password**。
3. 输入一次，再输入一次确认。PIN 为 6 位数字。图案至少连接 4 个点。密码至少 4 个字符。设置图案或密码时，每次输入后都要点按 **Continue**。
4. 在 **Save your recovery code** 页面，抄下 8 位恢复码，并放在安全的地方。这个码只显示一次。如果你忘记 PIN、图案或密码，它是重新进入的唯一办法。
5. 勾选 **I’ve saved this code somewhere safe**，然后点按 **Continue**。

现在你进入了主屏幕。在你允许权限并锁定第一个应用之前，它会显示 **Protection off**。

## 允许权限

只有当 Android 允许 AppLock 发现某个应用被打开，并允许它在上层显示锁屏时，AppLock 才能锁住应用。这需要两项权限：**Accessibility** 和 **Display over other apps**。其他权限都是可选的。

1. 在主屏幕上，点按 **Finish setup** 或 **Permissions**。
2. 点按 **Accessibility**。AppLock 会先显示一个名为 **What Accessibility access does** 的页面。请先阅读。
3. 点按 **I understand — open settings**。如果你不同意，点按 **Not now**：不会有任何改动，也不会打开设置。
4. 在打开的 Android 设置页面中，为 AppLock 打开该服务，然后返回 AppLock。
5. 点按 **Display over other apps**，并在 Android 设置页面中允许。
6. 点按你想允许的其他项目。完成后，该项会显示 **Granted**。

![在打开 Android 设置之前显示的 "What Accessibility access does" 页面](shots/05-accessibility-disclosure.png)

**AppLock 为什么需要 Accessibility。** AppLock 使用 Android 的无障碍服务只有一个目的：发现哪个应用刚刚切换到前台，以便在你选择保护的应用上显示锁屏。

- 它做什么：只监测刚刚打开的应用的名称，不做别的。解锁被锁应用或输错密码时，该应用的名称会保存在手机上的 **Security log** 中，方便你查看。
- 它绝不做什么：绝不读取屏幕内容、按键输入、密码、消息或任何其他屏幕数据，无论是在 AppLock 还是在其他应用中。不会向你的设备外发送任何内容。
- 你可以随时在 Android 设置中关闭它。关闭后，AppLock 就无法再显示锁屏。

**其他权限的用途。**

- **Display over other apps**：让锁屏显示在被锁应用的上层。
- **Usage access**：帮助确认保护功能稳定运行。
- **Notifications**：提醒你出现锁屏提示和闯入尝试。
- **Camera**（可选）：拍下解锁失败者的照片。
- **Notification access**：隐藏被锁应用的通知内容。
- **Ignore battery optimization**：让保护功能在后台持续运行。

所有权限都只在你的手机上使用。

![权限页面：每项权限都有说明，并带有绿色的 Granted 标签](shots/03-permissions.png)

## 选择要锁定的应用

1. 在主屏幕上，点按 **Lock apps**。
2. 找到要锁的应用。在 **Search apps** 中输入应用名称，或在 **User**、**System** 和 **Recent** 标签之间切换。**Recent** 会把最新安装的应用排在最前面。
3. 打开每个想锁定的应用旁边的开关。
4. 返回。主屏幕会显示 **Protected** 和已锁应用的数量。

![Lock apps 列表，带有搜索框、标签页和每个应用的开关](shots/06-lock-apps.png)

要彻底解锁某个应用，再次打开 **Lock apps**，关闭它的开关。

![主屏幕显示 Protected、6 apps locked，以及 Lock apps、Permissions、Security log、Intruder photos 和 Settings](shots/01-home.png)

## 打开被锁的应用

1. 打开一个你锁定的应用。锁屏会立即盖在它上面。
2. 输入你的 PIN、图案或密码。如果你打开了 **Unlock with biometrics**，也可以改用指纹。
3. 输错后可以重试。输错次数过多时，需要稍等片刻。

AppLock 本身也以同样的方式上锁，所以别人无法更改你的设置。

![显示 "Enter your PIN" 和数字键盘的锁屏](shots/02-lock-screen.png)

## 更改锁定方式

1. 在主屏幕上，点按 **Settings**。
2. 在 **Appearance** 下，选择 **System**、**Light** 或 **Dark**。
3. 在 **Re-lock** 下，选择解锁后的应用何时再次上锁：离开应用时 **Immediately**，**On screen off**，或 **After 5 min**。
4. 在 **Security** 下，打开 **Unlock with biometrics**。你需要先确认 PIN、图案或密码。这要求你的手机上已经设置了指纹或面部识别。
5. 在 **Protection** 下，打开 **Scramble the PIN pad** 来打乱数字键的位置，这样别人无法通过你点按的位置猜出 PIN。
6. 打开 **Hide notification content for locked apps**，让被锁应用的消息保持私密。这需要在 **Permissions** 中开启 **Notification access**。
7. 在 **Disguise** 下，打开 **Hide from Recents**，让 AppLock 不出现在最近使用的应用列表中。

![Settings：Premium 卡片、Appearance、Re-lock 和 Security](shots/04-settings.png)

## 查看谁试图闯入

1. 打开 **Settings**，打开 **Intruder photo after failed attempts**。
2. 打开 **Permissions**，允许 **Camera**。
3. 从现在起，在锁屏上连续输错三次后，前置摄像头会拍一张照片。
4. 在主屏幕上，点按 **Intruder photos** 查看照片，每张照片都附有当时被打开的应用。
5. 点按 **Security log**，查看解锁、失败尝试和设置更改的记录。

![Intruder photos 页面，显示解锁失败后拍下的照片](shots/07-intruder-photos.png)

## 忘记 PIN 后重新进入

1. 打开 AppLock。在解锁页面，点按 **Can’t get in?**
2. 输入你保存的 8 位恢复码，然后点按 **Continue**。
3. 设置新的 PIN、图案或密码。随后你会得到新的恢复码，旧的恢复码会失效。

如果你还记得 PIN，又想更换恢复码，请打开 **Settings** 并点按 **Replace recovery code**。

## Premium

Premium 是一次性付费，不是订阅。打开 **Settings**，点按 **Unlock Premium**。不购买 Premium，锁定应用也依然免费。Premium 包含：

- 无广告。
- **Fake crash screen (long-press to unlock)**：被锁的应用看起来像是崩溃了，而不是显示锁屏。
- 伪装图标：把 AppLock 在主屏幕上的图标和名称改成 **Calculator**、**Notes** 或 **Weather**。选择 **Calculator** 时，你可以打开 **Open a real calculator instead** 并设置 **Secret code**：输入该密码后按 = 即可打开 AppLock。你的 PIN 同样始终有效。
- 完整的入侵者照片历史。免费版只显示最新的 5 张。
- **Export backup**：把你的设置和锁定列表导出为加密副本，由你自选的密码保护。**Restore backup** 是免费的。

如果你之前购买过 Premium，请在 **Settings** 中点按 **Restore purchases**。

## Questions

**AppLock 为什么需要 Accessibility 权限？**
只是为了发现哪个应用刚刚被打开，以便在你锁定的应用上显示锁屏。它绝不会读取你屏幕上的内容或你输入的内容。详见上文“允许权限”。

**主屏幕显示 "Protection off"，是哪里出了问题？**
可能是 **Accessibility** 或 **Display over other apps** 没有允许，也可能是还没有锁定任何应用。点按 **Finish setup** 打开权限列表，然后检查 **Lock apps**。

**可以把 AppLock 完全隐藏吗？**
不可以。Android 始终会为已安装的应用保留一个图标。购买 Premium 后，你可以把图标和名称换成伪装样式。

**我忘记了 PIN，恢复码也丢了，你们能帮我重置吗？**
不能。AppLock 离线运行，也没有账号，所以无法通过邮件重置。恢复码是重新进入的唯一办法，请把它放在安全的地方。

**备份里包含我的 PIN 或入侵者照片吗？**
不包含。恢复备份后，应用会先要求你设置新的 PIN、图案或密码。

## Privacy

你的 PIN、已锁应用、安全日志和入侵者照片都保存在你的设备上，不会上传。免费版会显示来自 Google AdMob 的广告。请阅读完整的[隐私政策](https://varian1.github.io/privacy.html)。
