# MIUI 原生通知图标

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v2.95-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)
<br/><br/>
<img src="https://github.com/fankes/MIUINativeNotifyIcon/blob/master/app/src/main/ic_launcher-playstore.png" width = "100" height = "100"/>
<br/>
Fix the native notification bar icon function abandoned by the MIUI development team.

修复被 MIUI 开发组丢弃的原生通知图标，支持 MIUI 11、12、12.5、13、14 以及最新版本。

## 项目迁移公告

由于本人同时维护 **MIUI** 与 **ColorOS** 两个系统需要同时维护两个模块，十分不方便，所以我决定在后期逐渐合并两个项目并解耦合为一个新项目并计划适配更多系统与设备，例如原生与类原生系统。

在新的项目确定后，会在这里添加新项目的链接，届时我会终止维护这个项目并建议大家转移到新项目。

## 适配说明

- 请确保你使用的是 MIUI 官方版本，任何第三方官改包发生的问题，开发者没有义务去解决和修复，请自求多福

- 目前最低支持基于 Android 9 版本的 MIUI 11 或 MIUI 12、12.5 (最低建议)

- 建议最低从 MIUI 12.5 `2021-5-18` 开发版以后开始使用模块，之前的版本可能或多或少存在 MIUI 自身 BUG 不生效、图标黑白块的问题

- 请始终保持最新版本的 LSPosed，旧版本可能会出现 Hook 不生效的问题，若最新版本依然不生效请在作用域中长按“系统界面”(“系统 UI”)选择重新优化

Xposed-Modules-Repo 有一定时长的缓存，若最新版本无法下载请前往如下地址下载

[Release 发布地址](https://github.com/fankes/MIUINativeNotifyIcon/releases)

## 捐赠支持

- 工作不易，无意外情况此项目将继续维护下去，提供更多可能，欢迎打赏。<br/><br/>
  <img src="https://github.com/fankes/YuKiHookAPI/blob/master/img-src/wechat_code.jpg?raw=true" width = "200" height = "200"/>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2017-2023 Fankes Studio(qzmmcn@163.com)
