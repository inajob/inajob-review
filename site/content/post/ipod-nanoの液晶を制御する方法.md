---
title: iPod Nanoの液晶を制御する方法
date: 2019-08-20T23:00:38.935Z
description: ESP32でiPad Nanoの液晶を制御する方法を紹介します。
image: /img/nano-display.jpg
tags:
  - ディスプレイ
---
[How to use the iPod Nano 6 LCD for LittlevGL](https://blog.littlevgl.com/2019-02-02/use-ipod-nano6-lcd-for-littlevgl)から発見。画像もここから転載。

中古の携帯電話の液晶などをマイコンで制御する、というのはよく見ますが、iPod Nanoの液晶を制御したという話はあまり聞いたことがありません。

どうやらこの液晶はMIPI DSIという高速なシリアル通信のプロトコルで制御する必要があるようです。専用の出力があるマイコンを使わない場合、この通信をbit-bangで実現することは難しいので、ブリッジICというのを使うことになります。

この記事で使っているのはSSD2805というチップです。これはRGB/8080信号をMIPI信号に変換するチップです。

とそれっぽく書きましたが私はRGB/8080信号もよくわからないですし、SSD2805のチップは0.5mmピッチのBGAということで、手を出すのは難しそうです・・

新しい部品は高機能だけど制御も難しいな、と感じました。
