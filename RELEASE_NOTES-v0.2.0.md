# Give Me a Song 0.2.0 Preview（Android +12 热修）

这是面向初期用户的 Android、华为兼容设备和 Windows 预览版本。

## 主要功能

- 轻点“我”开始一首歌，或拖向月亮进入睡前模式。
- 支持应用歌单和用户导入的本机音频。
- Android 后台播放、锁屏媒体卡和系统媒体控制。
- 定时心跳与 Android 屏幕使用时长心跳。
- 离线歌曲、听歌记录、纪念词、分享卡和中英文界面。

## 下载哪个文件

- Android（64 位 ARM）：`Give-Me-a-Song-0.2.0+12-android-arm64.apk`
- Windows x64：`Give-Me-a-Song-0.2.0+11-windows-x64.zip`
- 校验：`SHA256SUMS.txt`

## Android +12 热修

- 修复部分 Android 15 / 厂商系统设备安装后无法启动的问题。
- 根因是 Release 混淆压缩移除了 WorkManager / Room 启动时需要的构造方法；热修版已显式保留该运行时入口。
- 已在 iQOO 15 真机完成全新安装、冷启动、播放页和主要页面流程验证。
- 使用与此前版本相同的正式签名，可覆盖安装升级。

Windows ZIP 必须完整解压后运行，不能只复制 EXE。当前 Windows 版本尚未购买代码签名证书，可能出现 SmartScreen 提示，请先核对 SHA-256。

## 平台边界

- 华为 / 鸿蒙兼容设备：仅适用于仍支持安装 Android APK 的设备。
- HarmonyOS NEXT：当前不是原生 HAP 应用，不支持。
- iOS、iPadOS、macOS：当前没有 Mac 构建与签名环境，本版本不提供。

## 隐私与反馈

- [中文隐私政策](https://antsally9-dev.github.io/give-me-a-song-privacy/zh-CN/)
- [English Privacy Policy](https://antsally9-dev.github.io/give-me-a-song-privacy/en-US/)
- 支持邮箱：`antsally9@gmail.com`

这是 Preview 版本。如果遇到异常，请提供设备型号、系统版本、App 版本及复现步骤。

