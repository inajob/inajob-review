---
title: ArduinoからHDMI出力するためのボード
date: 2019-07-31T03:38:36.076Z
description: ArduinoからHDMI出力するためのボードを紹介します
image: /img/arduino-hdmi.jpg
tags:
  - Arduino
---
[HDMI FROM YOUR ARDUINO](https://hackaday.com/2019/07/26/hdmi-from-your-arduino/)から発見。画像もここから転載。

Arduinoからディスプレイに映像を映すには様々なテクニックが必要です。特に最近のディスプレイはHDMIコネクタが標準となっており、こうなればArduinoからは映像を出すことは難しいです。

そこで登場するのが、このHDMIを出力するShieldです。

といってもHDMI出力はやはり大変のようでかなり複雑な構成になっています。
説明を見るとRA8876という液晶コントローラのチップで映像を作り、このチップから出てくるRGB信号をCH7035Bを使ってHDMIに変換しているようです。

まぁしかし普通にこういうことをするならRaspberry Piを使うのが簡単なんだろうなぁという感想です。ともあれこういう挑戦は非常に興味深いと感じました。
