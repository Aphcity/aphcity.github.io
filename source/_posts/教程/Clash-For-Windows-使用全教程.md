---
title: Clash For Windows 使用全教程
katex: false
cover: >-
  https://cdn.statically.io/gh/Aphcity/aphcity-assets@master/20230621/Clash-Cover.71yhx8jsqmw0.webp
tags:
  - Clash
  - 机场
updated: '2023/06/21 23:46:34'
categories:
  - 教程
abbrlink: 9493c649
date: 2023-06-21 22:49:07
---

> 心血来潮，因为好像最近的家人们有很多想要自己独立科学上网的，为了玩的，为了学的，为了看的，有点多，统一省事，也给博客加点养分，整理一下，也能有人再来问，能当甩手掌柜，以后直接用😝

## 前言

🚩Clash：一个 Go 语言开发的多平台代理客户端。[GitHub](https://github.com/Dreamacro/clash)

🚩ClashX: Clash 的 Mac 图形客户端。[GitHub](https://github.com/yichengchen/clashX)

🚩Clash For Android: Clash 的 Android 图形客户端。[GitHub](https://github.com/Kr328/ClashForAndroid)

🚩Clash for Windows: Clash 的 Windows/macOS/Linux 图形客户端。[GitHub](https://github.com/Fndroid/clash_for_windows_pkg)

`Clash` 算是近两年来比较高性能的代理软件，其支持 `vmess`, `ss`, `ssr` 等协议，通过自己的 core 来实现的相关代理协议。

这篇文章是配合机场使用订阅的一个教程，很基础的一个使用教程。`Clash for Windows` 是代理工具 `Clash` 在 `Windows` 系统的唯一图形客户端，早期`Clash for Windows`只有 `Windows` 端，因此而得名。但目前早已支持 `Windows`、`macOS`、`Linux` 三大平台，功能强大且支持多种代理协议，如 `Shadowsocks(SS)`、`ShadowsocksR(SSR)`、`Socks`、`Snell`、`V2Ray`、`Trojan`、`https` 等代理协议。

### 下载和安装

#### 官网下载

**Clash for Windows** 官网下载地址：[GitHub Releases](https://github.com/Fndroid/clash_for_windows_pkg/releases)
新手使用建议下载稳定版本，即版本号后标记为 `Latest` 的版本。

![Clash-GitHub-Release](https://cdn.statically.io/gh/Aphcity/aphcity-assets@master/20230621/Clash-GitHub-Release.hyq7qmc1zg8.webp)

本文编辑时为上图所示，根据本身系统及CPU架构选择下载的文件，一般而言，对于 家用 的 64位 Windows 操作系统，选择 `Clash.for.Windows.Setup.**.**.**.exe` 下载即可

| 文件名                                       | 说明                         |
| -------------------------------------------- | ---------------------------- |
| Clash.for.Windows-0.20.27-arm64-linux.tar.gz | Linux ARM 64位 版本 压缩包   |
| Clash.for.Windows-0.20.27-arm64-mac.7z       | Mac ARM 64位 版本 压缩包     |
| Clash.for.Windows-0.20.27-arm64-win.7z       | Windows ARM 64位 版本 压缩包 |
| Clash.for.Windows-0.20.27-arm64.dmg          | Mac ARM 64位 版本 安装包     |
| Clash.for.Windows-0.20.27-ia32-win.7z        | Windows 32位 版本 压缩包     |
| Clash.for.Windows-0.20.27-mac.7z             | Mac 64位 版本 压缩包         |
| Clash.for.Windows-0.20.27-win.7z             | Windows 64位 版本 压缩包     |
| Clash.for.Windows-0.20.27-x64-linux.tar.gz   | Linux 64位 版本 压缩包       |
| Clash.for.Windows-0.20.27.dmg                | Mac 64位 版本 安装包         |
| Clash.for.Windows.Setup.0.20.27.arm64.exe    | Windows ARM 64位 版本 安装包 |
| Clash.for.Windows.Setup.0.20.27.exe          | Windows 64位 版本 安装包     |
| Clash.for.Windows.Setup.0.20.27.ia32.exe     | Windows 32位 版本 安装包     |
| sha256sum                                    | 检测文件完整性的命令         |
| Source code (zip)                            | 源文件压缩包 zip 版本        |
| Source code (tar.gz)                         | 源文件压缩包 tar.gz 版本     |

下载完成后，打开进行安装。

## 使用

![Clash-Profiles](https://cdn.statically.io/gh/Aphcity/aphcity-assets@master/20230621/Clash-Profiles.5ixsnkb2fn40.webp)

安装完成，首先跳转至 `Profiles` 选项卡下，点击 `Download` 左侧的文本框，或点击框内的粘贴图标，将先前准备好的 `订阅链接` 复制到文本框内，之后点击 `Download` 即可将 `订阅` 导入到 `Clash For Windows` 中。

![Clash-General](https://cdn.statically.io/gh/Aphcity/aphcity-assets@master/20230621/Clash-General.5cp3n114zz00.webp)

之后，打开主界面，应当与上图大体一致，并且建议将面板勾选至与上述一致。具体选项会在之后介绍。

