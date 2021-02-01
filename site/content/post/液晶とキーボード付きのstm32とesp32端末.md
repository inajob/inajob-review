---
title: 液晶とキーボード付きのSTM32とESP32を搭載した端末
date: 2021-02-01T11:00:18.116Z
description: 液晶とキーボードがついたSTM32+ESP32ボードの作例を紹介します
image: /img/dumbdumb.jpg
tags:
  - ESP32
  - STM32
---
[DumbDumb](https://hackaday.io/project/168722-dumbdumb)から発見。画像もここから転載。

STM32コア（stm32g071r8）のほうで液晶の制御とVT100ターミナルエミュレータが実装されESP32上で動くMicroPythonとも連携できるようです。

単純なモバイルコンソール端末としても使い勝手がよさそうで、このようにデュアルプロセッサ構成にして、役割分担してモバイル端末を作るのも面白そうだと感じました。
