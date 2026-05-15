# Kazumi 老手机32位适配优化版 v2.1.1

> 32位 + 64位双ABI · Android 8.1+ 兼容 · 老SOC白屏修复 · 特摄搜索解锁

基于 [Predidit/Kazumi](https://github.com/Predidit/Kazumi) v2.1.1

---

## 新增支持
- 32位 ARM (armeabi-v7a) Android 设备
- Android 8.1 (SDK 27) 及以上老系统兼容
- 骁龙450 / MT6765 等老SOC实测通过
- 解锁特摄剧标签搜索（假面骑士、奥特曼等）

## 修改内容
- 32位 + 64位双ABI，按设备自动选择
- Android 11 及以下设备隐藏Vulkan选项，自动回退OpenGL
- arm64 注入兼容版 libmpv，修复由于过老的SOC不适配的兼容性问题而导致的白屏

## 运行要求
- 推荐 Android 8.1 (SDK 27) 及以上
- 2GB+ 运行内存

## 下载
前往 [Releases](https://github.com/bug333555/Kazumi-32-/releases) 下载最新 APK

## 更新说明
适配版不定时更新，跟随 Kazumi 上游主版本

## 问题反馈
遇到兼容性问题请提 Issue，附上：
- 设备型号（如 OPPO A5 PBAM00）
- Android 版本（设置 → 关于手机）以及Kazumi内的报错信息
- SOC 型号（可用 DevCheck 等 App 查看）
- 问题描述（白屏/闪退/视频无法播放等）
- 操作步骤（如何触发的问题）

## 鸣谢
- 原项目：[Predidit/Kazumi](https://github.com/Predidit/Kazumi)
- 弹幕服务：DanDanPlay API
- 图标：Yuquanaaa / [Pixiv](https://www.pixiv.net/artworks/116666979)
- 字体：Mi Sans by Xiaomi
