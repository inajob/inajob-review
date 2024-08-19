---
title: ATtiny85ボードによる謎解きゲーム
date: 2020-10-05T23:00:19.873Z
description: ATtiny85を使って作成されたCTF(Catch The Flag)を紹介します。
image: /img/attiny-ctf.png
tags:
  - attiny85
  - HACK
  - ゲーム機
---
[Capture The Flag Shitty Add-On](https://blog.wokwi.com/capture-the-flag-shitty-add-on/)から発見。画像もここから転載。

コンピュータを使った競技としてCTF（Capture The Flag）というのがあります。これはあるシステムに隠された秘密のメッセージなど（Flag）をハッキングなどを駆使して探し出すというものです。

今回紹介するボードはそのハードウェア版です。
ボードにはATTiny85が実装されておりI2Cの端子が露出しています。まず最初の挑戦はボードに実装されているLEDを点灯させることです。

その後はさらに難しい課題が用意されています。

[オープンソースプロジェクト](https://github.com/urish/ctf-shittyaddon)なので、部品をそろえることで自分でも同じものを作ることができます。
