# 本机内核快照 — houji (CrazyRabbitTt 设备)

由 OpenCode 在设备本机只读提取，供适配分析使用。未修改任何系统分区/配置。

- 设备代号: houji
- 系统: OS3.0.307.0.WNCCNXM (ColorOS / Android 14)
- 真实内核版本(/proc/version): 6.1.138-android14-11-g0c3d559bcd85-ab14529422
- 注意: uname -r 显示 g5929004f86ffc 为 SUSFS SPOOF_UNAME 伪造值，不可作为分析依据
- 内核配置中存在 CONFIG_KSU=y、CONFIG_KSU_SUSFS=y 等，无 CONFIG_NTSYNC

文件说明:
- proc_version.txt : /proc/version 原文
- defconfig        : /proc/config.gz 解压后的内核配置
- cmdline.txt      : /proc/cmdline 原文
