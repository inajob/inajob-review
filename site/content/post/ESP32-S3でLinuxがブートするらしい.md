---
title: ESP32-S3でLinuxがブートするらしい
date: 2023-07-06T23:59:06.507054
description: ESP32-S3でLinuxがブートするらしい
image: /img/ESP32-S3でLinuxがブートするらしい.jpg
tags:
  - ESP32
  - Linux
---
[Running Linux with kernel 6.3 on Open Source Hardware board with ESP32-S3!](https://olimex.wordpress.com/2023/06/27/running-linux-with-kernel-6-3-on-open-source-hardware-board-with-esp32-s3/)から発見。画像もここから転載。

ESP32-S3でLinuxがブートするらしい。
過去にした記事ではESP32上でRISC-Vなどのエミュレーションをするタイプのものでしたが、この記事では、直接ESP32のコンパイラを使ってLinuxをビルドしています。

ESP32-S3にMMUはついていないので、Buildrootを使ってMMUなしで構成しているように見えます。
ESP32-S3のような安価な組み込みチップでLinuxが動くと、色々と応用が利きそうです。



