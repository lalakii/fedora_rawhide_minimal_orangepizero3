# Fedora Rawhide On Orange Pi Zero3 
![Fedora](https://img.shields.io/badge/Fedora-2a4476?style=for-the-badge&logo=fedora&logoColor=white) <img width="28px" src="orangepi.svg"></img>

[ [中文说明](README_zh_CN.md#fedora-rawhide-on-orange-pi-zero3?lang=zh_CN) | [English](#) ]

Fedora Linux for Spiced Orange Pi Zero3, based on the Fedora Spins image.

## Quick Start

1. Download **fedora_41_minimal_orangepi_zero3.7z** and uboot.
   + patch uboot using [ImagePatcher2](https://github.com/lalakii/fedora_rawhide_minimal_orangepizero3/blob/master/ImagePatcher2.exe). (If the memory is 1.5G you can ignore this step), see [YouTube](https://www.youtube.com/watch?v=YLmtxsbvnFM&ab_channel=lalakii)
   + If the memory is 4GB, you may also need to replace certain files, see the u-boot download page for details.
2. Burn *fedora-rawhide-opi.raw* to sdcard using [Fedora Media Writer](https://fedoraproject.org/workstation/download/).

## Docs

[Fedora Linux 40](https://docs.fedoraproject.org/en-US/releases/f40/)

## Download

+ fedora_41_minimal_orangepi_zero3.7z: [LanZouYun01](https://a01.lanzout.com/b00xram0d) or [LanZouYun02](https://a01.lanzoui.com/b00xram0d), Password: 8aih
    + ssid: opi-zero3
    + ssh: root@192.168.10.254, the root password is empty
+ orangepizero3_uboot: [Github](https://github.com/leeboby/opizero3-uboot-dtb/)

## Preview

![fedora_40_minimal_orangepizero3_preview](https://raw.githubusercontent.com/lalakii/fedora_rawhide_minimal_orangepizero3/master/fedora_40_minimal_orangepizero3.png)

## License

[License of Fedora Linux](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/)
