---
title: ESP32で動くVGA出力機能付きのテキストエディタ
date: 2022-12-04T23:18:39.651562
description: ESP32で動くVGA出力機能付きのテキストエディタの作例を紹介します。
image: /img/ESP32で動くVGA出力機能付きのテキストエディタ.jpg
tags:
  - ESP32
  - テキストエディタ
  - FabGL
---
[GitHub - maksimKorzh/esp32-kilo: Kilo text editor port to esp32 using FabGL](https://github.com/maksimKorzh/esp32-kilo)から発見。画像もここから転載。

ESP32でVGA出力付きのテキストエディタの作例です。
エディタ界隈では有名(?)な[kilo](https://github.com/antirez/kilo)という実装を参考に作られており、短いコードでテキストエディタが作られています。

画面出力部分は[FabGL](../../post/esp32%E3%81%A7vga%E8%A1%A8%E7%A4%BA%E3%82%92fabgl/)を利用しているため、ソースコードは600行程度とシンプルにまとまっています。

ESP32を使ったDOSみたいな仕組みがあると、結構何でもできてしまうのではないかと妄想が膨らみます。



