---
title: 高解像度液晶付きのESP32開発ボードMakePython ESP32 Color LCD
date: 2022-10-10T19:37:01.541Z
description: 高解像度液晶付きのESP32開発ボードMakePython ESP32 Color LCDを紹介します。
image: /img/makepython-esp32-cover.jpg
tags:
  - Makerfabs
  - ESP32
  - 開発ボード
---
この記事はMakerfabsの提供でお届けします。

今回紹介する[MakePython ESP32 Color LCD](https://www.makerfabs.com/makepython-esp32-color-lcd.html)は[Makerfabs](https://www.makerfabs.com/)から提供いただいたものです。

（ですが、[MakePython ESP32 Color LCD](https://www.makerfabs.com/makepython-esp32-color-lcd.html)は[Makerfabs](https://www.makerfabs.com/)をレビューしたい！と言ったのは自分なので、[Makerfabs](https://www.makerfabs.com/)が無理やりこの商品を押しているわけではなく、inajobの一押しアイテム！、という感じです。）

## MakePython ESP32 Color LCDとは

ESP32とディスプレイを搭載した開発ボードです。

![](/img/makepython-esp32-boot.jpg)

* 1.3インチディスプレイ 解像度240*240
* ESP32-WROOM または ESP32-WROVER
* USBシリアル変換IC CP2104
* Mirco USB端子

開発にはMicroPythonや、Arduinoを利用することが出来ます。

まぁESP32を搭載した開発ボードであればどれでもこれらの開発環境は利用できます。

## MicroPythonで開発してみる

公式のドキュメントではuPyCraftを使う例が紹介されているので、それに従ってみます。
MicroPythonの開発環境はほかにもたくさんあるので、どれを使ってもよいと思います。

### ファームウェアの書き込み

購入時のMakePython ESP32 Color LCDのファームウェアは謎のファームウェアが書き込まれているのですが、どうもMicroPythonではないようだったので、ファームウェアの書き込みから実施する必要がありました。

MicroPythonのファームウェアは[ここ](https://micropython.org/download/esp32/)から入手しました。

![](/img/makepython-esp32-burn.png)

これを焼きこむと・・

![](/img/makepython-esp32-prompt.png)

うごいた！

### サンプルプログラムの実行

公式ページで紹介されているGitHubのプロジェクトからサンプルプログラムを取得して実行してみます。

ファイルの一覧はこちら https://github.com/Makerfabs/Makerfabs-MakePython-ESP32-Color-LCD/tree/master/workSpace

以下のファイルをすべて書き込んでColor_LCD_test01.pyを実行するとサンプルプログラムが実行できます。

* italicc.py
* romans.py
* st7789.py
* Color_LCD_test01.py

左カラムのdevice以下のファイルがボードに書き込まれたファイルです。

時々このリストの更新に失敗することがあり、何度かUSBケーブルを抜き差ししているとうまくいきました。
（uPyCraftのバグ？）

![](/img/makepython-esp32-files.jpg)

### MicroPythonで独自のプログラムを書いてみる

サンプルで利用している液晶ディスプレイ用のライブラリを利用して、独自のプログラムを実行してみます。

サンプルには線画用のフォントデータしかないので、ビットマップフォントのデータを用意して私のIDの「INA」を表示してみました。

MicroPythonで愚直に書くとアニメーションなどの処理は少し遅いようでした。

まぁアニメーションのような速度が必要な処理はネイティブで書くのが良いのでしょう。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">MicroPythonで描画。<br>のんびりだねー <a href="https://t.co/57m6w2f4eP">pic.twitter.com/57m6w2f4eP</a></p>&mdash; ina_ani@2歳児のパパ (@ina_ani) <a href="https://twitter.com/ina_ani/status/1578967726076620800?ref_src=twsrc%5Etfw">October 9, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

上のMicroPythonで作ったものと同じようなプログラムをArduinoで作ったものがこちら。さすがにネイティブなので早いですね。

<blockquote class="twitter-tweet" data-conversation="none"><p lang="ja" dir="ltr">Arduinoで描画、流石にネイティブだとこのくらい早い <a href="https://t.co/EqvCXFlEX5">pic.twitter.com/EqvCXFlEX5</a></p>&mdash; ina_ani@2歳児のパパ (@ina_ani) <a href="https://twitter.com/ina_ani/status/1578967896524742656?ref_src=twsrc%5Etfw">October 9, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Arduinoで開発してみる

もともとESP32の開発はやっていたのでArduino IDEの設定は終わっていました。
液晶の制御のためにはLovyanGFXを使う手法が紹介されていたので、従います。このライブラリもM5Stackなどで利用したことがあったので特に難しいことはありませんでした。

プログラムはこちら https://github.com/Makerfabs/Makerfabs-MakePython-ESP32-Color-LCD/blob/master/Color_LCD_test/Color_LCD_test.ino

しかしArduino IDEでのコンパイルが「遅い！！」。ESP32のビルドが遅いのは知っているのですが、このプログラムはそれに輪をかけて遅い・・

最近リリースされたArduino IDEの2系やPlatformioを使うともう少し早くビルドできると思います。

![](/img/makepython-esp32-arduino.jpg)

## まとめ

まぁ普通のESP32の開発ボードなのですが、ディスプレイとESP32の組み合わせで何かを作りたい際にはちょうど良いものだと感じました。

ディスプレイは240*240と高解像度ですがコストパフォーマンスが良く、手元にあるとプロトタイピングの助けになると感じまました。
