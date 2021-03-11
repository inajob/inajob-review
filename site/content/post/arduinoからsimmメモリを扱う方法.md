---
title: ArduinoからSIMMメモリを扱う方法
date: 2021-02-23T12:17:41.574Z
description: ArduinoからSIMMメモリを扱う方法を紹介します。
image: /img/ram-arduino3.jpg
tags:
  - Arduino
---
[30pin-simm-ram-arduino](https://github.com/zrafa/30pin-simm-ram-arduino/blob/master/README.md)から発見。画像もここから転載。

パソコンのメモリと言えば最近はDIMMですが、以前はSIMMタイプのメモリが主流でした。

この記事ではArduinoでSIMMメモリを扱う方法を紹介しています。
ピン数の制約で4KBのメモリを扱う例を紹介していますが、Analogピンを利用することで256KBまで扱えるようになるとのことです。

まぁ実際はSPI接続のRAM([23LC512](https://akizukidenshi.com/catalog/g/gI-14062/)など)などがあるので、SIMMメモリが役立つことはあまりなさそうですが、テクニックとしては面白そうです。

