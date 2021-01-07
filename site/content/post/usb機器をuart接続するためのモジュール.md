---
title: USB機器をUART接続するためのモジュール
date: 2021-01-07T12:21:23.246Z
description: USB機器をUART接続するための安価なモジュールを紹介します。
image: /img/ch559-module.jpg
tags:
  - CH559
  - USB
---
[CH559 USB Host to UART Bridge Module](https://www.tindie.com/products/matzelectronics/ch559-usb-host-to-uart-bridge-module/)から発見。画像もここから転載。

USB機器をマイコンから扱うためにはUSB Hostの機能が必要です。マイコンによってはUSB Host機能を持ったものもありますが、ArduinoやESP32などはこの機能を持ちません。

この記事で紹介するのはUSB機器をUART経由で操作できるようにするアダプタボードです。
コアとなっているのはCH559というICです。以前[CH552について紹介しました](../../post/usbもしゃべれる激安マイクロコントローラの使い方/)が、このCH559も似たようなスペックのICです。

加えてこのICは中国で安く手に入れられるものなので、ほかのUSB Hostモジュールより安価なのが特徴です。
