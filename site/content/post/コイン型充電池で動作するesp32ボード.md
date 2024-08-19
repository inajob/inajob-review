---
title: コイン型充電池で動作するESP32ボード
date: 2019-05-12T23:00:40.380Z
description: コイン型充電池で動作するESP32ボードを紹介します。
image: /img/esp32-pico-d4.png
tags:
  - ESP32
---
[A COIN CELL POWERS THIS TINY ESP32 DEV BOARD
](https://hackaday.com/2019/02/22/a-coin-cell-powers-this-tiny-esp32-dev-board/)にて発見。写真もここから転載。

ESP32の開発用モジュールはたくさん存在しますが、この「Pico D4」というボードはコイン型充電池で動作するというのが特徴のボードです。LIR2450というタイプのバッテリのようです。

元となったボードは[これ](https://www.youtube.com/watch?v=WG5k9fxXMjg)のようで、これは14550というかなり大きな充電池を必要としていました。

ESP32を日本で使う場合には技適を取得しているモジュールを使う必要があるので、これをそのまま使うことはできませんが、この小型の充電池は魅力的ですね。

プロジェクトは[オープンソースで公開されている](https://github.com/mike-rankin/ESP32_CoinCell)ので細かい部分が気になる人は見てみると良いでしょう。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/QvrdFFZR3Nw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
