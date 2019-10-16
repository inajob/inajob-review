---
title: ATtinyでMIDIをCVに変換する
date: 2019-10-16T23:00:09.524Z
description: ATtiny45/85を使ってMIDIをCVに変換する作例を紹介します。
image: /img/gomidi2cv.jpg
tags:
  - MIDI
  - attiny
---
[DIY GOOD OL’ MIDI TO CV](http://blog.dspsynth.eu/diy-good-ol-midi-to-cv/)から発見。画像もここから転載。

MIDIの入力を受け付けて、CV/Gage出力することができるプログラムの紹介です。
この仕組みがあると、MIDIを出力できる高レイヤーのDTM機器と、CV/Gateで動作する低レイヤーのシンセサイザーなどを連携させることができます。

しかもこれはATTinyを使った簡単な回路で、しかもプログラムを変更することで様々なMIDI信号に対応できます。ハードウェアDTM機器を組み合わせて使っている方には便利なユーティリティとして使うことができるでしょう。
