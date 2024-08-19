---
title: ゲームボーイアドバンスをESP32の力でBluetoothゲームコントローラにするHACK
date: 2021-11-23T12:00:36.878Z
description: ゲームボーイアドバンスの通信ポートを利用してESP32を接続しBluetoothゲームコントローラとして利用するHACKを紹介します。
image: /img/gba-meets-esp32.jpg
tags:
  - ゲームボーイアドバンス
  - ESP32
  - HACK
---
[Game Boy Advance Bluetooth HID](https://hackaday.io/project/166654-game-boy-advance-bluetooth-hid)から発見。画像もここから転載。

ゲームボーイアドバンスには通信ケーブルのポートがあります。このポートは通信対戦などで用いるのですが、その際カセットが刺さっていない端末にもプログラムを転送する機能があります。

この記事では、この機能を逆手にとって通信ポートから独自のプログラムを流し込んで実行するという手法を使い、ESP32をゲームボーイアドバンスに接続し、Bluetoothゲームコントローラとして利用できるようにするHACKを紹介しています。

ゲームコントローラにする以外にもこの通信ポートを使ったHACKは利用できそうです。
