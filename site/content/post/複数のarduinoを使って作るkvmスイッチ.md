---
title: 複数のArduinoを使って作るKVMスイッチ
date: 2021-11-28T22:00:11.263Z
description: 複数のArduinoを使って作られたKVMスイッチの作例を紹介します。
image: /img/kvm-arduino.png
tags:
  - Arduino
---
[KVM USES MANY ARDUINOS](https://hackaday.com/2020/04/19/kvm-uses-many-arduinos/)から発見。画像もここから転載。

1つのキーボードを複数のPCに接続するために用いられるKVMスイッチをたくさんのArduinoを使って実装している作例です。

キーボードを接続するのはメインのArduinoで、そこからソフトウェアシリアルで2つのArduino Pro Microにキーの入力情報を送ります。

Arduino Pro MicroはそれぞれPCに接続されHIDキーボードとしてふるまいます。

2つのPCを切り替える際はあまり使わないキーであるScrollLockを用いています。
