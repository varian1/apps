---
title: 一键锁屏 TapLock
name: TapLock
tagline: 一键锁定手机屏幕，指纹和人脸解锁照常使用。
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## 功能简介

TapLock 在屏幕上放一个大大的 **Lock** 按钮。点一下，手机马上锁屏，和按电源键一样。电源键不好按、磨损或者坏了的时候，用它特别方便。

- 使用无障碍锁屏时，你仍然可以用指纹、人脸、PIN 码或图案正常解锁。
- Device Admin 锁屏是另一种锁屏方式，不需要开启无障碍功能。
- 只有一个页面、一个按钮，无需注册账号，也无需登录。
- 免费使用，含广告。

## 开始使用

1. 打开 TapLock。第一次打开时，**Lock** 按钮下方会显示“One-time setup needed (about a minute).”
2. 点按 **Set up TapLock**，进入 **Lock setup** 页面。
3. 在两种锁屏方式中选择一种：
   - **Accessibility lock**（推荐，需要 Android 9 或更高版本）：效果和电源键一样，指纹和人脸解锁照常可用。
   - **Device Admin lock**：不需要无障碍功能。下次解锁时，Android 会要求你输入 PIN 码、图案或密码。
4. 按照下面对应的步骤操作。

你随时可以点按主页右上角的设置图标，重新打开 **Lock setup**。

## 开启无障碍锁屏

1. 在 **Lock setup** 页面的 **Accessibility lock** 卡片中，点按 **Turn on Accessibility lock**。
2. 弹出对话框 **Allow TapLock to use Accessibility?**，请先阅读 TapLock 如何使用该权限。
3. 点按 **Agree** 继续。如果点按 **Decline**，不会有任何变化，无障碍锁屏保持关闭。
4. Android 的无障碍设置会打开。找到 TapLock，通常在“已下载的应用”下面。
5. 打开“Use TapLock”，点按 **Allow**，然后返回 TapLock。
6. 卡片上显示 **On**，顶部出现 **You're all set**。点按 **Back to Lock**。

![对话框“Allow TapLock to use Accessibility?”，带有 Decline 和 Agree 两个按钮](shots/04-accessibility-consent.png)

**TapLock 为什么需要无障碍权限？** TapLock 使用无障碍服务 API 只是为了在你点按 **Lock** 按钮时锁定屏幕，效果和按电源键一样，所以指纹和人脸解锁可以照常使用。TapLock 不会读取你的屏幕内容，不会看到你输入的内容，也不会通过这个权限收集、存储或分享任何个人数据。在 Android 设置打开之前，你可以先选择 **Agree** 或 **Decline**，之后也可以随时关闭该权限。

如果卡片上显示 **Starting** 超过几秒钟，请在无障碍设置中先关闭再重新打开 TapLock。如果 Android 设置中的开关是灰色的，无法点按，请在 **Lock setup** 页面点按 **Switch greyed out?**，按提示操作。

## 改用 Device Admin 锁屏

1. 在 **Lock setup** 页面的 **Device Admin lock** 卡片中，点按 **Enable Device Admin**。
2. Android 会请你确认。TapLock 使用该权限只是为了在你点按 **Lock** 按钮时锁定屏幕。
3. 卡片上显示 **On**。

![Lock setup 页面：Accessibility lock 卡片显示 On，Device Admin lock 卡片上有 Enable Device Admin 按钮](shots/02-setup.png)

使用这种锁屏方式时，下次解锁 Android 会要求输入 PIN 码、图案或密码，而不是指纹或人脸。如果两种方式都已开启，TapLock 会使用无障碍锁屏。

## 锁定屏幕

1. 打开 TapLock。按钮下方的文字以“Ready.”开头。
2. 点按 **Lock**。屏幕立刻锁定。
3. 像平时一样解锁手机。

![主页上有圆形的 Lock 按钮，下方显示“Ready. Fingerprint and face unlock stay on.”](shots/01-home.png)

## 使用深色模式

1. 在手机的 Android 系统设置中打开深色主题。
2. 打开 TapLock。它会跟随手机自动切换为深色，应用内没有单独的设置。

![深色模式下的 TapLock 主页](shots/03-dark-mode.png)

## 更改语言

1. 在主页点按设置图标，打开 **Lock setup**。
2. 打开语言选择器。
3. 从 31 种语言中选一种，或保持系统默认，让 TapLock 跟随手机语言。

![语言选择器和语言列表](shots/06-language.png)

阿拉伯语、乌尔都语和希伯来语从右向左显示。在 Android 13 或更高版本中，你也可以在 Android 的应用语言设置里更改 TapLock 的语言。

## 关闭锁屏方式或卸载应用

1. 在主页点按设置图标，打开 **Lock setup**。
2. 要关闭无障碍锁屏，请点按 **Manage in Accessibility settings**，然后在那里关闭 TapLock。
3. 要关闭 Device Admin 锁屏，请点按 **Turn off Device Admin**。
4. 卸载 TapLock 之前，请先关闭 Device Admin。Android 不允许卸载仍处于激活状态的设备管理应用。

![Lock setup 页面，显示 You're all set 卡片和关闭 Device Admin 的按钮](shots/05-device-admin-on.png)

## 常见问题

**TapLock 为什么需要无障碍权限？**
只是为了在你点按 **Lock** 时锁定屏幕，和按电源键一样。它不会读取你的屏幕内容，也看不到你输入的内容。如果你不想授予该权限，可以使用 Device Admin 锁屏。

**用 TapLock 锁屏后，指纹无法解锁，为什么？**
你使用的是 Device Admin 锁屏，它会让 Android 在解锁时要求输入一次 PIN 码、图案或密码。开启无障碍锁屏，指纹和人脸解锁就能照常使用。

**我无法卸载 TapLock，怎么办？**
打开 **Lock setup**，点按 **Turn off Device Admin**，然后再卸载。

**需要什么版本的 Android？**
无障碍锁屏需要 Android 9 或更高版本。更低版本请使用 Device Admin 锁屏。

**TapLock 有中文界面吗？**
TapLock 支持 31 种语言。你可以在 **Lock setup** 页面选择语言，也可以保持系统默认。

## 隐私

TapLock 使用无障碍和 Device Admin 权限只是为了锁定屏幕，不会通过这些权限收集任何个人数据。应用会显示 Google AdMob 的广告；在需要的地区，你可以在 **Lock setup** 页面通过 **Privacy settings** 更改广告选择。请阅读完整的[隐私政策](https://varian1.github.io/LockAppOnlyWeb/privacy.html)。
