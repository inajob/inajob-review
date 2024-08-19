---
title: CCMという高速なメモリを搭載したSTM32マイコン
date: 2021-11-29T11:00:14.332Z
description: STM32マイコンの中にはCCMと呼ばれる高速なメモリを搭載したものがあるようです。
image: /img/stm32-ccm.jpg
tags:
  - STM32
  - HACK
---
[BOOST THE SPEED OF YOUR STM32 MICROCONTROLLERS BY 31% USING CORE-COUPLED MEMORY](https://www.electronics-lab.com/boost-speed-stm32-microcontrollers-31-using-core-coupled-memory/)から発見。画像もここから転載。

STM32のチップの中にはCore Coupled Memory (CCM)という種類のメモリを搭載しているものがあるそうです。

Flashメモリや、通常のSRAMよりも早い速度でアクセスできるメモリのようで、ここに命令セットを書き込んで実行することで、通常のメモリに配置したプログラムよりも早く処理を実行できるようです。

リアルタイム処理にこだわりたいときにはこういったプロセッサの利用を検討してみるのもよさそうです。
