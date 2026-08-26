# Quark Saver — Release Artifacts

本仓库仅用于存放 **Quark Saver**（夸克网盘转存助手）的公开发布产物（GitHub Release 镜像），
由主仓库 `Xwudao/quark-saver`（私有源码仓）的 GitHub Actions 自动发布。

> ⚠️ 请不要在本仓库提交代码。每次发版会由主仓库的 `release.yml` 自动创建对应的 Release。

## 产物说明

| 包类型 | 文件 | 说明 |
|--------|------|------|
| 🚀 便携版（免安装） | `quark-saver_*_portable.zip` | 解压后双击 `quark-saver.exe` 即可运行，内含 WebView2 引导程序 |
| 📦 独立 exe | `quark-saver.exe` | 可直接运行的可执行文件 |
| 📦 MSI 安装包 | `quark-saver_*.msi` | Windows 安装包 |
| 📦 NSIS 安装包 | `quark-saver_*_setup.exe` | Windows 安装程序 |

## 版本命名

每个 Release 对应一个版本 tag（如 `v0.1.0`），产物文件名会带上该版本号。

## 其他下载渠道

- 便携版同时镜像到 Cloudflare R2（路径 `/quark-saver/<随机前缀>/<版本>/`），链接会打印在主仓库对应 Release 的描述中。

## 使用说明

使用说明请前往文档站：[Quark Saver 文档](https://hunhepan-docs.pages.dev/quark-saver/)
