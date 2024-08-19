---
title: 電子工作でも「奴隷」廃止の動き（SPIバスの名称について）
date: 2020-07-12T23:00:10.636Z
description: 電子工作の世界も「奴隷」廃止の問題と無縁ではありません。
image: /img/sdo-sdi.png
tags:
  - 話題
---
ちょうどこんなニュースが話題になっています。
[IT用語も「奴隷」廃止の動き　「slave」は「フォロワー」や「レプリカ」に](https://www.itmedia.co.jp/news/articles/2007/13/news057.html)

電子工作の世界もこの問題とは無縁ではありません。

今回紹介するのは[A Resolution to Redefine SPI Signal Names](https://www.oshwa.org/a-resolution-to-redefine-spi-signal-names)です。

これはOpen Source Hardware Associationが発表した、SPI信号線の名称の再定義に関する文書です。

電子工作を少し嗜んだことがある方なら「SPI」という単語に聞き覚えがあるでしょう。
これは3本の信号線を用いて通信をする電子工作の世界ではごく一般的に用いられている「バス」の一種です。

今回問題となっているのはこの「信号線」の名称です。

SPIでは主となる機器とそれにつながる周辺機器があり、それぞれをMaster, Slaveと呼び、信号線もその名称を含んだものになっていました。
具体的にはMOSI(Master Out Slave In),MISO(Master In Slalve Out)というような名称です。
日本ではこれをそのままローマ字読みして「みそ」「もし」などと呼ばれたりしています。

今回の問題で、これらの名称にもメスが入れられました。
Open Source Hardware Associationはこれらの名称を次のように再定義することを推奨しています。

- COPI: Controller Out Peripheral In
- CIPO: Controller In Peripheral Out

もしくは

- SDO: Serial Data Out
- SDI: Serial Data In

(こちらは送りと受けでそれぞれ違う名称となるため注意が必要です)

従来Masterと呼んでいたものを Controller。Slaveと呼んでいたものを Peripheral に言い換えるという内容です。
3本ある信号線の残りの1本はSCK（Serial Clock）という、特に問題のない名称であるため、これはそのまま使用できます。
