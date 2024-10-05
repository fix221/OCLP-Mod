<div align="center">
             <img src="docs/images/OC-Patcher.png" alt="OpenCore Patcher Logo" width="256" />
             <h1>OCLP-Mod</h1>
  <a href="https://github.com/laobamac/OCLP-Mod/blob/main/README.md">English</a><a href="https://github.com/laobamac/OCLP-Mod/blob/main/README_CN.md">中文</a>
</div>
<br>

基于[Acidanthera的OpenCorePkg](https://github.com/acidanthera/OpenCorePkg) 和 [Lilu](https://github.com/acidanthera/Lilu) 的 Python 项目的修改版 [OCLP-Mod](https://github.com/laobamac/OCLP-Mod)，用于在支持和不支持的 Mac 上运行和解锁 macOS 的功能。

增加了中文语言、Sequoia 中的 Intel 无线网卡、KDK/MetalLib 文件加速下载&自由选择等。

----------

![GitHub 所有版本](https://img.shields.io/github/release/laobamac/OCLP-Mod) ![GitHub 顶部语言](https://img.shields.io/github/languages/top/laobamac/OCLP-Mod?color=4B8BBE&style=plastic) ![Github 许可证](https://img.shields.io/github/license/laobamac/OCLP-Mod)

----------

### OCLP-Mod 特点：

* 支持 macOS Big Sur、Monterey、Ventura、Sonoma 和 Sequoia
* 原生的 OTA 系统更新
* 支持 Penryn 和更新的 Mac
* 对于 BCM943224 和更新的无线芯片组，完全支持 WPA Wi-Fi 和个人热点
* 系统完整性保护、FileVault 2、.im4m 安全启动和保管
* 在非原生操作系统上启动恢复 OS、安全模式和单用户模式
* 即使在原生 Mac 上，也可以解锁 Sidecar 和 AirPlay 等功能
* 在非 Apple 存储设备上启用增强的 SATA 和 NVMe 电源管理
* 无需固件补丁（即 APFS ROM 补丁）
* 支持 Metal 和非 Metal GPU 的图形加速
* 提供 zh_CN 语言支持。
* 支持 Intel 无线网卡在Sequoia驱动补丁。
* 支持单独加速下载KDK、Metallib，Patch提示时也有加速！

## 支持

该项目按原样提供，我们不保证对可能出现的任何问题提供支持。然而在社区服务器，其他热情的用户和开发者可以帮助您：

* [SimpleHac论坛](https://www.simplehac.cn)

## 从源代码运行（仅适用于有修改倾向的用户）

要从源代码运行该项目，请查看： [从源代码构建和运行](./SOURCE.md)

## 致谢

* [Acidanthera](https://github.com/Acidanthera)
  * OpenCorePkg，以及许多核心 kext 和工具
* [Dortania](https://github.com/dortania) 和 OpenCore Legacy Patcher 贡献者
  * OpenCore-Legacy-Patcher
* Apple
  * 为 macOS 以及我们重新实现到较新操作系统中的许多 kext、框架和其他二进制文件
