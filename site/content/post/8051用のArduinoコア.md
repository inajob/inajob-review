---
title: 8051用のArduinoコア
date: 2026-04-14T23:22:44.643192
description: ちょっと変わった実装方式の8051用のArduinoコアを紹介します
image: /img/8051用のArduinoコア.jpg
tags:
  - 8051
  - RISC-V
---
[Arduino Code? On My 8051? It’s More Likely Than You Think](https://hackaday.com/2026/03/22/arduino-code-on-my-8051-its-more-likely-than-you-think/)から発見。画像もここから転載。

8051用のためのArduinoコアの実装です。
といっても、8051用のコードを直接実装するのではなく、8051用のRISC-Vエミュレータを実装し、そのうえでRISC-V用のArduinoコアを実行しています。

当然実行速度は遅くなりますが、どうしても8051でArduino風の開発が行いたい場合には役立つかもしれません。



