# 卿诚VPN Android

这里发布卿诚VPN Android 1.4.12 视觉更新版及相关资源。当前版本更新桌面盾牌图标与连接页背景；原 1.4.12 连接逻辑保持不变，应用标签为“卿诚VPN”，Manifest 中 `debuggable=false`。

## 下载与文档

| 内容 | 说明 |
|---|---|
| [GitHub Release](https://github.com/zhanwa2998/qinchengvpn-android/releases/tag/android-v1.4.12-visual-refresh) | APK、APKTool Smali 源码包、中文使用说明及视觉资源 |
| [使用说明](USAGE.md) | Android 安装、连接授权和网络出口说明 |
| [发布说明](RELEASE_NOTES.md) | 本次视觉更新和签名信息 |
| [启动器图标矢量](assets/ic_launcher_foreground.xml) | 青绿色盾牌图标前景 |
| [连接页背景](assets/connection-background-v1.4.12.png) | 集成到连接页 orb 的视觉资源 |

源码附件是从提供的 1.4.12 APK 解包得到的 APKTool Smali 级工程，不是原始 Java/Gradle 工程。代码树未改动，修改集中在图标、连接背景、应用名称与 Manifest 调试标志。APK 沿用提供版本的 Android Debug 证书，以保持与原包同证书；这不是应用商店生产签名。

## 网络出口说明

VPN Gate 使用志愿者运营的公开中继，网络中可能包含家庭宽带出口，但没有官方公布的住宅 IP 比例，也不能保证特定节点属于住宅网络。Cloudflare WARP 的出口来自 Cloudflare 网络，不等同于住宅宽带 IP。
