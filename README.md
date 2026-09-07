# Device Keeper

**Download APK (v3.3.5):** [toolbox-3.3.5-google-release.apk](https://github.com/magicsoft/toolbox-android/raw/main/dist/toolbox-3.3.5-google-release.apk)

Sideload APK only. This repository does not host source code.

---

# Device Keeper 3.3.5

Android utility app with a built-in **Clash Meta VPN**. You can import Clash YAML, manage proxies and rules, and keep everyday phone tools in one place.

**Package:** `zzy.cpucooler.google`  
**File:** `toolbox-3.3.5-google-release.apk`  
**SHA256:** `fa1f10c1884d333de040a11d273444c7f5e2363781e997446ad8b9231024787f`  
**Checksum:** [dist/SHA256SUMS.txt](dist/SHA256SUMS.txt)

## VPN / Clash (main)

- Start / stop a system VPN based on **Clash Meta**
- Import **Clash YAML** (`.yaml` / `.yml`) from a local file
- Add a profile from a **subscription / config URL**
- Switch among multiple profiles
- Clash **proxies, groups, and rules** (domain, IP, process, and typical rule providers in the YAML)
- Edit and save Clash settings before activating a profile
- Optional **daily auto-update** of bundled Clash YAML / nodes
- One-tap refresh when you need a newer node list

Supported config style is standard Clash / Clash Meta YAML, for example:

```yaml
proxies:
  - { name: example, type: ss, server: ..., port: ..., cipher: ..., password: ... }
proxy-groups:
  - { name: PROXY, type: select, proxies: [example] }
rules:
  - DOMAIN-SUFFIX,google.com,PROXY
  - MATCH,DIRECT
```

Put your own `config.yaml` in the app via **Profiles → New / Import**. URL profiles are fetched and stored as Clash config files.

## Other tools

- Device info: CPU, battery, storage, network
- QR, PDF/image convert and compress
- Wallpapers, GIF, blur, watermark removal
- Browser utilities, IPTV helper, Morse, lucky wheel

## Requirements

- Android 6.0 or newer
- VPN permission when you turn Clash on
- Allow install from this browser / file manager

## Install

1. Download [toolbox-3.3.5-google-release.apk](https://github.com/magicsoft/toolbox-android/raw/main/dist/toolbox-3.3.5-google-release.apk)
2. Open the file and install
3. Optional: [Obtainium](https://github.com/ImranR98/Obtainium/releases) → add `https://github.com/magicsoft/toolbox-android`

This APK **cannot** overwrite the Play Store install (different signing key). Keep only one install channel.

---

# 设备管家 3.3.5

内置 **Clash Meta VPN**。支持导入 Clash YAML 配置、规则分流，并附带常用手机工具。

**包名：** `zzy.cpucooler.google`  
**文件：** `toolbox-3.3.5-google-release.apk`  
**SHA256：** `fa1f10c1884d333de040a11d273444c7f5e2363781e997446ad8b9231024787f`  
**校验：** [dist/SHA256SUMS.txt](dist/SHA256SUMS.txt)

## VPN / Clash（重点）

- 一键开启 / 关闭系统 VPN（Clash Meta 内核）
- 从本地导入 **Clash YAML**（`.yaml` / `.yml`）
- 用 **订阅地址 / 配置 URL** 添加配置
- 多配置文件切换
- 支持 YAML 里的 **节点、策略组、规则**（域名、IP、进程等常见 Clash 规则）
- 激活前可保存 Clash 配置
- 可选 **每天自动更新** 内置节点 YAML
- 需要时手动刷新节点列表

配置格式为标准 Clash / Clash.Meta YAML，例如：

```yaml
proxies:
  - { name: example, type: ss, server: ..., port: ..., cipher: ..., password: ... }
proxy-groups:
  - { name: PROXY, type: select, proxies: [example] }
rules:
  - DOMAIN-SUFFIX,google.com,PROXY
  - MATCH,DIRECT
```

在应用里打开 **配置 → 新建 / 导入**，选择本地 `config.yaml`，或填写订阅 / 配置 URL。

## 其他工具

- 设备信息：CPU、电池、存储、网络
- 二维码、PDF/图片转换与压缩
- 壁纸、GIF、模糊、去水印
- 浏览器工具、IPTV、摩尔斯电码、幸运转盘

## 系统要求

- Android 6.0 及以上
- 开启 VPN 时需要系统 VPN 授权
- 允许当前浏览器或文件管理器安装未知应用

## 安装

1. 下载 [toolbox-3.3.5-google-release.apk](https://github.com/magicsoft/toolbox-android/raw/main/dist/toolbox-3.3.5-google-release.apk)
2. 打开文件安装
3. 如需自动更新，用 [Obtainium](https://github.com/ImranR98/Obtainium/releases) 添加 `https://github.com/magicsoft/toolbox-android`

本 APK **不能**覆盖 Play 商店已安装版本（签名不同）。请只保留一种安装来源。
