# MIUI 原生通知图标

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.95-green)
<br/><br/>
<img src="https://github.com/fankes/MIUINativeNotifyIcon/blob/master/app/src/main/ic_launcher-playstore.png" width = "100" height = "100"/>
<br/>
Fix the native notification bar icon function abandoned by the MIUI development team.<br/>
修复被 MIUI 开发组丢弃的原生通知图标，支持 MIUI 12、12.5、13 以及最新版本。
<br/><br/>
⚠️ 适配说明<br/>

- 目前最低支持基于 Android 9 版本的 MIUI 12 或 MIUI 12.5(最低建议)
- 请确保你使用的是 MIUI 官方版本，任何第三方官改包发生的问题，开发者没有义务去解决和修复，请自求多福
- 建议最低从 MIUI 12.5 `2021-5-18` 开发版以后开始使用模块，之前的版本可能或多或少存在 MIUI 自身 BUG 不生效、黑白块的问题
- 请始终保持最新版本的 LSPosed，旧版本可能会出现 Hook 不生效的问题

Xposed-Modules-Repo 有一定时长的缓存，若最新版本无法下载请前往如下地址下载<br/>
[Release 发布地址](https://github.com/fankes/MIUINativeNotifyIcon/releases)

# 历史背景

这个模块诞生来源于 MIUI 的乱改和不规范，本来 MIUI 9 之后，官方给出了原生通知图标样式，后面由于用户反应通知栏经常出现黑白块。<br/><br/>
这当然不是系统的错，而是国内 APP 和 `MIPUSH` 的通知极其不规范的通知图标设计。<br/><br/>
但是呢，接到反馈后 MIUI 开发组选择直接忽略这个问题，在 `2021-5-18` 的开发版开始，把全部通知图标都改成了 APP 的彩色图标，使得之前拥有自有样式的原生图标也被破坏。<br/><br/>
对于 Android 开发者来说，官方文档中的 `setSmallIcon` 不再适用于魔改后的 MIUI，这将会严重破坏非常多的状态图标。<br/><br/>
当然，国内的手机生态除了 `MIPUSH` 的营销通知就是社交软件的通知，可能大部分人都不会在意这件事情。<br/><br/>
但是，这个模块就是为了修复被 MIUI 开发组忽略的图标问题才诞生的，并完美地给 MIUI 修复了黑白块图标的问题。
