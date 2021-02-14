---
title: 暗号化チップを搭載したArduino互換ボード
date: 2021-02-09T11:00:00.344Z
description: ATmega4809と暗号化チップであるECC608を搭載した開発ボードを紹介します
image: /img/seeed-crypto-atmega4809-ecc608.jpg
tags:
  - Arduino
  - ATmega4809
  - 開発ボード
---
[Seeeduino Crypto (ATmega4809 & ECC608)](https://www.seeedstudio.com/Seeeduino-Crypto-ATmega4809-ECC608-p-4369.html)から発見。画像もここから転載。

Arduino互換の面白いボードです。新しいArduino Nano Everyなどにも使われているAATめが4809をコアとし、暗号化に特化したECC608というチップも搭載しています。

この暗号化チップはSHA-256 & HMAC Hash / AES-128を素早く計算することができるもののようで、メインCPUに負荷をかけることなく暗号化を実現することができます。
