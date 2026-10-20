# ScrapeFun Server for Android

面向 Android 的 ScrapeFun 综合媒体服务器，支持影视、漫画与远程资源。

本仓库用于发布 Android Server 安装包和更新清单，与 Android 客户端发布仓库相互独立。包名为 `com.scrapefun.server`。

## 下载与更新

正式安装包发布在 [Releases](https://github.com/HaoweiLi97/scrapefun-server-android/releases)。稳定版使用普通 release，测试版使用 prerelease；两条更新通道独立。

GitHub 分发版在应用运行设置中提供“应用更新”，支持自动检查、手动检查和跳过版本。更新必须通过大小、SHA-256、包名、递增 versionCode 和本机安装签名检查，然后由 Android 系统确认安装。更新前停止服务器并保留完整数据备份。

Google Play 分发版使用 Google Play 应用内更新，不从 GitHub 下载或安装 APK。Google Play 上架尚未完成；本仓库的建立不代表商店已经上架。

每个 GitHub release 包含 `scrapefun-server-android-manifest.json`、对应架构的签名 APK、APK 的 `.sha256` 和 `SHA256SUMS`。没有经过发布签名校验的开发 APK 不进入正式更新源。

初始发布仓库尚无可安装版本。当前受支持的运行环境架构为 `arm64-v8a`，其他架构以实际发布资产为准。
