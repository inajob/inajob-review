---
title: 小さいソーラパネルで動作する省エネのLチカ
date: 2022-02-02T21:51:39.059038
description: 小さなソーラーパネルで動作する省エネで動作するLチカの作例を紹介します。
image: /img/小さいソーラパネルで動作する省エネのLチカ.jpg
tags:
  - ソーラー
  - 日本
---
[ゆういちろうさんのTweet](https://twitter.com/yuuitirou528/status/1484176014645547008)から発見。画像もここから転載。

ソーラーパネルを使った作例は、電池なしでも半永久的に動作するため夢がありますが、大きなパネルを使わないと大した電力が得られず、なかなかハードルが高いです。

このTweetでは、一円玉大サイズのソーラーパネルを使い、LEDを点滅させることを実現しています。

M34-2LというLEDフラッシャーICをつかい、また電流量を制限するためにLEDとの間に1MΩの抵抗を挟んでいるようです。
次の点灯のために必要な電力を貯めるために10uFのコンデンサも実装されています。

この仕組みだと室内の照明の明かりなどでも動作するようです。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">小さいソーラーパネルの電力でLEDがチカチカするやつ好きなので作ってみた。部屋の灯かりでも動く！ <a href="https://t.co/2njMTD2miV">pic.twitter.com/2njMTD2miV</a></p>&mdash; ゆういちろう🦐 (@yuuitirou528) <a href="https://twitter.com/yuuitirou528/status/1484176014645547008?ref_src=twsrc%5Etfw">January 20, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
