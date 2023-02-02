---
title: 古いビデオコントローラの出力をキャプチャしてSPI接続TFT表示を行う
date: 2023-02-02T23:22:22.457062
description: 古いビデオコントローラの出力をキャプチャしてSPI接続TFT表示を行う手法を紹介します
image: /img/古いビデオコントローラの出力をキャプチャしてSPI接続TFT表示を行う.jpg
tags:
  - TFT
  - 液晶
  - 表示機
---
[Classic Video Chip Drives A Modern TFT](https://hackaday.com/2023/01/07/classic-video-chip-drives-a-modern-tft/)から発見。画像もここから転載。

古いビデオコントローラであるTMS9928Aの出力をキャプチャしてSPI接続TFTで表示を行っている作例です。

こういうのはよくFPGAで実装されますが、この記事ではSTM32G4を使って実現しています。
今やSPI接続のTFTディスプレイはコモディティ化しているので、こういう手法があると、レトロガジェットの再実装にも役立ちそうです。


