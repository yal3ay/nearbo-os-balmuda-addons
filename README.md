# Nearbo OS 附加包（BALMUDA Phone A101BM）

Nearbo OS（基于 LineageOS 24.0 / Android 17）的附加包。ROM 本身不带这些，在手机上打开
「设置 → 系统 → 系统更新 → 附加包」选择安装：手机会下载、校验，然后重启进 TWRP 安装，装完自动回到系统。
系统更新（OTA）之后附加包会通过 addon.d 自动保留。

| 附加包 | 内容 |
|---|---|
| Google 服务 | MindTheGapps 17.0.0 arm64（精简版） |
| Google 服务兼容性 | com.xz1c.compatibility，装好后在 APatch 里授予 root |
| 巴慕达应用 | 巴慕达原厂的时钟、日历、备忘录、计算器、相机，以及它们需要的 com.balmuda.phone.jb 库 |

- 包的列表在 [`addons.json`](addons.json)，文件在 [Releases](../../releases)。
- 每个包都用 Nearbo OS 的发布密钥签名，系统只接受这个密钥签的包。也可以在 TWRP 里手动刷。
- 只适用于 BALMUDA Phone（A101BM / X01A）上的 Nearbo OS，Android 17（SDK 37）。

巴慕达应用、原厂素材的版权属于 BALMUDA / 京瓷；MindTheGapps 中的 Google 应用版权属于 Google。

---

# Nearbo OS add-ons (BALMUDA Phone A101BM)

Optional packages for Nearbo OS (LineageOS 24.0 / Android 17). Install them from
Settings → System → System updates → Add-ons: the phone downloads and verifies them, restarts into
TWRP to install, and restarts back. addon.d keeps them across OTA updates.

- Google services: MindTheGapps 17.0.0 arm64 (trimmed)
- Google services compatibility: com.xz1c.compatibility (grant root in APatch after install)
- BALMUDA apps: stock BALMUDA Clock, Calendar, Notes, Calculator, Camera and the com.balmuda.phone.jb library

The list is [`addons.json`](addons.json); the files are on the [Releases](../../releases) page.
Packages are signed with the Nearbo OS release key. BALMUDA apps are © BALMUDA / Kyocera;
the Google apps in MindTheGapps are © Google.
