# Agent Studio 桌面版

多模型 Agent 配置工作台的 Windows 安装包与更新源。

## 下载安装

前往 [最新版本](https://github.com/YQSida/AgentTools-Releases/releases/latest)，下载 `Agent-Studio-Setup-版本-x64.exe` 并运行。安装后会创建 **多模型 Agent 工作台** 桌面快捷方式，无需另行安装 Node.js、PowerShell 或浏览器环境。

适用于 Windows x64。安装版会在启动时自动检查更新，也可在右上角 **版本与更新** 或菜单 **检查更新** 中手动检查。发现新版后，由你确认下载；下载完成后，再确认重启安装。

已保存的 Agent 配置会保留。更新前请先保存工作台中的草稿。

## 发布文件

每个正式版本包含：

- `Agent-Studio-Setup-版本-x64.exe`：Windows 安装程序。
- 同名 `.exe.blockmap`：增量下载辅助文件。
- `latest.yml`：版本号、下载路径与 SHA-512 校验清单。

此仓库公开分发桌面应用及更新清单，不存放用户本机的配置、账户信息或密钥。安装包包含运行工作台所需的应用代码。