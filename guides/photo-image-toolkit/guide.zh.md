---
title: 图片压缩 缩放 裁剪 格式转换工具
name: Photo & Image Toolkit
tagline: 手机上压缩、改尺寸、裁剪、转格式、拼图、一键抠图,照片处理一个应用搞定。
project: photo-image-toolkit
package: io.github.varian1.photoimagetoolkit
version: 1.0.0
updated: 2026-11-17
privacy: https://varian1.github.io/photoimagetoolkit/privacy.html
---

## 功能简介

Photo & Image Toolkit 把五个常用的照片工具放在一个应用里:压缩、缩放与裁剪、格式转换、拼图和抠图。所有工具都在手机上运行,并且保存为新的副本,不会改动原照片。应用支持 14 种语言,会跟随手机的语言设置。

- 无需账号。照片只在你的设备上处理,不会上传。
- 应用只能看到你选择的照片。
- 保存的副本会去除位置信息和相机信息。
- 免费使用,含广告。一次性购买 Premium 即可去除广告,并解锁批量处理。

## 快速开始

1. 打开 Photo & Image Toolkit。主屏幕上会显示五个工具。
2. 点按一个工具,例如 **Compress**。
3. 点按 **Select photo**,选择一张照片。应用不会请求访问你的整个相册。
4. 结果生成后,点按 **Save** 将其保存为新照片,或点按 **Share** 发送给其他应用。

![主屏幕,显示 Compress、Resize & Crop、Remove Background、Convert 和 Collage 工具](shots/01-home.png)

## 压缩照片

1. 在主屏幕上点按 **Compress**,再点按 **Select photo**。
2. 在 **Quality** 下选择 **Low**、**Medium** 或 **High**。选择 Low 时文件最小。
3. 在 **Output format** 下选择 **JPEG** 或 **WebP**。
4. 如果文件必须小于某个大小,请在 **Target size (optional)** 中输入数值,单位为 KB。
5. 点按 **Compress**。你会看到压缩前后的对比,包括原始大小、新的大小和节省的空间。
6. 点按 **Save** 或 **Share**。

![压缩界面:照片压缩前后对比,358 KB 缩小到 92.9 KB,并有 Save 和 Share 按钮](shots/02-compress.png)

如果要达到目标大小就必须大幅降低画质,应用会提示你,并给出能做到的最小结果。

## 缩放、裁剪、旋转或翻转

1. 点按 **Resize & Crop**,再点按 **Select photo**。
2. 在 **Crop ratio** 下保持 **Free**,或选择固定比例,例如 **1:1**、**4:5** 或 **16:9**。
3. 在裁剪框内拖动可移动裁剪框。拖动裁剪框角上的蓝点可放大或缩小。
4. 点按 **⟲ Left** 或 **⟳ Right** 旋转照片。点按 **Flip** 按钮可镜像翻转。
5. 在 **Resize** 下,选择 **Original** 保持原尺寸,选择 **Pixels** 输入宽度,选择 **%** 按百分比缩放,或选择 **Presets** 使用适合社交媒体和文档的现成尺寸。
6. 在 **Format** 下选择 **JPEG**、**PNG** 或 **WebP**。
7. 查看 **Output** 一行中的最终尺寸,然后点按 **Apply**。
8. 点按 **Save** 或 **Share**。

![缩放与裁剪界面:4:5 裁剪框、旋转和翻转按钮,以及 Resize 和 Format 选项](shots/03-resize.png)

## 转换为 JPEG、PNG 或 WebP

1. 点按 **Convert**,再点按 **Select photo**。可以打开 HEIC、PNG、WebP 和 JPEG 照片。
2. 在 **Convert to** 下选择 **JPEG**、**PNG** 或 **WebP**。按钮下方有一行简短说明,介绍各格式的适用场景。
3. 选择 JPEG 或 WebP 时,请选择 **Quality**:**Low**、**Medium** 或 **High**。
4. 点按卡片底部的 **Convert to** 按钮,例如 **Convert to JPEG**。
5. 对比转换前后的大小,然后点按 **Save** 或 **Share**。

![转换界面:一张 HEIC 照片转换为 JPEG,并显示转换前后的大小](shots/04-convert.png)

