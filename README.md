<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" width="800">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg" width="800">
  <img alt="pubglite55" src="assets/header-dark.svg" width="800">
</picture>

</div>

系统底层与逆向：Linux 内核 UAF 利用、Android 固件移植、TWS 蓝牙协议抓包，以及把 macOS 塞进一台 ROG 游戏本。

`C` · `ARM64 Assembly` · `Python` · Linux Kernel · XNU · UEFI (EDK II) · OpenCore / ACPI · Frida · IDA

---

## 现在在做

### iOS 16 on Xiaomi 13 Pro

<sub>nuwa / SM8550 / 12 GB · <a href="https://github.com/pubglite55/UniXNU-nuwa">UniXNU-nuwa</a> · 预链接 Apple 原厂 kext 的 XNU</sub>

引导链已全通：ABL → UEFI（Mu-Silicium）→ DarwinBoot → XNU。**AMFI / IOKit / BSD init 均已在真机通过，根文件系统两条路径都挂载成功**（`rd=md0` ramdisk 与 `rootdev=` UFS 卷）。当前在攻真实 iOS 根与 AMFI 根封印。

### GhostLock · CVE-2026-43499

<sub>Linux kernel · ARM64 · <a href="https://github.com/pubglite55/oppofindN2-ghostlock">oppofindN2-ghostlock</a></sub>

Linux 内核栈 UAF 从 x86_64 向 ARM64 移植适配，CFI bypass 攻坚中。

---

## 其他项目

- **[ROG-GU603ZM-Hackintosh](https://github.com/pubglite55/ROG-GU603ZM-Hackintosh)** — 华硕 ROG 幻16 的 OpenCore EFI：macOS Sequoia 15 + RTX 3060 Laptop
- **[motobuds-for-hyper](https://github.com/pubglite55/motobuds-for-hyper)** — 把 Moto Buds 接进 HyperOS 3：超级岛电量、融合设备中心、降噪切换
- **[SpaceTravel-Protocol](https://github.com/pubglite55/SpaceTravel-Protocol)** — 水月雨 Space Travel TWS 的 GAIA V3 / BLE GATT 协议完整分析
- **[nuwa-mainline](https://github.com/pubglite55/nuwa-mainline)** — 小米 13 Pro 的 Linux mainline 移植：kernel + Ubuntu GNOME rootfs，arm64 CI
- **[ta_companion](https://github.com/pubglite55/ta_companion)** — Flutter + Riverpod 的 AI 伴侣 App：记忆、心情、朋友圈

---

## 联系

GitHub [@pubglite55](https://github.com/pubglite55) · 昵称 xiuxiu391 · 3418516663@qq.com

欢迎开 Issue，或者直接 DM。
