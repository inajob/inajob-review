---
title: 物理スイッチでブートするOSを選択するデバイス
date: 2022-05-31T22:05:46.782871
description: 物理スイッチでブートするOSを選択するデバイスの作例を紹介します。
image: /img/物理スイッチでブートするOSを選択するデバイス.jpg
tags:
  - RP2040
---
[Simple Hardware Switch For OS Dualbooting, Thanks To RP2040](https://hackaday.com/2022/05/02/simple-hardware-switch-for-os-dualbooting-thanks-to-rp2040/)から発見。画像もここから転載。

この記事で紹介しているのは物理スイッチでブートするOSを選択するデバイスです。

RP2040ボード自体が起動ディスクとして振舞い、スイッチの状態に応じてgrubの設定ファイルがさし変得ているようです。

最近のマイクロコントローラはUSBマスストレージデバイスとして振る舞うことができるので、このようなガジェットが作りやすくなったようです。


