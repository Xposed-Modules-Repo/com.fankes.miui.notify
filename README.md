# MIUI 原生通知图标

[![GitHub license](https://img.shields.io/github/license/fankes/MIUINativeNotifyIcon?color=blue)](https://github.com/fankes/MIUINativeNotifyIcon/blob/master/LICENSE)
[![GitHub CI](https://img.shields.io/github/actions/workflow/status/fankes/MIUINativeNotifyIcon/commit_ci.yml?label=CI%20builds)](https://github.com/fankes/MIUINativeNotifyIcon/actions/workflows/commit_ci.yml)
[![GitHub release](https://img.shields.io/github/v/release/fankes/MIUINativeNotifyIcon?display_name=release&logo=github&color=green)](https://github.com/fankes/MIUINativeNotifyIcon/releases)
![GitHub all releases](https://img.shields.io/github/downloads/fankes/MIUINativeNotifyIcon/total?label=downloads)
![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.fankes.miui.notify/total?label=LSPosed%20downloads&labelColor=F48FB1)

[![Telegram CI](https://img.shields.io/badge/CI%20builds-Telegram-blue.svg?logo=telegram)](https://t.me/MIUINativeNotifyIcon_CI)
[![Telegram](https://img.shields.io/badge/discussion-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)
[![QQ](https://img.shields.io/badge/discussion-QQ-blue.svg?logo=tencent-qq&logoColor=red)](https://qm.qq.com/cgi-bin/qm/qr?k=dp2h5YhWiga9WWb_Oh7kSHmx01X8I8ii&jump_from=webapi&authKey=Za5CaFP0lk7+Zgsk2KpoBD7sSaYbeXbsDgFjiWelOeH4VSionpxFJ7V0qQBSqvFM)
[![QQ 频道](https://img.shields.io/badge/discussion-QQ%20频道-blue.svg?logo=tencent-qq&logoColor=red)](https://pd.qq.com/s/44gcy28h)

<img src="https://github.com/fankes/MIUINativeNotifyIcon/blob/master/img-src/icon.png?raw=true" width = "100" height = "100" alt="LOGO"/>

Fix the native notification bar icon function abandoned by the MIUI development team.

修复被 MIUI 开发组丢弃的原生通知图标，支持 MIUI 11、12、12.5、13、14 以及最新版本。

## 项目迁移公告

由于本人同时维护 **MIUI** 与 **ColorOS** 两个系统需要同时维护两个模块，十分不方便，所以我决定在后期逐渐合并两个项目并解耦合为一个新项目并计划适配更多系统与设备，例如原生与类原生系统。

在新的项目确定后，会在这里添加新项目的链接，届时我会终止维护这个项目并建议大家转移到新项目。

## 适配说明

- 请确保你使用的是 MIUI 官方版本，任何第三方官改包发生的问题，开发者没有义务去解决和修复，请自求多福

- 目前最低支持基于 Android 9 版本的 MIUI 11 或 MIUI 12、12.5 (最低建议)

- 建议最低从 MIUI 12.5 `2021-5-18` 开发版以后开始使用模块，之前的版本可能或多或少存在 MIUI 自身 BUG 不生效、图标黑白块的问题

- 请始终保持最新版本的 LSPosed，旧版本可能会出现 Hook 不生效的问题，若最新版本依然不生效请在作用域中长按“系统界面” (“系统 UI”) 选择重新优化

## 发行渠道

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub CI](https://github.com/fankes/MIUINativeNotifyIcon/actions/workflows/commit_ci.yml) | CI 自动构建 (测试版) |
|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------|

| <img src="https://github.com/peter-iakovlev/Telegram/blob/public/Icon.png?raw=true" width = "30" height = "30" alt="LOGO"/> | [Telegram CI 频道](https://t.me/MIUINativeNotifyIcon_CI) | CI 自动构建 (测试版) |
|-----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|---------------|

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub Releases](https://github.com/fankes/MIUINativeNotifyIcon/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|-----------|

| <img src="https://avatars.githubusercontent.com/u/78217009?s=200&v=4?raw=true" width = "30" height = "30" alt="LOGO"/> | [Xposed-Modules-Repo](https://github.com/Xposed-Modules-Repo/com.fankes.miui.notify/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------|

| <img src="https://cdn-icons-png.flaticon.com/128/1163/1163624.png" width = "30" height = "30" alt="LOGO"/> | [蓝奏云 **(密码：62ll)**](https://fankes.lanzouy.com/b030o2e8h) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|-----------|

| <img src="https://static.coolapk.com/static/web/v8/images/header-logo.png" width = "30" height = "30" alt="LOGO"/> | [酷安应用市场](https://www.coolapk.com/apk/com.fankes.miui.notify) | 正式版 (稳定版) |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|-----------|

本模块发布地址仅限于上述所列出的地址，从其他非正规渠道下载到的版本或对您造成任何影响均与我们无关。

## 项目推广

如果你正在寻找一个可以自动管理 Gradle 项目依赖的 Gradle 插件，你可以了解一下 [SweetDependency](https://github.com/HighCapable/SweetDependency) 项目。

如果你正在寻找一个可以自动生成属性键值的 Gradle 插件，你可以了解一下 [SweetProperty](https://github.com/HighCapable/SweetProperty) 项目。

本项目同样使用了 **SweetDependency** 和 **SweetProperty**。

## 捐赠支持

工作不易，无意外情况此项目将继续维护下去，提供更多可能，欢迎打赏。

<img src="https://github.com/fankes/fankes/blob/main/img-src/payment_code.jpg?raw=true" width = "500" alt="Payment Code"/>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/HighCapable/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2017-2023 Fankes Studio(qzmmcn@163.com)
