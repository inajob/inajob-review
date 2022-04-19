---
title: ESP32のULPのプログラムを簡単に作るためのライブラリ
date: 2022-04-19T23:13:30.69233
description: ESP32のULPのプログラムを簡単に作るためのライブラリを紹介します
image: /img/ESP32のULPのプログラムを簡単に作るためのライブラリ.jpg
tags:
  - ESP32
  - ULP
---
[boarchuz/HULP](https://github.com/boarchuz/HULP)から発見。画像もここから転載。

ESP32にはデュアルコアのCPUとして知られていますが、実はもう一つUltra Low Power Co-Processor (ULP)という、低消費電力のCPUが搭載されています。
ULPは独自の機械語となっており、高級言語からのコンパイラは存在しません。

ということで、基本的には仕様書を見つつアセンブラをせこせこ打ち込む必要があるのですが、このHULPを使うと、簡単なマクロを組み合わせる事でULPのプログラミングが出来ます。

