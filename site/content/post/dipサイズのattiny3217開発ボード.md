---
title: DIPサイズのATTINY3217開発ボード
date: 2021-10-11T12:00:05.886Z
description: 使いやすいサイズ・性能の開発ボードです。
image: /img/dily3217.jpg
tags:
  - attiny3217
  - 開発ボード
---
[Dily3217 mini ATtiny3217 development breakout board in DIL24](https://www.avdweb.nl/arduino/attiny3217/dily3217)から発見。画像もここから転載。

ATtiny3217というICを使った開発ボードです。聞きなれない型番ですが、Arduino UNOなどに使われているATmega328Pとほぼ同じ性能です。32KのROMに2KのRAM、GPIOが21個、さらにATmega328には無かった8bit DACの機能も搭載されています。

開発ボードの真ん中に一列にふらふらとピンが並んでいますが、このフラフラした並びがポイントで、これによりピンヘッダをはんだ付けせずに固定することが出来るようです。簡易的に書き込み装置をつなげる場合に便利に利用できます。

水晶発振子は搭載されていないので、クロックの精度が悪いので注意が必要です。
