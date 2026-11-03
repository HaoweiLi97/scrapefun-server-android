<div align="center">
  <img src="./docs/images/server-icon.png" alt="ScrapeFun Server" width="80" />
  <h1>ScrapeFun Server for Android</h1>
  <p><strong>简体中文</strong> · <a href="./README.en.md">English</a></p>
  <p><a href="https://scrapefun.com/">官网</a> · <a href="https://github.com/HaoweiLi97/scrapefun-server-android/releases/latest">下载安装</a> · <a href="https://github.com/HaoweiLi97/scrapefun-server-android/releases">全部发行</a> · <a href="https://scrapefun.com/#/docs">使用文档</a></p>
</div>

Android 服务端，在手机或平板上运行 ScrapeFun，管理影视、漫画与远程资源，并供浏览器或其他设备的 Client 连接。Server 与 Android Client 是两个独立应用，可同时安装。

## 下载与设备要求

| 项目 | 0.5.0 正式版 |
| --- | --- |
| 下载 | [发行页](https://github.com/HaoweiLi97/scrapefun-server-android/releases/tag/v0.5.0) |
| 系统 | Android 9 或更新版本 |
| 架构 | arm64-v8a（64 位 ARM） |
| 安装包 | `scrapefun-server-android-0.5.0-arm64-v8a.apk` |
| 校验 | APK 的 `.sha256`、`SHA256SUMS` |

当前通过 GitHub 提供 APK。Google Play 尚未上架；请从本仓库的发行页下载。

## 安装与首次使用

1. 下载 APK，按 Android 系统提示允许当前下载来源安装应用。
2. 打开 ScrapeFun Server，完成应用内的首次准备。安装和准备过程需要足够可用空间。
3. 启动服务，通过管理界面完成初始化，并按需要授予本机媒体目录的访问权限。
4. 需要其他设备连接时，使用 Android 设备的实际局域网地址和服务端口；其他设备上的 `localhost` 不指向这台 Android 设备。

## 更新与备份

在应用运行设置中打开“应用更新”，可自动检查、手动检查或跳过版本。下载后由 Android 系统确认安装。0.5.0 沿用上一版的发布证书，可在停止服务器并备份数据后覆盖安装。

稳定版和测试版使用独立更新频道。请沿用原应用与签名；系统提示签名不一致时，先检查来源，不要直接卸载原应用绕过提示。卸载可能清除本机 Server 数据。

<details>
<summary>故障排查</summary>

安装失败时，请检查系统版本、设备架构和剩余空间。无法从其他设备连接时，先确认服务仍在运行，再检查地址、端口和网络。Android 的后台限制可能影响服务运行，请同时核对系统的电池与后台运行设置。

</details>

## 支持与许可

[产品主页](https://github.com/HaoweiLi97/ScrapeFun) · [使用文档](https://scrapefun.com/#/docs) · [问题反馈](https://github.com/HaoweiLi97/ScrapeFun/issues)

账号、激活及私密日志请联系 `scrapefun@outlook.com`，不要公开上传密码、激活码或完整私人数据。软件授权见[许可与协议](https://github.com/HaoweiLi97/ScrapeFun/blob/main/legal/README.md)，开源组件见[第三方组件说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.md)。
