---
title: 映像にに情報をオーバーレイするOSDチップをESP32から制御する
date: 2026-10-19T22:01:27.892195
description: 映像にに情報をオーバーレイするOSDチップをArduinoから制御する
image: /img/映像にに情報をオーバーレイするOSDチップをESP32から制御する.jpg
tags:
  - OSD
---
[Own The OSD Chip In Your Cheap Composite Monitor](https://hackaday.com/2026/10/03/own-the-osd-chip-in-your-cheap-composite-monitor/)から発見。画像もここから転載。

OSD（On Screen Display）チップとは、画面上にメニューや文字情報をオーバーレイ表示するための専用プロセッサのことです。

この記事では、安価な車載バックモニター等に使われているAMT630Aという制御チップのOSD機能を、外部のマイコンから直接制御するリバースエンジニアリングの試みが紹介されています。元のファームウェアを無理に書き換えるのではなく、基板上のテストパッドからI2C経由で内部レジスタを直接叩くことで、ESP32から任意のグラフィックやセンサー情報をオーバーレイ表示させるライブラリが公開されています。

映像に文字をオーバーレイする機能が安価で手に入るとしたら・・・これは何かに使えそうです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/0eQ94DHOay0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



