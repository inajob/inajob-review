---
title: CH32V用のuf2ブートローダー
date: 2024-05-23T23:44:28.107903
description: CH32V用のuf2ブートローダー
image: /img/CH32V用のuf2ブートローダー.jpg
tags:
  - CH32V
  - uf2
---
[GitHub - ArcaneNibble/wch-uf2: CH32V UF2 bootloader](https://github.com/ArcaneNibble/wch-uf2)から発見。画像もここから転載。

デバイスをUSBでパソコンに繋げると、マスストレージとして認識され、そこにファームウェアのファイルをコピーすることで書き込みを実現するuf2という仕組みがあります。

有名なところだとRaspberry Pi Picoなどに採用されていますが、それ以外にも様々な開発ボードがこの仕組みに対応してます。
ここで紹介するのはCH32V用のuf2ブートローダーです。

uf2サポートがあれば専用の書き込み機や書き込みソフトウェアなしにファームウェアを書き換えられるので便利です。



