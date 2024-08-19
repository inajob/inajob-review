---
title: ESP32にSPIRAMを足す方法
date: 2019-03-05T23:00:51.192Z
description: ESP32にSPIRAMを足す方法を紹介します
image: /img/esp32_feather_psram.jpg
tags:
  - ESP32
---
[Upgrade ESP32 board without psRAM with 4MB/8MB SPIRAM](https://loboris.eu/forum/showthread.php?tid=117)にて発見。写真もここから転載。

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

## 実際に試した方が！

ここに書いた手法を実際に試し、PSRAMの無いESP-WROOM-32モジュールに非破壊に外付けでSPIRAMを増設できたという報告を頂きました。


<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">と、いうわけで、買いました、SPRAM<br>ESP-PSRAM64H 3.3V SOP8 64Mbit PSRAM compatible with IPS6404LSQ IPS6404L-SQ-SPN<a href="https://t.co/vZRhXslUVC">https://t.co/vZRhXslUVC</a><br>なんか1ヶ$0.9位だったような気がする(Ali)<br>そして変換基板でこんなのを作って...無理やり裏に付ける...とたぶんok <a href="https://t.co/C5l09R6shA">pic.twitter.com/C5l09R6shA</a></p>&mdash; n602💉💉💉 (@n602_NA) <a href="https://twitter.com/n602_NA/status/1384903307060187137?ref_src=twsrc%5Etfw">April 21, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



