---
title: VGAケーブルで接続された分割キーボード
date: 2022-12-08T23:19:49.740975
description: VGAケーブルで接続された分割キーボードの作例を紹介します
image: /img/VGAケーブルで接続された分割キーボード.jpg
tags:
  - 自作キーボード
  - VGA
---
[Colorful Split Keyboard Uses VGA Connections](https://hackaday.com/2022/11/19/colorful-split-keyboard-uses-vga-connections/)から発見。画像もここから転載。

分割型の自作キーボードが流行りです。
その多くは左右のキーボードをTRRSケーブルという、いわゆる4極のオーディオケーブルで接続しています。

この4極をVCC,GND,信号線2本として使うことで左右のキーが連携するというものです。（信号線はUARTやI2Cでやり取りすることが多いようです）

しかし、この方式だと分割キーボードの左右にマイコンが必要となります。

もっとたくさんの電極を持つケーブルを使えば、片方のキーボードのマトリクス配線をすべて反対側のキーボードに伝えることができ、マイコンボードは片方だけにあればよいことになるのに・・という流れで設計されたのが、このVGAケーブル接続の分割キーボードです。

VGAケーブルの一部の端子はGNDにショートしているらしく、すべてのピンを使うことが出来ない点は注意が必要です。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/nY5QrDrGWAw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

