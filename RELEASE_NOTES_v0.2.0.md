# ClearClip 0.2.0

首个按 macOS/Windows 共享架构整理的朋友分享版本。

## 本次提供

- `ClearClip-0.2.0-macOS-Universal-friends.zip`
- 对应 SHA-256 校验文件

macOS 包同时支持 Apple Silicon 与 Intel，包含 ClearClip.app、安装脚本和中文使用说明。

## 验证结果

- macOS `arm64` 与 `x86_64` 双架构检查通过
- 应用临时签名和严格签名校验通过
- 皮皮虾公开链接真实解析通过
- 抖音公开链接真实解析通过，并取得 2160×3840、60fps 的 HEVC/ByteVC1 无水印流
- 前端生产构建和 Rust 测试通过
- Windows x64 交叉编译与 Release 链接构建通过

Windows NSIS/MSI 安装包将在 Windows 10/11 x64 真机完成端到端验证后补充，不发布未实测的交叉编译文件。

仅用于下载你有权保存和使用的公开内容；不绕过登录、付费权限、DRM 或网站访问控制。
