---
title: 対話型のシェルでArduinoを操作する
date: 2021-08-18T14:00:59.434Z
description: 対話型のシェルでArduinoを操作できるようになるファームウェア Piconomixを紹介します。
image: /img/piconomix.gif
tags:
  - Arduino
---
[ARDUINO GETS A COMMAND LINE INTERFACE](https://hackaday.com/2018/11/10/arduino-gets-a-command-line-interface/)から発見。画像もここから転載。

Arduinoのプログラムは、ビルドしたアプリケーションを書き込むのが普通です。
ちょっと動作を変更したくなった場合はプログラムを書き直し、再度ビルドして、書き込みなおす必要があります。


しかし、場合によっては対話型のCLIでコマンドを実行するような形で、ArduinoのGPIOを操作できたほうが便利なことがあります。


この記事で紹介しているPiconomixというファームウェアを使うと、CLIで対話的にGPIOを操作できるようになります。


I2CやSPIといったよく使うインターフェースも簡単に扱えるようになっているようで、便利そうです。

