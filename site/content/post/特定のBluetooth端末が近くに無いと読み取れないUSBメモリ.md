---
title: 特定のBluetooth端末が近くに無いと読み取れないUSBメモリ
date: 2025-06-03T22:11:32.04532
description: 特定のBluetooth端末が近くに無いと読み取れないUSBメモリの作例を紹介します
image: /img/特定のBluetooth端末が近くに無いと読み取れないUSBメモリ.jpg
tags:
  - Bluetooth
  - nRF52840
---
[A Presence-sensing Drive For Securely Storing Secrets](https://hackaday.com/2025/05/24/a-presence-sensing-drive-for-securely-storing-secrets/)から発見。画像もここから転載。

USBメモリは便利ですが、盗難されたり紛失したりした際に内部のデータを盗み見られないかが心配です。

この記事では特定のBluetooth端末が近くに無いと読み取れないUSBメモリを作ってこの問題に対応しています。
実証実験ということでnRF52840の開発ボードにCircuitPythonを導入したものを使いました。

nRF52840で動作するCircuitPythonはUSBマスストレージの機能もBLEの機能も操作できるので、このような実験を行うのに向いていたようです。




