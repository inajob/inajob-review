---
title: Arduboy互換機にMidiがついた「midiboy」
date: 2019-07-13T12:47:47.888Z
description: Arduboyの互換機にMidi端子をつけたmidiboyを紹介します。
image: /img/midiboy.png
tags:
  - ゲーム機
  - 音楽
---
[Meet Midiboy!](https://blokas.io/midiboy/)から発見。画像もここから転載。

MidiboyはArduboyにMIDI端子がついたガジェットです。

[回路図](https://github.com/BlokasLabs/Midiboy-Schematics/blob/master/Midiboy.pdf)を見るとArduboyとはちょっと違った回路になっていることがわかります。

まずCPUがAtmega328になっています。このチップはハードウェアとしてはUSBをサポートしていません。しかし、ソフトウェアでUSBを実装しているようでそこに直接USBの信号を入力しています。（[USBasp](https://www.fischl.de/usbasp/)というソフトウェアのようです）

MIDI端子はINとOUTがあり、それぞれがArduinoのピンとつながっています。

（USBaspはAVRのライターとしては知っていたのですが、USBasp自体のファームウェアを書き換える機能が存在することをこれを見て知りました。）

