---
title: RaspberryPi4にPCI Expressポートを増やす、さらに簡単な方法が編み出される
date: 2020-07-05T23:00:51.505Z
description: 以前紹介したRaspberryPi4にPCI Expressポートを増やす方法を、より簡単に実施する方法が編み出されました。
image: /img/rpi4_bridge_chip.jpg
tags:
  - RaspberryPi
  - Hack
---
[Raspberry Pi 4 PCI-Express Bridge “Chip”](https://blog.zakkemble.net/rpi4-pci-express-bridge-chip/)から発見。画像もここから転載。

以前紹介した[Raspberry Pi 4にPCI Expressのボードを接続する裏技
](https://inajob.github.io/iroiro-review/post/raspberry-pi-4%E3%81%ABpci-express%E3%81%AE%E3%83%9C%E3%83%BC%E3%83%89%E3%82%92%E6%8E%A5%E7%B6%9A%E3%81%99%E3%82%8B%E8%A3%8F%E6%8A%80/)を簡単に実施する方法が編み出されました。
PCI Expressバスに直結されているUSBハブのコントローラチップをはがして、PCI Expressの信号をそのままUSBポートに引き出すという改造ですが、以前はこれを細いワイヤーのはんだ付けで実施していましたが、今回紹介するのは、それ専用の「基板」を利用する方法です。

![](../../img/rpi4_bridge_chip2.jpg)

ICと同じ大きさのこの基板は、前述の信号のバイパスを行う配線となっています。

これを使うことで、USBハブのICをはがして、この基板を実装しなおすだけで、PCI Expressが利用できるというものです。
