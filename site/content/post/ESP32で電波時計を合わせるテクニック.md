---
title: ESP32で電波時計を合わせるテクニック
date: 2022-03-09T23:00:00.000000
description: M5Stick-Cだけを使って電波時計用の電波を発する手法を紹介します
image: /img/ESP32で電波時計を合わせるテクニック.jpg
tags:
  - M5Stick-C
  - 電波時計
  - ESP32
  - 日本
---
[ESP32 (M5Stick-C) で電波時計を合わせよう](https://neocat.hatenablog.com/entry/2020/07/24/074229)から発見。画像もここから転載。

電波時計は時刻を勝手に合わせてくれて便利ですが、電波をうまく拾えない環境や、天災やメンテナンスによる標準電波の停波などにより、うまく時刻が合わせられないことがあります。

この記事では、M5Stick-Cをつかって簡単に標準電波を発生させる手法が紹介されています。
アンテナが必要か、、と思いきや、電波時計にかなり近づけることでアンテナすら不要で電波時計の時計を合わせることができるようです。

このテクニックを使えば、電波時計を改造することなく好きな時刻に設定できる時計ガジェットも作ることができそうです。



