---
title: ATSAMD21を使った最小構成開発環境の紹介
date: 2019-03-24T13:11:47.903Z
description: ATSAMD21を使った最小構成開発環境を紹介します。
---
[Minimal ATSAMD21 Computer 2](http://www.technoblogy.com/show?2HQ2)から発見。画像もここから転載。

ATSAMD21というのはArduino M0やArduino Zeroなどで使われているAtmelのCortex-M0+のCPUです。
この記事では、ArduinoボードではなくICと周辺部品をブレッドボード上で回路を構成し、最低限の開発環境を作る方法を紹介しています。

同じIC（ATSAMD21G18A）は秋月電子でも買うことができるため
http://akizukidenshi.com/catalog/g/gI-09837/
このICを使って何か作ろうと考えている方は要チェックです。

初回のブートローダーの書き込みにはArduino Zeroなどを使うようです。その後Arduinoとして書き込む際はICに内蔵されているUSBの機能で書き込みができるということのようです。

プロトタイピングをArduino M0やArduino Zeroで行った後に小さくプリント基板にまとめる際などにもこの記事に記載のノウハウが役に立つでしょう。
