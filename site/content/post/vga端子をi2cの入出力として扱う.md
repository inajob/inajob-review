---
title: VGA端子をI2Cの入出力として扱う
date: 2020-01-03T09:40:21.453Z
description: LinuxマシンでVGA端子をI2Cバスとして使用する方法を紹介します。
image: /img/vga-as-i2c.png
tags:
  - HACK
---
[i2c on your unused/legacy VGA output](http://vogelchr.blogspot.com/2019/01/i2c-on-your-unusedlegacy-vga-output.html)から発見。画像もここから転載。

ディスプレイを接続するためのVGA端子ですが、そのピンの中にI2Cの機能のピンがあることを知っていますか？

本来はモニタのサポートしている解像度などをPCとやり取りするために使われるもののようですが、この記事ではLinuxで、このI2Cを厚克方法を紹介しています。

カーネルモジュールをロードするだけで、使えるようになり、記事の中では気温・湿度センサーの値をこのVGA端子から読み取っている様子が紹介されています。
