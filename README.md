# HyperOS/MIUI Stock Notification Icon / HyperOS/MIUI 原生通知图标

[![GitHub license](https://img.shields.io/github/license/fankes/MIUINativeNotifyIcon?color=blue&style=flat-square)](https://github.com/fankes/MIUINativeNotifyIcon/blob/master/LICENSE)
[![GitHub CI](https://img.shields.io/github/actions/workflow/status/fankes/MIUINativeNotifyIcon/commit_ci.yml?label=CI%20builds&style=flat-square)](https://github.com/fankes/MIUINativeNotifyIcon/actions/workflows/commit_ci.yml)
[![GitHub release](https://img.shields.io/github/v/release/fankes/MIUINativeNotifyIcon?display_name=release&logo=github&color=green&style=flat-square)](https://github.com/fankes/MIUINativeNotifyIcon/releases)
![GitHub all releases](https://img.shields.io/github/downloads/fankes/MIUINativeNotifyIcon/total?label=downloads&style=flat-square)
![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.fankes.miui.notify/total?label=LSPosed%20downloads&labelColor=F48FB1&style=flat-square)

[![Telegram CI](https://img.shields.io/badge/CI%20builds-Telegram-blue.svg?logo=telegram&style=flat-square)](https://t.me/MIUINativeNotifyIcon_CI)
[![Telegram Channel](https://img.shields.io/badge/channel-Telegram-blue.svg?logo=telegram&style=flat-square)](https://t.me/XiaofangDaily)
[![Telegram](https://img.shields.io/badge/discussion-Telegram-blue.svg?logo=telegram&style=flat-square)](https://t.me/XiaofangInternet)
[![QQ](https://img.shields.io/badge/discussion-QQ-blue.svg?logo=tencent-qq&logoColor=red&style=flat-square)](https://qm.qq.com/cgi-bin/qm/qr?k=dp2h5YhWiga9WWb_Oh7kSHmx01X8I8ii&jump_from=webapi&authKey=Za5CaFP0lk7+Zgsk2KpoBD7sSaYbeXbsDgFjiWelOeH4VSionpxFJ7V0qQBSqvFM)
[![QQ 频道](https://img.shields.io/badge/discussion-QQ%20频道-blue.svg?logo=tencent-qq&logoColor=red&style=flat-square)](https://pd.qq.com/s/44gcy28h)

<img src="https://github.com/fankes/MIUINativeNotifyIcon/blob/master/img-src/icon.png?raw=true" width = "100" height = "100" alt="LOGO"/>

简体中文用户请 [前往这里](#simplified-chinese) 以查看简体中文版自述文件内容。

---
## English

## Project Migration Notice

Maintaining two modules for both **HyperOS/MIUI** and **ColorOS** at the same time is very inconvenient, so I plan to gradually merge and decouple the
two
projects into a new one, with plans to support more systems and devices, such as AOSP and AOSP-like systems.

The new project is [Sumi](https://github.com/fankes/Sumi), which is currently in development. After the new project publishes its official
release, I will stop maintaining this project and recommend that everyone move to the new project.

## Compatibility Notes

- **LSPosed** (scope: "System UI") is recommended
- Please make sure you are using an official HyperOS/MIUI build. The developer has no obligation to solve or fix problems that occur on any
  third-party
  modified ROM
- The minimum supported version is MIUI 11 based on Android 9, or MIUI 12 / 12.5
- It is recommended to use the module from the MIUI 12.5 `2021-5-18` development build onwards. Earlier versions may have MIUI's own bugs that make it
  ineffective or show black and white block icons

## Release Channels

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub CI](https://github.com/fankes/MIUINativeNotifyIcon/actions/workflows/commit_ci.yml) | CI automatic builds (beta) |
|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|----------------------------|

| <img src="https://github.com/peter-iakovlev/Telegram/blob/public/Icon.png?raw=true" width = "30" height = "30" alt="LOGO"/> | [Telegram CI Channel](https://t.me/MIUINativeNotifyIcon_CI) | CI automatic builds (beta) |
|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|----------------------------|

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub Releases](https://github.com/fankes/MIUINativeNotifyIcon/releases) | Official releases (stable) |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------|

| <img src="https://avatars.githubusercontent.com/u/78217009?s=200&v=4?raw=true" width = "30" height = "30" alt="LOGO"/> | [Xposed-Modules-Repo](https://github.com/Xposed-Modules-Repo/com.fankes.miui.notify/releases) | Official releases (stable) |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------|

The release addresses of this module are limited to those listed above. We are not responsible for any impact caused by versions downloaded from other
unofficial channels.

### Choose a Module Version by Scenario

The installation packages of this project come in two tracks: **modern** and **legacy**.

- Versions marked **modern** are for Xposed frameworks that support the libxposed API, such as LSPosed
- Versions marked **legacy** are for Xposed frameworks that support the Xposed Framework API, such as old LSPosed (≤ 1.9.0), EdXposed, etc.

The **modern** version supports automatic hot reload on LSPosed 2.1.0+. After the first installation, later module updates take effect without
restarting System UI.

## Notes

1. This software is free and developed out of interest, for learning and communication only. If you obtained it from an unofficial channel by paying
   for it, you may have been defrauded, and you are welcome to report suspicious behavior to us.
2. This software is licensed under the **GNU Affero General Public License (AGPL 3.0)**. According to the license:
    1. Any derivative work must use the same AGPLv3 license
    2. The complete source code must be provided when distributing this software or its modified versions
    3. The original copyright notice and license information must be retained
    4. No additional restrictions may be imposed to limit others' free use of this software
3. We encourage free distribution and improvement under the terms of AGPLv3, but please respect the author's attribution and do not impersonate the
   original author

## More Projects

<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h2>Hey, please stay a moment! 👋</h2>
    <h3>If you find this project helpful, take a look at my other projects below!</h3>
    <h3>If these projects help you, consider giving me a follow or a star ⭐️!</h3>
    <h1><a href="https://github.com/fankes/fankes/blob/main/project-promote/README.md">→ Click here to see more of my projects ←</a></h1>
</div>

## Built with

This module is built with [YukiHook](https://github.com/HighCapable/YukiHook).

YukiHook is a modern hook API and Xposed module solution that makes developing Xposed modules easier and more reliable.

This module is powered by [KavaRef](https://github.com/HighCapable/KavaRef).

KavaRef is a modern Java reflection library implemented in Kotlin, designed to make your Xposed module development more stable and up-to-date.

Copyright © 2017 Fankes Studio(qzmmcn@163.com)

---
## Simplified Chinese

## 项目迁移公告

由于本人同时维护 **HyperOS/MIUI** 与 **ColorOS** 两个系统需要同时维护两个模块，十分不方便，所以我决定在后期逐渐合并两个项目并解耦合为一个新项目并计划适配更多系统与设备，例如原生与类原生系统。

在新的项目确定后，会在这里添加新项目的链接，届时我会终止维护这个项目并建议大家转移到新项目。

新项目已确定为 [Sumi](https://github.com/fankes/Sumi)，目前处于开发阶段，在新项目发布正式版本后，我会终止维护这个项目并建议大家转移到新项目。

## 适配说明

- 推荐使用 **LSPosed** (作用域 “系统界面”)
- 请确保你使用的是 HyperOS/MIUI 官方版本，任何第三方官改包发生的问题，开发者没有义务去解决和修复
- 目前最低支持基于 Android 9 版本的 MIUI 11 或 MIUI 12、12.5
- 建议最低从 MIUI 12.5 `2021-5-18` 开发版以后开始使用模块，之前的版本可能或多或少存在 MIUI 自身 BUG 不生效、图标黑白块的问题

## 发行渠道

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub CI](https://github.com/fankes/MIUINativeNotifyIcon/actions/workflows/commit_ci.yml) | CI 自动构建 (测试版) |
|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------|

| <img src="https://github.com/peter-iakovlev/Telegram/blob/public/Icon.png?raw=true" width = "30" height = "30" alt="LOGO"/> | [Telegram CI 频道](https://t.me/MIUINativeNotifyIcon_CI) | CI 自动构建 (测试版) |
|-----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|---------------|

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub Releases](https://github.com/fankes/MIUINativeNotifyIcon/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|-----------|

| <img src="https://avatars.githubusercontent.com/u/78217009?s=200&v=4?raw=true" width = "30" height = "30" alt="LOGO"/> | [Xposed-Modules-Repo](https://github.com/Xposed-Modules-Repo/com.fankes.miui.notify/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------|

| <img src="https://cdn.nlark.com/yuque/0/2023/png/39215739/1697095421529-avatar/0305d093-2687-4529-834f-505f11f1ac50.png" width = "30" height = "30" alt="LOGO"/> | [123 云盘](https://1857720810.share.123pan.cn/123pan/zdcUvd-Hy65d?pwd=mnnc) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|-----------|

本模块发布地址仅限于上述所列出的地址，从其他非正规渠道下载到的版本或对您造成任何影响均与我们无关。

### 按场景选择模块版本

此项目的模块安装包采用双轨制，分为 **modern** 和 **legacy** 两个版本。

- 标有 **modern** 的版本适配支持 libxposed API 的 Xposed 框架，例如 LSPosed
- 标有 **legacy** 的版本适配支持 Xposed Framework API 的 Xposed 框架，例如旧版 LSPosed (≤ 1.9.0)、EdXposed 等

**modern** 版本的模块在 LSPosed 2.1.0+ 支持自动热重载功能，在首次安装后，接下来的版本中继续更新模块，不再需要重启系统界面即可生效。

## 注意事项

1. 本软件免费、由兴趣驱动开发，仅供学习交流使用。如果你是从其他非官方渠道付费获得本软件，可能已遭遇欺诈，欢迎向我们举报可疑行为。
2. 本软件采用 **GNU Affero General Public License (AGPL 3.0)** 许可证。根据该许可证的要求：
    1. 任何衍生作品必须采用相同的 AGPLv3 许可证
    2. 分发本软件或其修改版本时，必须提供完整的源代码
    3. 必须保留原始的版权声明及许可证信息
    4. 不得额外施加限制来限制他人对本软件的自由使用
3. 我们鼓励在遵守 AGPLv3 条款的前提下进行自由传播和改进，但请尊重作者署名权，勿冒用原作者名义

## 更多项目

<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h2>嘿，还请君留步！👋</h2>
    <h3>如果你觉得这个项目能给你提供帮助，不妨继续往下看看我的更多项目吧！</h3>
    <h3>如果这些项目能为你提供帮助，不妨为我点个关注或者 star ⭐️ 吧！</h3>
    <h1><a href="https://github.com/fankes/fankes/blob/main/project-promote/README-zh-CN.md">→ 查看更多关于我的项目，请点击这里 ←</a></h1>
</div>

## 基于以下项目构建

本模块使用 [YukiHook](https://github.com/HighCapable/YukiHook) 构建。

YukiHook 是一个现代化的 Hook API 与 Xposed 模块解决方案，让你的 Xposed 模块开发变得更轻松可靠。

本模块使用 [KavaRef](https://github.com/HighCapable/KavaRef) 强力驱动。

KavaRef 是一个使用 Kotlin 实现的现代化 Java 反射，让你的 Xposed 模块开发变得更稳定和现代化。

版权所有 © 2017 Fankes Studio(qzmmcn@163.com)
