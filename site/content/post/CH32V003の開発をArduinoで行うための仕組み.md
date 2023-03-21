---
title: CH32V003の開発をArduinoで行うための仕組み
date: 2023-03-21T23:27:33.783225
description: CH32V003の開発をArduinoで行うための仕組み
image: /img/CH32V003の開発をArduinoで行うための仕組み.jpg
tags:
  - CH32V003
  - Arduino
---
[GitHub - AlexanderMandera/arduino-wch32v003: Arduino Core for CH32V303 RISC-V microcontroller](https://github.com/AlexanderMandera/arduino-wch32v003)から発見。画像もここから転載。

CH32V003の開発をArduinoで行うための仕組みです。

RISC-Vの格安ICであるCH32V003ですが、ペリフェラルの操作にはSDKの独自の関数を使う必要があります。

このプロジェクトではCH32V003向けのArduino風ラッパーを提供しています。
RISC-V用のgccは別途インストールが必要そうですが、Arduinoに慣れた人からすると嬉しそうです。

まだシンプルなI/O命令とdelay命令くらいしかサポートされていないので、利用の際は注意が必要です。


