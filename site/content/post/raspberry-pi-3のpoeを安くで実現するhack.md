---
title: Raspberry Pi 3のPoEを安くで実現するHACK
date: 2019-10-15T02:11:03.050Z
description: Raspberry Pi 3でPoEを安くで実現する方法を紹介します。
image: /img/poor-poe.jpg
tags:
  - RaspberryPi
---
[Poor man's PoE for Raspberry pi-3/4 under ~$2](http://albert-david.blogspot.com/2019/09/poor-mans-poe-for-raspberry-pi-3-under-2.html)から発見。画像もここから転載。

最近のRaspberry piはLANケーブルから電源を供給するPoEをサポートしています。
しかし、通常PoEを利用するためには、専用のボード（PoE Hat）を取り付ける必要があります。

この記事では、もっと簡単にPoEを実現する方法を紹介しています。

単純にPoEで供給される電力をDC-DCコンバータで5Vに降圧して、RaspberryPiの電源に接続しています。

PoE Hatを見ると回路はもっと複雑なものとなっていることから、ここで紹介している方法はPoE Hatのものとは違うアプローチのようなので、利用する際にはPoEについて詳しく学んだうえで実施するのがよさそうです。

