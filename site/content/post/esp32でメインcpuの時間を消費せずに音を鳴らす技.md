---
title: ESP32でメインCPUの時間を消費せずに音を鳴らす技
date: 2019-04-16T23:00:11.219Z
description: ESP32でメインCPUの時間を消費せずに音を鳴らす技を紹介します。
image: /img/esp32-sound-driver.png
tags:
  - ESP32
---
[This Sound Driver Runs on the ESP32’s ULP Coprocessor](https://blog.hackster.io/this-sound-driver-runs-on-the-esp32s-ulp-coprocessor-df5bd197e0cf) から発見。画像もここから転載。

ESP32はパワフルで便利ですが、音を鳴らしながら何かする、ということを実現するためには、貴重なCPUコアの1つを消費してしまうことになります。ESP32はCPUが2コアあるものの、なるべくそれらを音の再生のために使いたくないでしょう。

そこでこの記事ではESP32についている省電力プロセッサ通称ULPを使って音を鳴らす方法を紹介しています。ULPはEspressif独自の機械語でプログラミングをする必要があるため、活用している事例はとても珍しいです。

ソースコードは[公開されている](https://github.com/bitluni/ULPSoundESP32)ので、気になる人は手元で実行してみると良いでしょう。

追記： 少しソースコードを読んでみたところ、メインCPUでオーディオのストリームをバッファに詰め込みULPがそれを読み込んで音を鳴らすようです。タイマ割り込みに比べてメインCPUの処理時間が少なくなる、ということのようです。ソースコードの[このへん](https://github.com/bitluni/ULPSoundESP32/blob/master/ULPSoundMono/ULPSoundMono.ino#L38)を見ると、泥臭くULPの機械語を書いているのがわかります。これはデバッグが大変そう・・

実際にM5Stackで動作を確認した方もいるようです↓

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">おお…メインの処理とは別で音を鳴らすサンプル…参考になる…<a href="https://t.co/I9xQCVGCuJ">https://t.co/I9xQCVGCuJ</a> <a href="https://t.co/MLNvRwVZ1X">pic.twitter.com/MLNvRwVZ1X</a></p>&mdash; らびやん (@lovyan03) <a href="https://twitter.com/lovyan03/status/1116916152179888129?ref_src=twsrc%5Etfw">2019年4月13日</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

