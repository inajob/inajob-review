---
title: ESP32によるミニチュアピンボールマシン
date: 2022-08-04T23:18:45.730265
description: ESP32によるミニチュアピンボールマシンの作例を紹介します。
image: /img/ESP32によるミニチュアピンボールマシン.jpg
tags:
  - ESP32
  - ゲーム機
  - 3Dプリンタ
---
[Tiny Pinball Machine Also Runs X86 Code](https://hackaday.com/2022/07/21/tiny-pinball-machine-also-runs-x86-code/)から発見。画像もここから転載。

ESP32によるミニチュアピンボールマシンの作例です。
よくできたミニチュア筐体で液晶に表示されたピンボールゲームが遊べます。

このゲーム自体はDOS時代の古いゲームのようですが、これはx86の機械語で書かれていたようです。
そこでESP32上でx86エミュレータを動すことで、このゲームを動かしているようです。

さらに、触覚フィードバックや、筐体を傾けることによる操作などもサポートするようにアップグレードしています。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/0JSB5lK9SYs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

