---
title: PICライターとしてRaspberry Pi Picoを使う
date: 2024-01-25T23:07:48.085241
description: PICライターとしてRaspberry Pi Picoを使う手法を紹介します
image: /img/PICライターとしてRaspberry Pi Picoを使う.jpg
tags:
  - Raspberry Pi Pico
---
[Saving PIC Microcontrollers With DIY Programmer](https://hackaday.com/2024/01/14/saving-pic-microcontrollers-with-diy-programmer/)から発見。画像もここから転載。

PICに書き込むためには専用のライターが必要ですが、これは自作することも出来ます。
ここでは、Raspberry Pi Picoを使ってPICライターを自作しています。

Raspberry Pi PicoはUSBマスストレージデバイスとしてふるまうことが出来るので、パソコンからPICのHEXファイルを、そのドライブに書き込むことで、PICマイコンに書き込みできるというスムーズな開発体験を提供できます。

Raspberry Pi PicoをプログラマブルなUSBマスストレージデバイスとととらえる手法はいろいろと応用が出来そうです。


