---
title: 3ポートでLED4つスイッチ4つを扱う回路 "Tucoplexing" の紹介
date: 2019-10-08T23:00:41.525Z
description: 3ポートでLED4つスイッチ4つを扱う回路である "Tucoplexing" を紹介します。
image: /img/tucoplexing.png
tags:
  - 回路
---
[TUCOPLEXING: A NEW CHARLIPLEX FOR BUTTONS AND SWITCHES](https://hackaday.com/2019/03/23/tucoplexing-a-new-charliplex-for-buttons-and-switches/)から発見。画像もここから転載。

少ないGPIOで多くの入出力を扱うというのはMakerの性です。有名なものとしてCharlieplexingがあります。

この記事で紹介している”Tucoplexing”は3つのGPIOで4つのLEDと4つのスイッチの入力を制御しています。

LED部分はCharlieplexingで見たことがある構成です。スイッチの入力に関しては、コンデンサを間に入れることで、2つのスイッチによる電圧の立ち上がりの時間差を利用して1ポートで複数のスイッチの入力を実現しています。

Charlieplexingは出力のみでしたが、この"Tucoplexing"は入力も扱える点が優れているように感じます。
