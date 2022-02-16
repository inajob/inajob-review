---
title: 低解像度のドットマトリクスLEDで複雑な漢字を表示するHACK
date: 2022-01-26T23:02:07.986295
description: 8x8の低解像度ドットマトリクスLEDで複雑な漢字を表示するHACKを紹介します
image: /img/低解像度のドットマトリクスLEDで複雑な漢字を表示するHACK.jpg
tags:
  - 日本
  - HACK
  - マトリクスLED
---
[KenKenMkIISRさんのTweet](https://twitter.com/KenKenMkIISR/status/1476934681492819974)から発見。画像もここから転載。

ドットマトリクスLEDといえば8x8が基本単位です。
英字や数字を表示するにはこれで十分なのですが、日本語となるとちょっと物足りないです。
そんな時に役立つのがこのTweetで紹介されている手法です。

4倍解像度のフォントデータを用意し、1つのドットにつき2x2のドットを時分割で素早く表示を切り替えるだけなのですが、人間の目には高解像度の文字として認識することができます。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">新年おめでとうございます。今年もよろしくお願いします。<br>信じられないかもしれませんが、横8ドットの低解像度デバイスで明朝体を表示しています。 <a href="https://t.co/hInCF1SXJq">pic.twitter.com/hInCF1SXJq</a></p>&mdash; KenKenMkIISR (@KenKenMkIISR) <a href="https://twitter.com/KenKenMkIISR/status/1476934681492819974?ref_src=twsrc%5Etfw">December 31, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
