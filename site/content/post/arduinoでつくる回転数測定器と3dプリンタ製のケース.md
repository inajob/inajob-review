---
title: Arduinoでつくる回転数測定器と3Dプリンタ製のケース
date: 2021-06-07T11:00:18.792Z
description: 3Dプリンタで作ったケースに収まったArduinoで作られた回転数測定器の作例を紹介します。
image: /img/tachometer.jpg
tags:
  - 3Dプリンタ
  - Arduino
---
[LASER TACHOMETER KNOWS HOW FAST YOU WERE SPINNING BACK THERE](https://hackaday.com/2020/02/12/laser-tachometer-knows-how-fast-you-were-spinning-back-there/)から発見。画像もここから転載。

回転数を測定する装置はたくさん市販されていますが、比較的簡単に自作することが出来るようです。材料はArduino、表示用のOLED、レーザーダイオード、受光素子です。

その仕組みはともかく、この作例の素晴らしいのは3Dプリンタで作られたケースです。
Arduino NanoやOLEDがきちっとハマる枠を3Dプリンタで作り、その枠をブリッジするような橋状の部品をねじで止めることで、部品をきっちりとケースに固定しています。

おかげでこの作例ではユニバーサル基板を使うことなく、しかし部品が取っ散らかる事のない、高い完成度となっています。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/0UqHNrqmTRU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>