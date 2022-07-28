---
title: ESP32でRISC-Vのエミュレータを動かしLinuxを動かす
date: 2022-07-28T22:20:01.473713
description: ESP32でRISC-Vのエミュレータを動かしLinuxを動かすテクニックを紹介します。
image: /img/ESP32でRISC-Vのエミュレータを動かしLinuxを動かす.jpg
tags:
  - ESP32
  - RISC-V
---
[It’s Linux. On An ESP32](https://hackaday.com/2022/07/14/its-linux-on-an-esp32/)から発見。画像もここから転載。

ESP32はパワフルなCPUですが、独自のインストラクションセットなので、既存の資源の活用が難しいなど問題もあります。

この記事で紹介しているのはESP32の上でRISC-Vのエミュレータを動作させLinuxを動かす手法です。
エミュレータとしてはTinyEMUを利用しています。

カーネルが起動するには1分35秒ほどかかるようです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/f3a3xeTRj_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

