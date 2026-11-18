# ClearClip Downloads

ClearClip 桌面端是一个使用 Tauri 2、Rust 和 React 构建的本地视频解析工具，支持皮皮虾和抖音公开普通视频分享链接，并将平台公开返回的原始/无水印播放流保存到本机。本下载页还提供仅支持皮皮虾的 iPhone/iPad 快捷指令。

## 直接下载

### macOS 0.2.0 Universal

同时支持 Apple Silicon 与 Intel Mac：

- [下载 ClearClip 0.2.0 macOS 朋友版](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-0.2.0-macOS-Universal-friends.zip)
- [下载 SHA-256 校验文件](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-0.2.0-macOS-Universal-friends.zip.sha256)

解压后按住 Control 点击 `install.command`，选择“打开”。朋友分享版没有提交 Apple 公证；如果系统阻止首次打开，请前往“系统设置 → 隐私与安全性”，点击“仍要打开”。

### iPhone/iPad 皮皮虾快捷指令

不依赖电脑或 ClearClip 桌面端，只支持皮皮虾公开普通视频：

- [直接安装已签名快捷指令](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-Pipixia-Shortcut.shortcut)
- [下载快捷指令朋友版 ZIP（含中文说明）](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-Pipixia-Shortcut-Friends.zip)
- [下载快捷指令 SHA-256](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-Pipixia-Shortcut.shortcut.sha256)
- [下载朋友版 ZIP SHA-256](https://github.com/zhangwenlv/ClearClip-Downloads/releases/latest/download/ClearClip-Pipixia-Shortcut-Friends.zip.sha256)

在 iPhone 上打开 `.shortcut` 文件，跳转到“快捷指令”后点击“添加快捷指令”。可以从皮皮虾的分享菜单运行，也可以复制皮皮虾链接后单独运行；首次使用时需要允许网络访问和写入“照片”。快捷指令不支持抖音。

### Windows 10/11 x64

Windows 源码、浏览器适配和打包脚本已完成，并通过 x64 交叉编译及 Release 链接检查。正式 NSIS/MSI 安装包仍需在 Windows 10/11 x64 真机完成抖音、皮皮虾、下载和文件夹定位验证后上传，因此当前 Release 不提供未实测的 Windows 文件。

## 功能

- 支持粘贴皮皮虾、抖音分享链接或整段抖音分享文案
- 获取标题、作者、封面、时长和分辨率
- 优先选择平台公开返回的最高画质无水印播放流
- 通过系统保存窗口下载 MP4，并可在文件夹中定位成品
- 解析与下载均在本机完成，不上传视频到第三方解析服务
- 抖音解析使用独立临时浏览器目录，不读取个人 Cookie 或浏览器配置
- iPhone/iPad 快捷指令可从皮皮虾分享菜单直接解析并保存到“照片”

## 使用范围

仅用于下载你有权保存和使用的公开内容。ClearClip 不绕过登录、付费权限、DRM 或网站访问控制。已删除、私密、仅登录可见、图集、直播及平台未公开返回播放流的内容可能无法解析。

项目源码维护在私有仓库。GitHub Release 页面自动显示的 “Source code” 文件只是本下载页仓库的快照，不是 ClearClip 安装包，请使用上面的直接下载链接。
