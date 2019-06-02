---
title: 新しいArduino Nanoシリーズ
date: 2019-05-29T12:29:06.410Z
description: 新しいArduino Nanoシリーズについて紹介します。
image: /img/new-arduino-nano.jpg
---
[Introducing Four New Arduino Nanos](https://blog.hackster.io/introducing-four-new-arduino-nanos-869b8abbccb4)から発見。画像もここから転載。

Arduino Nanoサイズの新しい開発ボードが発表されたようです。

## Arduino Nano Every

ほかのボードは技適が確認できていないので、日本人的に最も興味があるボードはこれです。

* メインチップは ATmega4809
* USB Serialは ATSAMD11

## Arduino Nano 33 IoT

* メインチップはATSAMD21
* WiFiとBLEのためのESP32を搭載した NINA W102
* 9軸加速度センサ
* 暗号チップ

## Arduino Nano 33 BLE

* nRF52840を搭載した NINA B306
* 9軸加速度センサ

## Arduino Nano 33 BLE Sence

* nRF52840を搭載した NINA B306
* 9軸加速度センサ
* 気圧センサ
* 湿度センサ
* 温度センサ
* 光センサ
* ジェスチャーセンサー
* マイク

## 注目点

これは全シリーズに共通の特徴として、ブレッドボードに接続できるスルーホールの穴に加えて、表面実装もできるパッドがついています。

このパッドを活用すると、小型を保ったままArduinoを組み込んだ製品を作ることができそうです。

私が作っている[RakuChord](https://inajob.github.io/rakuchord/)も内部にAruino Nanoをそのままくっつけていますが、表面実装するパッドがなかったので、組み込んだ高さが気になっていました。

![](/img/arduino-nano-mount.jpg)

このような用途に新しいArduino Nanoはぴったりだなと感じました。
