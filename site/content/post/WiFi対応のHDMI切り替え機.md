---
title: WiFi対応のHDMI切り替え機
date: 2026-01-25T22:13:31.927572
description: WiFi対応のHDMI切り替え機の作例を紹介します
image: /img/WiFi対応のHDMI切り替え機.jpg
tags:
  - TS3DV642
  - HDMI
  - ESP32-C3
  - ESP32
---
[IoT HDMI Switch 1×2 by Guim Store on Tindie](https://www.tindie.com/products/guimpt/iot-hdmi-switch-12/)から発見。画像もここから転載。

複数のモニタに1つのHDMIを出力する機器をつなげる際に利用できる、HDMI切り替え機の作例です。
ESP32-C3をコアとしており、WiFi経由できりかえができるようです（このパッケージは技適未取得と思われるので、日本で利用する際には工夫が必要そうです）

信号の切り替えには マルチプレクサ TS3DV642を使用しています。

この手の仕組みはいろいろな製品がありますが、WiFi対応しているものはあまりなさそうなので、欲しい人もいるのではないでしょうか？




