# 超凡右键 · FanRightTool 技术支持

超凡右键是一款 macOS Finder 右键工具，支持新建文件、复制路径、常用目录、复制与移动、终端和外部应用打开，以及图片转换、哈希校验和二维码生成。

系统要求：macOS 14.0 或更高版本。支持简体中文与英文。

## 开始使用

1. 安装后打开超凡右键。
2. 在“通用设置”中打开 Finder 扩展管理界面，并启用超凡右键扩展。
3. 在“授权管理”中为需要写入的文件夹授予访问权限。
4. 在 Finder 中右键点击文件、文件夹或空白处，打开“超凡右键”菜单。菜单内容会随所选项目变化。

关闭设置窗口后，可以让主 App 留在菜单栏运行，以处理文件写入和工具请求。

## 常见问题

### Finder 中看不到菜单

确认已打开主 App，并在通用设置所打开的系统界面中启用 Finder 扩展。返回 Finder 重新打开菜单。若曾安装多个测试版本，请反馈具体版本和安装位置，避免同时使用多个副本。

### 提示没有文件夹权限

在授权管理中重新选择相关目录。复制或移动到常用目录时，也需要为目标目录授权；移动还需要对源位置具有相应权限。请先用专用测试目录验证，不需要为此开启完全磁盘访问。

### 某个外部应用打不开

确认目标应用已经安装，并在外部应用设置中启用。对于自定义应用，重新选择对应的 `.app`。各应用支持的文件类型可能不同。

### 隐藏功能是否修改 Finder 全局设置

应用修改文件的隐藏标记；“显示隐藏文件”处理已授权目录直接包含的、由 Finder 隐藏标记隐藏的项目，不包括以点号开头的文件，也不修改 Finder 全局显示设置。

## 联系开发者

邮箱：[fqsyfan@gmail.com](mailto:fqsyfan@gmail.com)

反馈时请提供应用版本、macOS 版本、操作步骤和错误提示。截图或日志请先去除个人信息，不要发送密码、密钥或不必要的原始文件。

开发者：[fanxiangyang](https://github.com/fanxiangyang)

## 隐私

请阅读[隐私政策](https://github.com/fanxiangyang/FanRightTool-Public/blob/main/隐私政策.md)。

## English support

FanRightTool adds file actions and local utilities to the macOS Finder context menu. It requires macOS 14.0 or later and supports English and Simplified Chinese.

Open the app, enable its Finder extension from General settings, and authorize the folders where you want to perform file operations. Keep the main app running in the menu bar for write operations and tool requests.

For help, email [fqsyfan@gmail.com](mailto:fqsyfan@gmail.com) with your app version, macOS version, steps to reproduce the issue, and any error message. Remove personal information from screenshots or logs before sending them.
