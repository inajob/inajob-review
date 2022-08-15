---
title: Raspberry Pi Pico上で動くvi風エディタとCコンパイラ
date: 2022-08-15T23:13:23.378442
description: Raspberry Pi Pico上で動くvi風エディタとCコンパイラの作例を紹介します。
image: /img/Raspberry Pi Pico上で動くvi風エディタとCコンパイラ.jpg
tags:
  - Raspberry Pi Pico
---
[Self-Hosted Pi Pico Development](https://hackaday.com/2022/08/01/self-hosted-pi-pico-development/)から発見。画像もここから転載。

Raspberry Pi Picoはパワフルなマイコンボードで、これだけで何でもできてしまいそうです。

ということで、この記事では、Raspberry Pi Picoの上で動作する開発環境の作例を紹介しています。
C言語のコンパイラ、vi的なエディタ、ファイルシステムなどをRaspberry Pi Picoだけで動くように移植することでセルフ開発環境を構築しています。

C言語のコンパイラについて、もう少し見てみると、amaccと呼ばれるコンパイラのパーサージェネレータを流用しc4と呼ばれる仮想言語機械上で動作する機械語を出力しているようです。

viについてはBusyBoxに内蔵されているものを移植しています。

これを使うためには何らかのシリアルコンソールにアクセスできる端末が必要ですが、その部分もRaspberry Pi Picoで実現することもそこまで難しくなさそうです。


