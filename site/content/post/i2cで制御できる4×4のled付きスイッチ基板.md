---
title: I2Cで制御できる4×4のLED付きスイッチ基板
date: 2019-05-12T01:23:48.949Z
description: I2Cで制御できる4×4のLED付きスイッチ基板の作例を紹介します。
image: /img/buttonmatrix.jpg
---
[Illuminated Button Matrix](http://www.technoblogy.com/show?1YJO)から発見。画像もここから転載。

光るスイッチ、というのは非常にガジェットっぽくて、心惹かれる部品です。
この記事では4×4のLED付きタクトスイッチをI2Cで制御できるボードの作例を紹介しています。

CPUはATtiny88で非常に簡単な回路で16個のLED付きスイッチを制御しています。
動作の例としてArduino UNOと接続させて、「Takoyoki+」という（おそらく[ライツアウト](https://ja.wikipedia.org/wiki/%E3%83%A9%E3%82%A4%E3%83%84%E3%82%A2%E3%82%A6%E3%83%88)のような）ゲームを動かす例を紹介しています。
