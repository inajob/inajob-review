---
title: 8ドルのRISC-Vチップ
date: 2019-02-16T03:48:28.711Z
description: 噂のRISC-Vチップが発売されたので紹介します。
image: /img/riskv.jpg
tags:
  - RISC-V
  - MAix
---
[Sipeed MAIX-I module w/o WiFi ( 1st RISC-V 64 AI Module, K210 inside )
](https://www.seeedstudio.com/Sipeed-MAIX-I-module-w-o-WiFi-1st-RISC-V-64-AI-Module-K210-insid-p-3210.html)で発見。写真もここから転載。

噂のRISC-Vアーキテクチャのチップ。8ドル程度の安さで買えるというのが画期的。

AI的な機能も付いているということで、TPUも搭載されているようだ。
8MBのSRAM、400MHzのCPU（最大800MHz)、TPUやAudioProcessor、カメラ用のインターフェースなども付いているらしい。盛りだくさん。

このモデルはWiFi機能がついていないが、技適がないとWiFiが使えない日本においては、こちらのチップのほうが良いだろう。

[開発用ボード](https://www.seeedstudio.com/Sipeed-M1-dock-suit-M1-dock-2-4-inch-LCD-OV2640-K210-Dev-Board-1st-RV64-AI-board-for-Edge-Computing-p-3211.html)もWiFiなしバージョンが存在し、19ドル程度で購入できるようだ。カメラと画面がついてこの値段はかなり良心的、というか普通に安い。

開発にはFreeRTOSベースのSDKか、micropythonを使うことができるようだ。
