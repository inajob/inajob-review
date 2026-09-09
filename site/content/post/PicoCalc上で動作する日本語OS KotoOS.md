---
title: PicoCalc上で動作する日本語OS KotoOS
date: 2026-09-09T23:51:47.335515
description: PicoCalc上で動作する日本語OS KotoOSを紹介します
image: /img/PicoCalc上で動作する日本語OS KotoOS.jpg
tags:
  - PicoCalc
  - Raspberry PI Pico
  - Raspberry PI Pico 2
---
[手のひらサイズの自作OS「KotoOS」を公開しました — PicoCalcで動く日本語PDA環境をRustでつくった話](https://note.com/siskatech/n/n4f9dd2827e45)から発見。画像もここから転載。

ミニマルなマイコン端末用をPDA的に扱うことが出来るファームウェアは数多くありますが、そのミニマルさゆえに日本語に非対応なものがほとんどです。

この記事では、物理キーボード付き小型端末PicoCalc向けに開発された自作PDA環境「KotoOS」を紹介しており、帯状の分割描画やPSRAMからの8KiBストリーミング実行といった工夫によって、264KiBの制約下でSKK方式の日本語IMEや自作VM上のゲーム動作を実現したプロセスが解説されています。

その後バージョンアップして、RP2350A搭載のRaspberry Pi Pico 2 Wにも対応されており、さらに機能が追加されています。



