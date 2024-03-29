---
title: CH32V003でソフトウェアでUSBデバイスを実現するライブラリ
date: 2023-11-13T23:11:02.341718
description: CH32V003でソフトウェアでUSBデバイスを実現するライブラリを紹介します
image: /img/CH32V003でソフトウェアでUSBデバイスを実現するライブラリ.jpg
tags:
  - CH32V003
  - USB
---
[GitHub - cnlohr/rv003usb: CH32V003 RISC-V Pure Software USB Controller](https://github.com/cnlohr/rv003usb)から発見。画像もここから転載。

CH32V003といえば、言わずとしれた安価なRISC-Vマイコンです。
このマイコン、$1未満で、SRAM2K、Flash16Kとスペックもそこそこですが、USB機能を持たないのが玉に傷です。

ということでソフトウェア実装でUSBデバイスを実現するライブラリを作った人がいるようです。
このライブラリを利用することでゲームパッドやマウス、キーボードといったデバイスや、CH32V003自身への書き込み機能などを実現することが出来るようです。

まぁひとつ上グレードのCH32V203などを使えばハードウェアのUSBドライバが利用できるので、懐に余裕がある方はそちらを使うのが良さそうです。


