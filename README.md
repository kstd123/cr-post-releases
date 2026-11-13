# CR Post Desktop

macOS 安装包和客户端更新专用仓库；应用源码不在此仓库。

## 下载与安装

在 [Releases](https://github.com/kstd123/cr-post-releases/releases/latest) 下载适合电脑架构的 ZIP，解压后将 **CR Post.app** 拖到 **Applications**。

- `arm64` 适用于 Apple Silicon / M 系列 Mac。
- 本应用未签名公证。首次启动若被 macOS 拦截，请在“系统设置 → 隐私与安全性”允许打开。
- 使用需联网及公司 Okta 登录。

## 检查更新

1.1.2 起可在客户端点击“检查更新”，发现新版本后点击“更新”完成下载、校验和重启。无需 GitHub 账号。应用用户数据和图片篮保留。

1.1.1 及更早版本需要先手动安装一次 1.1.2。遇到 GitHub 网络错误或限流，可稍后重试；当前应用不会因此被替换。

发布只包含 ZIP 和 SHA-256 校验文件。每个稳定版使用 `desktop-vX.Y.Z` 标签，包名为 `CR-Post-X.Y.Z-mac-arm64.zip`。客户端使用 GitHub 的大小与 SHA-256 元数据验证下载完整性。
