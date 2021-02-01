---
title: ATmega4809をブレッドボードで動かしてみた
date: 2021-02-01T12:38:04.794Z
description: ATmega4809をブレッドボードで動かす方法を紹介します。
image: /img/atmega4809mcp2221.jpg
tags:
  - ATmega4809
  - ブレッドボード
---
[Minimal ATmega4809 on a Breadboard](http://www.technoblogy.com/show?2QVZ)から発見。画像もここから転載。

新しいAVRのシリーズである ATmega4809をブレッドボードで試すための回路の紹介をしている記事です。

実はこのATmega4809はDIP版が存在しており、ブレッドボードで試すにはこれが一番簡単です。

ATmega4809の書き込みはUDPIというプロトコルで行う必要がありますが、jtag2updiというソフトウェアを使うことで一般的なUSB-Serial変換ICを使うことで書き込みすることが出来ます。
