---
title: TFT液晶コントローラの余ったメモリをRAMとして利用するテクニック
date: 2022-08-18T21:00:00.000Z
description: TFT液晶コントローラの余ったメモリを外付けのRAMとして利用するテクニックを紹介します。
image: /img/tft-spare-ram.jpg
tags:
  - HACK
  - 液晶
---
[Breadboard games 2020](https://ioprog.com/2020/05/19/breadboard-games-2020/)から発見。画像もここから転載。

マイコンのRAMは限られているため、場合によっては外付けのRAMを取り付けることも珍しくありません。

この記事で紹介しているのは、TFT液晶のコントローラのメモリの利用していない領域を汎用メモリとして利用するというテクニックです。
特に8色モードとしている場合は、各ピクセルごとに15ビットメモリが余るので、かなりの容量が確保できるようです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/XIE2ECZmJnc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
