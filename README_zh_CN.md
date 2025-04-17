# Fedora Rawhide On Orange Pi Zero3
![Fedora](https://img.shields.io/badge/Fedora-2a4476?style=for-the-badge&logo=fedora&logoColor=white) <img width="28px" src="orangepi.svg"></img>

[ [English](README.md#fedora-rawhide-on-orange-pi-zero3?lang=en) | [中文说明](#) ]

为香橙派zero3制作的Fedora Linux，基于Fedora Spins镜像

## 快速开始

1. 下载 **fedora_rawhide_minimal_orangepi_zero3.7z** 以及 uboot文件（1.5G内存的设备，跳到第2步，直接写入镜像）
   + 解压缩镜像文件后, 使用 [ImagePatcher3](https://github.com/lalakii/fedora_rawhide_minimal_orangepizero3/blob/master/ImagePatcher3.exe) 修补镜像的uboot
   + 如果是4GB的设备，可能还需要替换某些文件，具体参考u-boot下载页面的教程
2. 使用 [Fedora Media Writer](https://fedoraproject.org/workstation/download/) 将镜像文件 *fedora.raw* 写入到SD卡，[参考视频](https://www.bilibili.com/video/BV1Zb4y137j3/) 

## 文档

[Fedora Linux Rawhide](https://docs.fedoraproject.org/en-US/releases/rawhide/)

## 下载

+ fedora_rawhide_minimal_orangepi_zero3.7z:
  
  + 从这些云盘中获取镜像以及部分工具
      + [123云盘](https://www.123912.com/s/jE3Sjv-Ctmxd)
      + [123云盘备份](https://www.123865.com/s/jE3Sjv-Ctmxd)
      + [蓝奏云01](https://a01.lanzout.com/b00xram0d)
      + [蓝奏云02](https://a01.lanzoui.com/b00xram0d), Password: 8aih
        
  + ssid: opi-zero3
  + ssh: root@192.168.10.254, 无密码
+ orangepizero3_uboot: [Github](https://github.com/leeboby/opizero3-uboot-dtb/)

## 预览

![fedora_rawhide_minimal_orangepizero3_preview](https://raw.githubusercontent.com/lalakii/fedora_rawhide_minimal_orangepizero3/master/fedora_40_minimal_orangepizero3.png)

## 许可证

[License of Fedora Linux](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/)
