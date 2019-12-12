---
title: 小型の携帯ゲーム機Spark
date: 2019-11-11T10:18:53.509Z
description: 小型のOLEDを搭載した携帯ゲーム機「Spark」を紹介します。
image: /img/spark-game.png
tags:
  - ゲーム機
  - atmega32u4
---
[Spark Handheld Video Game Kit](https://hackaday.io/project/168134-spark-handheld-video-game-kit)から発見。画像もここから転載。

Sparkは手のひらサイズのポータブルゲーム機です。コアとなるCPUはAtmega32u4で、128x64のモノクロOLED、スピーカーを搭載しています。

バッテリーはCR2032です。スペックはArduboyとほぼArduboyと同じなので、Arduboy用のゲームであれば簡単動かすことができそうです。（ディスプレイがI2C接続なのでArduboyとは違います。）

回路図も公開されているので、似たようなものが作りたい人は要チェックです。

OLEDのフレキケーブルをそのまま基板にはんだ付けするスタイルのゲーム基板は作るのは大変そうですが、コンパクトな筐体を実現することができます。
