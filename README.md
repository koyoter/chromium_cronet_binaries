# chromium_cronet_binaries

[中文](#中文) | [English](#english)

---

## 中文

本仓库提供跨平台 Chromium Cronet 二进制文件，支持 Android、Windows、Linux、macOS 和 iOS 平台。所有平台使用同一稳定版本。

### 工作原理

- 根目录的 `CHROMIUM_STABLE_VERSIONS` 文件用于控制所有平台打包的版本号。
- 版本信息从 [https://chromiumdash.appspot.com/releases](https://chromiumdash.appspot.com/releases) 获取。
- 当提交更改时，GitHub Actions 会自动处理打包过程。

### 自定义版本

如果您需要特定版本：
1. Fork 本仓库
2. 修改 `CHROMIUM_STABLE_VERSIONS` 文件
3. 提交您的更改
4. GitHub Actions 将自动运行打包过程

### 支持的平台

- Android
- Windows
- Linux
- macOS
- iOS

---

## English

This repository provides cross-platform Chromium Cronet binaries for Android, Windows, Linux, macOS, and iOS. All platforms use the same stable version.

### How it works

- The `CHROMIUM_STABLE_VERSIONS` file in the root directory controls the version numbers for packaging all platforms.
- Version information is obtained from [https://chromiumdash.appspot.com/releases](https://chromiumdash.appspot.com/releases).
- GitHub Actions automatically handle the packaging process when changes are committed.

### Custom versions

If you need a specific version:
1. Fork this repository
2. Modify the `CHROMIUM_STABLE_VERSIONS` file
3. Commit your changes
4. GitHub Actions will automatically run the packaging process

### Supported Platforms

- Android
- Windows
- Linux
- macOS
- iOS