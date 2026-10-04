# LXT 互动影视编辑器 · 桌面下载

此公开仓库用于分发 LXT 桌面安装包、更新签名和发布说明，不包含编辑器源码。

在线编辑器：[bjq-next.vercel.app](https://bjq-next.vercel.app/)

| 系统 | v0.2.0 安装包 |
|---|---|
| Windows x64 | [下载安装 EXE](https://github.com/2061863797/bjq-next-releases/releases/download/v0.2.0/LXT_0.2.0_x64-setup.exe) |
| macOS 12+，Intel / Apple 芯片 | [下载通用 DMG](https://github.com/2061863797/bjq-next-releases/releases/download/v0.2.0/LXT_0.2.0_universal.dmg) |

后续版本请查看[最新发布](https://github.com/2061863797/bjq-next-releases/releases/latest)。下载无需 GitHub 登录，需要能够访问 GitHub 及其下载域名。

`.app.tar.gz` 用于 macOS 桌面应用更新；网页下载安装请选择 DMG。`.sig` 和 `latest.json` 是更新及发布校验文件。当前 macOS 包使用 ad-hoc 签名，尚未经过 Apple 公证，Mac 实机安装仍待验收。

已安装的 bjq-next v0.2.0 继续通过原 `/updates/latest.json` 入口检查后续版本，无需因下载托管迁移重装。同版本迁移保留原安装包字节及 Tauri 签名，不产生一次版本升级。

版本安装包地址固定在对应标签下，已发布资产不覆盖。此仓库自动生成的 Source code ZIP 只包含分发说明。
