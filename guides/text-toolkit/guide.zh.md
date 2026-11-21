---
title: 字数统计器：文本工具箱
name: Text Toolkit
tagline: 离线统计字数、转换大小写、清理、排序和对比文本，手机上随手可用。
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## 功能简介

Text Toolkit 只有一个界面，内含九个文本工具。在顶部的输入框里输入或粘贴文字，选一个工具，再复制或分享结果。它可以统计字数、转换大小写、清理空格、排序行、查找替换、反转文字、编码解码、格式化 JSON，还能对比两段文本。

- 所有工具都在手机本地运行，无需联网。
- 无需账号。你的文字不会被上传，应用也不会使用相机、照片、通讯录或位置信息。
- 不保存你的文字。关闭应用后，文字就没有了。
- 免费使用。屏幕底部可能会显示一条横幅广告。

## 快速上手

1. 打开 Text Toolkit。**YOUR TEXT** 框里有一小段示例文字，方便你试用各个工具。
2. 点按 **Clear** 后输入你自己的文字，或点按 **Paste**，用你在其他应用中复制的内容替换现有文字。点按 **Sample** 可以恢复示例文字。
3. 在输入框下方的一行里选择工具：**Counter**、**Case**、**Clean**、**Lines**、**Replace**、**Reverse**、**Encode**、**Format** 或 **Diff**。左右滑动这一行可以看到全部工具。

![主界面：带有 Paste、Sample 和 Clear 的 YOUR TEXT 框、工具栏，以及 Counter 的统计数字](shots/01-home.png)

应用会使用手机的系统语言，支持 11 种语言：英语、西班牙语、葡萄牙语、德语、法语、印地语、印尼语、阿拉伯语、意大利语、俄语和土耳其语。

## 统计字数和字符数

1. 点按 **Counter**。
2. 查看各项数字：**Characters**、**No spaces**、**Words**、**Sentences**、**Paragraphs**、**Lines** 和 **Reading time**。
3. 在下方的 **TOP WORDS** 中，可以看到你用得最多的词（最多八个）及各自出现的次数。

数字会随着你的输入实时变化。阅读时间按每分钟 200 词计算。

## 转换大小写

1. 点按 **Case**。
2. 上下滑动卡片。每张卡片以另一种样式显示你的文字：**UPPERCASE**、**lowercase**、**Title Case**、**Sentence case**、**Capitalized Case**、**aLtErNaTiNg**、**iNVERSE**、**camelCase**、**PascalCase**、**snake_case**、**kebab-case**、**CONSTANT_CASE** 和 **URL slug**。
3. 在你想要的卡片上点按 **Copy**。

![Case 工具：UPPERCASE、lowercase 和 Title Case 卡片，每张都有 Use input、Share 和 Copy](shots/02-case.png)

## 清理文本

1. 点按 **Clean**。
2. 点按其中一个操作：
   - **Clean all**：一次删除制表符、重复空格、行尾空格、空行和重复行。
   - **Extra spaces**、**Trim lines**、**No empty lines**、**No duplicates** 或 **Remove tabs**：只做对应的这一件事。
   - 换行操作：删除文字中的换行。
3. 在 **CLEANED RESULT** 下查看结果。输入框里你自己的文字保持不变。

![Clean 工具：清理按钮和 CLEANED RESULT 卡片](shots/03-clean.png)

## 排序或反转

1. 点按 **Lines**，可以按整行处理：**A to Z**、**Z to A**、**Reverse lines**、**Shortest first**、**No duplicates** 或 **Reverse characters**。排序时会忽略大小写和行首的空格。
2. 点按 **Reverse** 来颠倒文字：**Entire text**、**Each word**、**Word order**、**Line order** 或 **Characters per line**。
3. 结果会显示在按钮下方的卡片中。

## 查找和替换

1. 点按 **Replace**。
2. 在 **Find** 中输入要查找的文字，在 **Replace with** 中输入新文字。
3. 点按选项来开启或关闭：**Replace all**（关闭时只替换第一处匹配）、**Case sensitive** 和 **Whole word**。
4. 查看替换次数和 **REPLACEMENT PREVIEW**。两者都会随着你的输入实时更新。

![Replace 工具：Find 和 Replace with 输入框、三个选项按钮、替换次数和预览](shots/04-replace.png)

搜索时只会查找你输入的原文，不支持正则表达式或通配符。

## 编码、解码和格式化

1. 点按 **Encode**，选择 **URL**、**Base64** 或 **HTML Entities**，然后点按 **Encode** 或 **Decode**。
2. 点按 **Format**，选择 **Format JSON** 可用两个空格缩进 JSON，选择 **Minify JSON** 可把它压缩成一行，选择 **Strip Markdown** 可把 Markdown 转成纯文本。
3. 如果 JSON 有错误，屏幕上方会出现一行以 "Invalid JSON" 开头的提示，并说明错在哪里。

## 对比两段文本

1. 把第一个版本放进 **YOUR TEXT**，然后点按 **Diff**。
2. 在 **COMPARE WITH** 中输入或粘贴第二个版本。
3. 查看 **DIFF COMPARISON**。只出现在第二个版本中的行为绿色，前面带 **+**。只出现在第一个版本中的行为红色，前面带 **-**。相同的行没有标记。
4. 点按 **Copy Diff**，可以复制带有 + 和 - 标记的对比结果。

![Diff 工具：COMPARE WITH 输入框，以及 DIFF COMPARISON 卡片，其中有一行绿色的新增内容和一行红色的删除内容](shots/05-diff.png)

## 复制、分享或继续处理

1. 在结果卡片上点按 **Copy**，把结果放入剪贴板。
2. 点按 **Share**，把结果发送到其他应用。
3. 点按 **Use input**，把结果移入 **YOUR TEXT**，这样就可以再用另一个工具继续处理。

## 高级版

所有工具都免费。另有一项可选的一次性购买，可以去除广告。只需付费一次，不是订阅。

## 常见问题

**没有网络能用吗？**
可以。九个工具都在手机上运行。只有广告和去除广告的购买需要网络连接。

**我的文字会被保存吗？**
不会。应用只在打开期间保留你的文字。想留住的结果，请先复制或分享出去。

**切换工具后，为什么结果是空的？**
Clean、Lines、Reverse、Encode 和 Format 共用一张结果卡片，切换工具时会清空。再点一次对应的操作即可。修改文字后也请这样做。Counter、Case、Replace 和 Diff 会自动更新。

**支持深色模式吗？**
支持。应用会使用你手机上设置的浅色或深色主题。

**开源许可在哪里看？**
滑到最底部，点按 **Open-source licenses**。**Privacy policy** 就在它旁边。

## 隐私

你的文字只在手机上处理，不会被上传或保存。应用可能显示来自 Google AdMob 的广告；在法律要求的地区，应用会先询问你的选择，你之后可以在主界面通过 **Ad privacy choices** 更改。请阅读完整的[隐私政策](https://varian1.github.io/text-toolkit/privacy.html)。
