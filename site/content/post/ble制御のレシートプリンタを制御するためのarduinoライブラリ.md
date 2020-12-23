---
title: BLE制御のレシートプリンタを制御するためのArduinoライブラリ
date: 2020-12-23T12:45:06.173Z
description: BLE制御のレシートプリンタを制御するためのArduinoライブラリを紹介します。
image: /img/thermal-printer.jpg
tags:
  - Arduino
  - Bluetooth
---
[bitbank2/Thermal_Printer](https://github.com/bitbank2/Thermal_Printer)から発見。画像もここから転載。

最近はBLE接続のレシートプリンタが流通するようになりましたが、それらは専用アプリからの印刷を前提としているものが多いです。

この記事で紹介するのは、BLE接続のレシートプリンタGOOJPRT PT-210をESP32やArduino Nano 33 BLEから制御するためのライブラリです。

これを使うことで、簡単にレシートプリンタを使った電子工作を実現することが出来ます。
