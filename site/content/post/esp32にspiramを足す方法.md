---
title: ESP32にSPIRAMを足す方法
date: 2019-02-09T02:44:51.192Z
description: ESP32にSPIRAMを足す方法を紹介します
image: /img/esp32_feather_psram.jpg
---
[Upgrade ESP32 board without psRAM with 4MB/8MB SPIRAM](https://loboris.eu/forum/showthread.php?tid=117)にて発見

[IPS6404L-SQ-SPN](https://www.electrodragon.com/product/2pcs-ipus-ips6404-iot-ram/)をESP32に外付けする方法について紹介されている。
3.3V駆動なのでそのままつなげることができる。

この投稿によると、SPIRAMの2,3,4,5,8ピンをそのままESP32の対応するピンに接続する。
1番ピンはESP32の16番ピンに10kのプルアップを付けて接続。
6番ピンはESP３２のGPIO17に接続。

この投稿の初めの写真は、ESP32のシールドを引っぺがして、中の端子に直接つなげているが、これをすると日本では技適が無効になってしまいます。外付けすることもできると書いてあるので、もし試すなら外付けする方法をお勧めします。

その場合の配線はこんな感じ

```
1 - GPIO16
2 - SD0
3 - SD3
4 - GND
5 - SD1
6 - GPIO17
7 - SD2
8 - 3,3v
plus 10k pullup on pin 16 (1 - R10k - 8)
```


