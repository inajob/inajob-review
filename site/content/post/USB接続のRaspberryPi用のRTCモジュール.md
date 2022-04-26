---
title: USB接続のRaspberryPi用のRTCモジュール
date: 2022-04-26T22:48:37.674193
description: USB接続のRaspberry Pi用RTCモジュールの作例を紹介します
image: /img/USB接続のRaspberryPi用のRTCモジュール.jpg
tags:
  - RaspberryPi
  - RTC
---
[USB-to-UART/I2C USB RTC for Raspberry Pi](https://www.tindie.com/products/sbc/usb-to-uarti2c-usb-rtc-for-raspberry-pi/)から発見。画像もここから転載。

Raspberry PiにはRTCモジュールが搭載されていないため、ネットワークに接続していない状態で再起動すると時計を合わせることができません。
ということで、外付けのRTCモジュールが必要となります。

この記事で紹介しているのはUSB接続のRTCモジュールです。

DS3231という定番のRTCモジュールをMCP2221というUSB-UARTのICを介してRaspberry Piからアクセスできます。



