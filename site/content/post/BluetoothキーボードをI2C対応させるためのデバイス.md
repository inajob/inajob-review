---
title: BluetoothキーボードをI2C対応させるためのデバイス
date: 2026-06-28T22:45:10.764487
description: BluetoothキーボードをI2C対応させるためのデバイスを紹介します
image: /img/BluetoothキーボードをI2C対応させるためのデバイス.jpg
tags:
  - Bluetooth
  - I2C
---
[Pi Pico Puts Bluetooth Keyboards On The I2C Bus](https://hackaday.com/2026/06/06/pi-pico-puts-bluetooth-keyboards-on-the-i2c-bus/)から発見。画像もここから転載。

Bluetoothのキーボードは市販品の種類が豊富で入手しやすい反面、マイコン側で直接その入力を受け取るには、Bluetoothプロトコルスタックの制御やHIDプロファイルの解析など、リソースの限られた環境では実装の難易度が高いという相性の悪さがあります。

この記事では、Raspberry Pi Pico Wを中継器として使い、市販のBluetoothキーボードからの入力を、既存のBlackBerry用I2Cキーボードの信号に模してI2Cバス上に流すプロジェクトを紹介しています。

複雑な無線処理をすべてPico W側に任せられるため、メインのマイコンからはシンプルなI2Cデバイスとして容易に市販キーボードを扱える仕組みになっています。

こういう仕組みがあると、自作のポータブル端末を作る際に、お気に入りの無線キーボードをわずかな配線でシステムに組み込めますね！




