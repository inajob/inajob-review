---
title: ATmega2560をコアとしたラップトップ風ガジェット
date: 2026-11-01T22:04:26.112302
description: ATmega2560をコアとしたラップトップ風ガジェットの作例を紹介します
image: /img/ATmega2560をコアとしたラップトップ風ガジェット.jpg
tags:
  - Atmega2560
  - Cyberdeck
---
[AVR Laptop Pushes The Limits Of 8-Bit](https://hackaday.com/2026/10/04/avr-laptop-pushes-the-limits-of-8-bit/)から発見。画像もここから転載。

ATmega2560というのは、RAMがわずか8KBしか搭載されていない、Arduino Megaなどで広く使われている8ビットのマイクロコントローラです。

この記事では、ATmega2560を頭脳に据え、FreeRTOSを移植してマルチタスク環境を実現した自作ラップトップ端末を紹介しています。専用ドライバを構築して128×64ドットのモノクロ液晶で24fpsの動画再生や音声出力をこなすほか、Alt-Tabのようにアプリ（タスク）を切り替えてゲームやメモ帳を行き来させるなど、8ビット機の限界に挑んだ内容となっています。

限られたリソースの8ビットマイコンであっても、ファームウェアの工夫次第でマルチタスクの切り替えまで構築できる点は非常に興味深く、マイコンの限界を探るハックとして調べてみようと感じました。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/KBe1VKjbryw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



