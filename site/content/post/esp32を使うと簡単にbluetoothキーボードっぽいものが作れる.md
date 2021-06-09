---
title: ESP32を使うと簡単にBluetoothキーボードっぽいものが作れる
date: 2021-06-09T12:00:47.984Z
description: ESP32にスイッチをつなげるだけで簡単にBluetoothキーボード的なガジェットが作れてしまいます。
image: /img/bluetooth-hid.png
tags:
  - ESP32
  - Bluetooth
---
[EMULATING A BLUETOOTH KEYBOARD WITH THE ESP32](https://hackaday.com/2020/02/13/emulating-a-bluetooth-keyboard-with-the-esp32/)から発見。画像もここから転載。

ESP32は非常に強力なマイコンで、しかもかなり安く手に入ります。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=inajob-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B086WWNP9Y&linkId=9e9b7de3babb3883d1501b2444cdacac"></iframe>

ESP32はWiFiとBluetoothをサポートしており、WiFiはよく使われていますが、Bluetoothについては、あまり使用例を見かけないかもしれません。

しかし、この記事にあるようにESP32を使うと非常に簡単にBluetoothキーボードっぽいガジェットを作ることが出来ます。

いくつかのスイッチをESP32に接続し、すでに存在しているHIDのライブラリをちょっと利用すればあっという間にBluetooth接続のキーボードやゲームパッドの完成です。

オリジナルのキーボードやゲームパッドのアイデアのある方は試してみてはどうでしょうか？

<iframe width="100%" height="315" src="https://www.youtube.com/embed/4sIkW7wogrE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
