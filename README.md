<div align="center">

# Vento

面向 Qoder 的本机单活加速控制台（原 `Qoder Switcher`）

[![Version](https://img.shields.io/github/v/release/726599757/vento-releases?display_name=tag&style=flat-square)](https://github.com/726599757/vento-releases/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-0ea5e9?style=flat-square)](https://github.com/726599757/vento-releases/releases)

到 [Releases](https://github.com/726599757/vento-releases/releases) 下载对应系统的安装包。

</div>

> [!NOTE]
> 安装包未签名。Windows 可能被 SmartScreen 拦截；macOS 请右键打开，或执行 `xattr -cr` 后再启动。从旧版升级时会自动无损迁移数据并沿用已有信任证书。

| 系统 | 安装包形态 |
| --- | --- |
| Windows（Win10/11 amd64） | `*-windows-amd64.exe`（标准用户权限直接运行） |
| Linux（amd64） | `*-linux-amd64.AppImage` |
| macOS（Apple 芯片） | `*-darwin-arm64.dmg` |
| macOS（Intel） | `*-darwin-amd64.dmg` |

完整性校验：核对同一 Release 附带的 `SHA256SUMS.txt`。

Linux 运行：`chmod +x *.AppImage` 后直接执行；无 FUSE 环境可使用 `APPIMAGE_EXTRACT_AND_RUN=1 ./Vento-*.AppImage`。
