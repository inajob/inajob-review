---
title: スルーホール部品のみで作るArduino互換キット
date: 2019-04-11T23:00:41.969Z
description: すべてスルーホールのパーツを使うことで自作しやすくしたArduino互換機を紹介します
image: /img/makit-tht.png
tags:
  - Arduino
---
[MAKIT-THT Soldering Kit](https://thunkitelectronics.com/products.html?page=MAKIT-THT%20Soldering%20Kit)で発見

最近の電子回路の多くは表面実装の部品を使っているものが多いです。
そうすることで、大量生産は楽ですし、基板のサイズを小さくすることができます。しかし、表面実装チップの実装は電子工作素人には難しい・・

ということで作られたのが、このMAKEIT-THTです。これはArduino Unoと同等の機能を持ったボードですが、すべてスルーホール部品で実装されています。

このキットを作ることで自分の手でArduinoを作ることができます。

（この手のキットで難しいのがUSBシリアル変換ICだと思っています。スルーホールのUSBシリアル変換ICはあまり種類がないからです。このキットではMCP2221Aを使っているようですが、このICではリセットをうまく扱うことができません。
そこで、このキットでは書き込み時にリセットボタンを手で押す、ということで問題を回避しています。（回避といえるのか・・？））

そういう意味ではArduinoとよく似ていますが、挙動は少し違うキットといえます。

[Tindie](https://www.tindie.com/products/cmccaskey/makit-tht-arduino-through-hole-soldering-kit/)からキットを購入できるので、自分の手でArduinoを作ってみたい人は買ってみてはどうでしょう？

部品表（BOM）や回路、組み立てガイドなどが充実しているので、Arduinoのようなボードを作ろうとしている人の参考にもなると思います。
