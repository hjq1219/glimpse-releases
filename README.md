# Glimpse

轻量 macOS 菜单栏截图翻译工具。按 Option + S 框选文字，自动显示原文与中文译文；支持中英文识别、自定义快捷键和字号。

此仓库只用于发布安装包和更新清单，不包含应用源码。

## 安装

需要 **Apple 芯片 Mac（M1 或更新）和 macOS 15 或更新版本**，不支持 Intel Mac。

当前版本：[下载 Glimpse 0.11.1](https://github.com/hjq1219/glimpse-releases/releases/download/v0.11.1/Glimpse-0.11.1-arm64.dmg)，或查看 [Releases](https://github.com/hjq1219/glimpse-releases/releases)。应用及 DMG 已通过 Developer ID 签名和 Apple 公证。打开 DMG，将 Glimpse 拖到 Applications，推出磁盘后从“应用程序”启动。

首次运行按系统提示下载英文和简体中文翻译语言包；首次截图允许屏幕录制。截图和译文不建立历史记录。临时截图读入内存后尝试删除，强制结束或删除失败可能留下临时文件。

## 更新

从 0.11.0 开始，菜单栏提供“检查更新…”入口，确认后下载、校验并安装更新。默认不后台检查或静默安装，检查和下载需要能访问 GitHub。

0.9.1 等旧版本需要手动安装一次新 DMG。从临时签名旧版本迁移时，可能需要重新添加一次屏幕录制权限；后续保持同一开发者团队和应用标识的更新通常可沿用授权，系统仍可能因自身策略要求再次确认。
