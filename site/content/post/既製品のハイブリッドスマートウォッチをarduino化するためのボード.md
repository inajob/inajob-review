---
title: 既製品のハイブリッドスマートウォッチをArduino化するためのボード
date: 2021-02-02T12:31:21.191Z
description: 既製品のハイブリッドスマートウォッチをHackしやすいArduinoベースに変更するための改造用ボードを紹介します。
image: /img/open-chronograph.png
tags:
  - HACK
  - Arduino
  - 時計
  - スマートウォッチ
---
[OPENCHRONOGRAPH LETS YOU ROLL YOUR OWN SMART WATCH](https://hackaday.com/2020/02/26/openchronograph-lets-you-roll-your-own-smart-watch/)から発見。画像もここから転載。

文字盤はアナログ時計ですが、活動量計や歩数計、通知機能などを搭載した腕時計。いわゆる「ハイブリッドなスマートウォッチ」を改造するためのボードを紹介します。

この記事で紹介しているのは、ハイブリッドスマートウォッチの内部基板をそっくり入れ替えてArduinoを基にしたHackしやすいものに変更してしまうという手法です。

ハック用の基板はオープンソースで開発されており、RTC、3軸加速度センサー、気圧・緯度経度・温度センサー、3つのマイクロモーター駆動回路を搭載しており、時計に必要な機能はそろっています。

スマートウォッチは面白いガジェットですが、各社独自の基板・ファームウェアで、改造するのが難しいところがあるので、このようなオープンソースの試みは面白そうです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/Nqi1F6wrvCc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
