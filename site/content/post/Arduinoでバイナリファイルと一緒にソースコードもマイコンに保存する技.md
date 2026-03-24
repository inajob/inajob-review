---
title: Arduinoでバイナリファイルと一緒にソースコードもマイコンに保存する技
date: 2026-03-24T23:32:02.738956
description: Arduinoでバイナリファイルと一緒にソースコードもマイコンに保存する技
image: /img/Arduinoでバイナリファイルと一緒にソースコードもマイコンに保存する技.jpg
tags:
  - HACK
  - Arduino
---
[Forgetfulino Puts Back Up Of Source Inside The Binary](https://hackaday.com/2026/03/18/forgetfulino-puts-back-up-of-source-inside-the-binary/)から発見。画像もここから転載。

Arduinoを用いた開発ではマイコンにプログラムを書き込むことで、意図した動作を実現します。
このプログラムはバイナリ形式となっており、ソースコードとは異なるものです。

月日が経って、プログラムの書きこまれたマイコンだけが残った場合、そのソースコードを探すことが困難になるという問題があります。

この記事では、この問題の解決策として、ソースコードの内容もマイコンのROMに書き込む方法を紹介しています。

マイコンのメモリは限りがありますが、もし単純なプログラムでマイコンの容量に空きがあるなら、このような手法も便利そうです。



