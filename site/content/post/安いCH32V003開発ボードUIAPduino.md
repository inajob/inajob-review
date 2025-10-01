---
title: 安いCH32V003開発ボードUIAPduino
date: 2025-10-01T22:54:58.290552
description: 安いCH32V003開発ボードUIAPduinoについて紹介します
image: /img/安いCH32V003開発ボードUIAPduino.jpg
tags:
  - CH32V003
  - 開発ボード
---
[スイッチサイエンスのページ](https://www.switch-science.com/products/9914)から発見。画像もここから転載。

最近流行りの？CH32V003ですが、開発ボードの入手性は微妙です。

もちろん腕に覚えのある人は自分で基板を設計すればよいのですが、そこまでは出来ないという人も多いでしょう。
そんな中で、今回紹介するのはスイッチサイエンスなどで購入できるCH32V003搭載の開発ボードです。

初期ファームウェアにはUSB書き込みができるブートローダーが書き込まれているため、専用のライターを使う必要なく開発が出来ます。
（CH32V003にはUSB機能は搭載されていないので、この機能はソフトウェア的にUSBデバイスを実装することで実現しています）

注意点としては、Arduino対応を謳ってはいますがCH32V003用のArduinoコアはビルド後のバイナリサイズが大きくなりがちで、複雑なことをするには向かないです。
本格的に使いたい場合は[ch32fun](https://github.com/cnlohr/ch32fun) というライブラリを使うのがおすすめです。
Arduinoとは使勝手が違いますが、サンプルプログラムが充実しているので、そこまで困ることはなさそうです。

なんといっても290円という価格が魅力です。スイッチサイエンスで何か買うときについでに何枚か買いたくなってしまいますね。



<iframe width="100%" height="315" src="https://www.youtube.com/embed/ytX5Kg9k41k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

