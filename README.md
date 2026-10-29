# ScrapeFun Server for Android

面向 Android 的 ScrapeFun 综合媒体服务器，支持影视、漫画与远程资源。

本仓库用于发布 Android Server 安装包和更新清单，与 Android 客户端发布仓库相互独立。包名为 `com.scrapefun.server`。

## 下载与更新

正式安装包发布在 [Releases](https://github.com/HaoweiLi97/scrapefun-server-android/releases)。稳定版使用普通 release，测试版使用 prerelease；两条更新通道独立。

GitHub 分发版在应用运行设置中提供“应用更新”，支持自动检查、手动检查和跳过版本。更新必须通过大小、SHA-256、包名、递增 versionCode 和本机安装签名检查，然后由 Android 系统确认安装。更新前停止服务器并保留完整数据备份。

Google Play 分发版使用 Google Play 应用内更新，不从 GitHub 下载或安装 APK。Google Play 上架尚未完成；本仓库的建立不代表商店已经上架。

每个 GitHub release 包含 `scrapefun-server-android-manifest.json`、对应架构的签名 APK、APK 的 `.sha256` 和 `SHA256SUMS`。没有经过发布签名校验的开发 APK 不进入正式更新源。

当前稳定版为 [0.4.3](https://github.com/HaoweiLi97/scrapefun-server-android/releases/tag/v0.4.3)（versionCode 4003），支持 Android 9 或更新版本、`arm64-v8a` 设备，使用与上一版一致的发布证书。更新前请停止服务器并保留完整备份，再覆盖安装新版 APK；安装和首次准备需预留足够空间。

[本版更新说明](https://github.com/HaoweiLi97/scrapefun-server-android/releases/tag/v0.4.3) · [最新签名 APK](https://github.com/HaoweiLi97/scrapefun-server-android/releases/latest/download/scrapefun-server-android-0.4.3-arm64-v8a.apk)