如果照片有透明区域而你选择了 JPEG,应用会提醒你这些区域会变成白色。

## 制作拼图

1. 点按 **Collage**,再点按 **Select photos**。选择 2 到 9 张照片。
2. 要调整顺序,先在预览中点按一张照片,再点按要与它交换位置的照片。
3. 在 **Layout** 下选择照片的排列方式。标有 ★ 的版式属于 Premium。
4. 在 **Shape** 下选择 **1:1**、**4:5**、**9:16** 或 **16:9**。
5. 设置照片之间的 **Spacing**、**Corners**(**Square**、**Soft** 或 **Round**)以及 **Background** 颜色。
6. 在 **Format** 下选择 **JPEG** 或 **PNG**。
7. 点按 **Create collage**,然后点按 **Save** 或 **Share**。

![拼图界面:四张照片组成的网格,以及 Layout、Shape 和 Spacing 选项](shots/05-collage.png)

## 抠图去背景

1. 点按 **Remove Background**,再点按 **Select photo**。应用会立即抠出主体。画面中只有一个清晰的主体(人物、宠物或商品)时效果最好。
2. 点按 **Before** 和 **After**,对比抠图结果与原图。
3. 在 **Background** 下选择主体后面的内容:
   - **Transparent**:保存为透明背景的 PNG。
   - **Colour**:从显示的颜色中选择一种。
   - **Photo**:点按 **Choose background photo**,再选择另一张照片。
4. 点按 **Save** 或 **Share**。

![抠图界面:一个马克杯在透明背景上被抠出,并有 Transparent、Colour 和 Photo 选项](shots/06-background.png)

开通 Premium 后,还可以把主体放在渐变背景上。

抠图在你的设备上完成。第一次使用这个工具时,手机可能需要短暂联网,通过 Google Play 服务下载抠图模型。

## 打开设置

1. 在主屏幕上,点按右上角的 **Settings**。
2. 在 **Premium** 下,可以查看当前是 **Free** 还是 **Premium**,点按 **Upgrade to Premium**,或点按 **Restore purchases**。
3. 在 **Privacy** 下,可以打开 **Privacy Policy** 或 **Terms of Use**。在部分国家和地区,你还会看到 **Ad privacy choices**,可在这里更改广告同意设置。

![设置界面,显示 Premium 状态、Restore purchases 和隐私链接](shots/07-settings.png)

## Premium

Premium 是一次性付费,不是订阅。点按主屏幕上的 **★ Go Premium**,或 **Settings** 中的 **Upgrade to Premium**。它包含:

- 无广告。
- 使用 **Batch** 按钮批量处理:一次最多压缩或转换 20 张照片,或一次最多抠图 10 张。也可以一次缩放多张照片。
- 高分辨率导出:长边最高 8192 px(免费版为 4096 px),抠图最高 4096 px(免费版为 2048 px),并支持更大的拼图。
- 在 **Remove Background** 中使用 **Smooth edges**,让抠图边缘更柔和,还有渐变背景模板。
- 更多拼图版式。

如果你之前已购买 Premium,请点按 **Settings** 或 Premium 界面中的 **Restore purchases**。

![Premium 界面,显示功能列表和购买按钮](shots/08-premium.png)

## 常见问题

**会改动我的原照片吗?**
不会。每个工具都会保存为新的副本。在 Android 上,副本会保存到相册中的 **Photo Toolkit** 相簿。

**我的照片会被上传吗?**
不会。五个工具都在你的手机上运行,抠图也一样。

**为什么保存后的照片像素比原图小?**
免费版保存的照片长边最大为 4096 px,抠图最大为 2048 px。更大的照片会被缩小。Premium 可提高这些上限。

**可以保存为 HEIC 吗?**
在 Android 上不可以。你可以打开 HEIC 照片,并把它们转换为 JPEG、PNG 或 WebP。

**抠图时出现错误,怎么办?**
这个工具需要 Google Play 服务。请确认手机已联网,并且已设置好 Google Play,然后再试一次。

## 隐私

你的照片只在设备上处理,不会上传。免费版会显示来自 Google AdMob 的广告。请阅读完整的[隐私政策](https://varian1.github.io/photoimagetoolkit/privacy.html)。
