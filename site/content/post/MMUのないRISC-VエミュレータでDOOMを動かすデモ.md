---
title: MMUのないRISC-VエミュレータでDOOMを動かすデモ
date: 2022-12-12T22:59:58.546502
description: MMUのないRISC-VエミュレータでDOOMを動かすデモ
image: /img/MMUのないRISC-VエミュレータでDOOMを動かすデモ.jpg
tags:
  - RISC-V
---
[A Tiny RISC-V Emulator Runs Linux With No MMU. And Yes, It Runs DOOM!](https://hackaday.com/2022/12/07/a-tiny-risc-v-emulator-runs-linux-with-no-mmu-and-yes-it-runs-doom/)から発見。画像もここから転載。

MMUのない小規模なRISC-Vエミュレータを作りLinuxを動かし、そこでDOOMを実行しています。

このRISC-Vエミュレータはシンプルさゆえに移植もしやすそうで、[M5Stackに移植するのも比較的簡単のようです。](https://twitter.com/verylowfreq/status/1601531892410777600)
（ただしM5Stackでの実行は非常に遅いようですが・・）


<iframe width="100%" height="315" src="https://www.youtube.com/embed/YT5vB3UqU_E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/M5Stack?src=hash&amp;ref_src=twsrc%5Etfw">#M5Stack</a> (ESP32)でLinux (RISC-V)を動かすコードを公開しました。実用性には触れませんが、キーボードのFACEを利用すればまさに手のひらLinuxマシンとなる、ロマン性能が高めのブツです。<br><br>コード:<a href="https://t.co/PrM18pHjot">https://t.co/PrM18pHjot</a><br><br>起動画面を8分ほど眺める動画: <a href="https://t.co/IdAm9fAEMW">https://t.co/IdAm9fAEMW</a></p>&mdash; verylowfreq (@verylowfreq) <a href="https://twitter.com/verylowfreq/status/1601531892410777600?ref_src=twsrc%5Etfw">December 10, 2022</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


