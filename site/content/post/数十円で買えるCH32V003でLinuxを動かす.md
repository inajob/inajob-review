---
title: 数十円で買えるCH32V003でLinuxを動かす
date: 2024-04-01T23:31:01.940541
description: 数十円で買えるCH32V003でLinuxを動かす
image: /img/数十円で買えるCH32V003でLinuxを動かす.jpg
tags:
  - CH32V003
  - HACK
---
[Bring Linux To CH32V003 Through, Yes, RISC-V Emulation](https://hackaday.com/2024/03/03/bring-linux-to-ch32v003-through-yes-risc-v-emulation/)から発見。画像もここから転載。

数十円で買えるCH32V003でLinuxを動かすという事例です。
CH32V003で直接動かすのではなく、RISC-VのエミュレータをCH32V003上で動かし、その腕Linuxを実行するという仕組みのようです。

CH32V003はRISC-VのICではありますが、RAMが小さすぎるため、エミュレータを使い外部RAMを利用するというアイデアのようです。

なお起動には5分くらいかかるらしい


