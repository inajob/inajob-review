---
title: 600行のC言語で書かれたRISC-Vエミュレータ
date: 2023-06-30T00:02:42.597928
description: 600行のC言語で書かれたRISC-Vエミュレータを紹介します。
image: /img/600行のC言語で書かれたRISC-Vエミュレータ.jpg
tags:
  - RISC-V
  - エミュレータ
---
[A 32-BIT RISC-V CPU CORE IN 600 LINES OF C](https://hackaday.com/2023/06/24/a-32-bit-risc-v-cpu-core-in-600-lines-of-c/)から発見。画像もここから転載。

600行のC言語で書かれたRISC-Vエミュレータです。
RV32IMCの実装のようです。

速度に心配はありますが、RISC-Vとは違うアーキテクチャのCPUでRISC-Vの資産を利用したいときに活躍しそうです。

こういったエミュレータの活用例として、これとは別のRISC-Vエミュレータですが、[Raspberry Pi PicoでLinuxを動かす作例を以前紹介しました。](../post/raspberry-pi-picoでrisc-vをエミュレーションしてlinuxを動かす/)
このLinuxを動かす作例ではRV32imaのエミュレーションを行っています。




