---
title: 3Dプリンタのブザーをgcodeで制御してMIDIファイルを演奏するHACK
date: 2021-11-30T11:00:20.156Z
description: 3Dプリンタのブザーをgcodeで制御してMIDIファイルを演奏するHACKを紹介します。
image: /img/midibuzzergcode.jpg
tags:
  - 3Dプリンタ
  - HACK
---
[SIGNAL THE END OF A PRINT WITH MIDI OF YOUR CHOICE](https://hackaday.com/2020/04/25/signal-the-end-of-a-print-with-midi-of-your-choice/)から発見。画像もここから転載。

3Dプリンタのコントローラボードにはブザーがついている機種が多く、これはgcodeで鳴らすことが出来ます。

このページで紹介しているのは、MIDIファイルからそのgcodeを生成するWebサービスです。

このツールで生成したgcodeを3Dプリントデータの最後に付け加えておけば、印刷が完了したときにファンファーレを鳴らすようなことが実現できます。
