<div align="center">
  <img src="./docs/images/server-icon.png" alt="ScrapeFun Server" width="80" />
  <h1>ScrapeFun Server for Android</h1>
  <p><a href="./README.md">简体中文</a> · <strong>English</strong></p>
  <p><a href="https://scrapefun.com/?lang=en">Website</a> · <a href="https://github.com/HaoweiLi97/scrapefun-server-android/releases/latest">Download</a> · <a href="https://github.com/HaoweiLi97/scrapefun-server-android/releases">All releases</a> · <a href="https://scrapefun.com/?lang=en#/docs">Documentation</a></p>
</div>

Run ScrapeFun Server on an Android phone or tablet to manage movies, comics and remote resources, and connect from a browser or Client on another device. Server and Android Client are separate apps and can be installed together.

## Downloads and device requirements

| Item | Stable 0.5.0 |
| --- | --- |
| Download | [Release page](https://github.com/HaoweiLi97/scrapefun-server-android/releases/tag/v0.5.0) |
| System | Android 9 or later |
| Architecture | arm64-v8a (64-bit ARM) |
| Installer | `scrapefun-server-android-0.5.0-arm64-v8a.apk` |
| Verification | APK `.sha256` and `SHA256SUMS` |

The APK is available through GitHub. The app is not yet available on Google Play; download from this repository's release page.

## Installation and first use

1. Download the APK and allow installation from your download source when Android asks.
2. Open ScrapeFun Server and complete its initial preparation. Keep enough free storage for installation and preparation.
3. Start the server, complete setup in its management interface, and grant access to local media folders as needed.
4. To connect from another device, use the Android device's actual LAN address and server port. `localhost` on another device does not refer to this Android device.

## Updates and backups

Open Application Updates in the app's runtime settings to check automatically, check manually or skip a version. Android confirms installation after the download. Version 0.5.0 retains the previous release's signing identity; stop the server and back up its data before updating in place.

Stable and beta updates use separate channels. Keep the same app and signing identity. If Android reports a signing mismatch, verify the source before taking action; do not uninstall the existing app to bypass the warning. Uninstalling can erase local Server data.

<details>
<summary>Troubleshooting</summary>

For installation failures, check the Android version, CPU architecture and free storage. If another device cannot connect, confirm that the server is running and check its address, port and network. Android background restrictions can affect the running service; also check battery and background-app settings.

</details>

## Support and licensing

[Product overview](https://github.com/HaoweiLi97/ScrapeFun/blob/main/README.en.md) · [Documentation](https://scrapefun.com/?lang=en#/docs) · [Report an issue](https://github.com/HaoweiLi97/ScrapeFun/issues)

For accounts, activation and private logs, contact `scrapefun@outlook.com`. Do not post passwords, activation codes or private data publicly. See [licensing and agreements](https://github.com/HaoweiLi97/ScrapeFun/blob/main/legal/README.en.md) and [third-party components](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.en.md).
