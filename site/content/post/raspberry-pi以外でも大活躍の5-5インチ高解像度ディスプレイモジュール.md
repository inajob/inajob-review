---
title: Raspberry Pi以外でも大活躍の5.5インチ高解像度ディスプレイモジュール
date: 2021-08-05T01:57:31.646Z
description: Raspberry Pi用の5.5インチ高解像度ディスプレイモジュールの活用例を紹介します。
image: img/wareshare-5-5-cover.png
tags:
  - Banggood
  - RaspberryPi
---
この記事はBanggoodの提供でお届けします。

[以前紹介した](../../post/中国ecサイトbanggood/)ようにこのブログは[Banggood](https://jp.banggood.com/?p=0M092355466124202012)と提携させていただいており、今回紹介する[Wareshare® 5.5 Inch AMOLED HDMI Display](https://www.banggood.com/Wareshare-5_5-Inch-AMOLED-HDMI-Display-Capacitive-Touch-Screen-with-Tempered-Glass-Support-for-NVIDIA-Jetson-Nano-Raspberry-Pi-p-1526354.html?p=0M092355466124202012)も、[Banggood](https://jp.banggood.com/?p=0M092355466124202012)からいただいたものとなります。[Wareshare® 5.5 Inch AMOLED HDMI Display](https://www.banggood.com/Wareshare-5_5-Inch-AMOLED-HDMI-Display-Capacitive-Touch-Screen-with-Tempered-Glass-Support-for-NVIDIA-Jetson-Nano-Raspberry-Pi-p-1526354.html?p=0M092355466124202012))についてはBanggoodから紹介されましたが、自分も面白い製品であると感じたためこのレビューを引き受けたため、[Banggood](https://jp.banggood.com/?p=0M092355466124202012)が無理やりこの商品を押しているわけではなく、inajobの一押しアイテム！、という感じです。）

## Wareshare® 5.5 Inch AMOLED HDMI Display とは

いわゆるRaspberry Pi用のHDMIディスプレイです。特筆すべきは1080×1920という高解像度です。
加えて静電容量タッチセンサーにより、画面を触ることでPCの操作ができます。

![](img/wareshare-5-5-raspberrypi.jpg)

この高解像度でありながら、ディスプレイのサイズは5.5インチと小型で、まるでスマートフォンのディスプレイのようです。（というかスマートフォンのディスプレイを転用してこの製品を作ったように見えます。)

## 付属品

必要なものはだいたい入っています

![](img/wareshare-5-5-accessory.jpg)

* HDMIケーブル
* USBケーブル
* コの字型HDMI端子 2種
* コの字型USB端子 2種
* ディスプレイ固定用スペーサー

## Raspberry Piと接続してみる

まずは看板通りRaspberry Piにつなげてみます。説明書には「driver free」と書かれていますが、少しだけ設定が必要です。

手元にはRaspberry Pi3 B+があったのでそれで試しましたが、最新のRaspberry Pi 4Bや 小型のRaspberry Pi Zeroなどとも接続できるようです。

設定は[本家のWiki](https://www.waveshare.com/wiki/5.5inch_HDMI_AMOLED)に書かれていますが、`/boot/config.txt`に設定を少しだけ書く必要があります。

付属品のコの字型のHDMIと、USB端子を使うことで、「スマートフォン」とまではいきませんが、非常にコンパクトにRaspberry Piと接続することが出来ます。

![](img/wareshare-5-5-raspberrypi.jpg)

![](img/wareshare-5-5-raspberrypi-back.jpg)

![](img/wareshare-5-5-raspberrypi-side.jpg)

![](img/wareshare-5-5-raspberrypi-side2.jpg)

高解像度ディスプレイなので、かなり細かい情報を表示することが出来ます。

![](img/wareshare-5-5-raspberrypi-detail.jpg)

ただしRaspberryPiの標準のデスクトップはマウスで操作するように作られているため、タッチパネルでの操作は非常に困難でした。これ専用のアプリケーションを書く必要があるでしょう。

## WindowsノートPCと接続してみる

次にWindowsノートPCに接続してみました。なんと、何も設定せずとも認識してくれました。

ちょうどサブディスプレイが欲しかったので、手元の3Dプリンタを使ってノートPCのモニタの上に載せられるようにしてみました。

![](img/wareshare-5-5-winnote.jpg)
(動画はこちら https://www.youtube.com/watch?v=TLkA0RELQ1g )

![](img/wareshare-5-5-winnote2.jpg)
Twitterを表示してみた例（ちょっと小さくて読みづらいかな）

![](img/wareshare-5-5-winnote3.jpg)
裏面はこんな感じです。

シンデレラフィット！ と言いたくなるような使い勝手です。

個人的にはこのディスプレイはRaspberry Piとつなげるよりも、普段使いのノートPCのサブディスプレイにするのにちょうど良さそうです。

（一方手元のMacBookにHDMIで接続してみましたがうまく認識されませんでした。）

## 基板をよく見てみる

ディスプレイについては、全くの無知ですが、一応むき出しの基板に乗っているICを見てみました。

![](img/wareshare-5-5-circuit.jpg)

* TOSHIBA 358779XBG

  * 中国製品には珍しい東芝製のICです。これがHDMIの制御をしているようです。
* FT24C02A

  * EEPROMのようですが、何に使っているかはわかりませんでした
* GD32F350CBT6

  * 最近話題（？）のGigaDrive製のARMマイコンです。タッチパネルの制御をしているようです

汎用のARMマイコンが乗っているのがちょっと意外でした。うまく書き込みができると、タッチパネルの動作を変更できるかもしれません。

## まとめ

ちょっとお値段はしますが、この高密度で高解像度なディスプレイの価格としては妥当なものだと思います。

給電がUSBポートでできるという点も利用しやすくて良いです。

RaspberryPiを使ったリッチなガジェットのお供にはもちろん、普段使いのWindowsPCのサブディスプレイとしても常用できる、一石二鳥のガジェットだと感じました。

# クーポンコード

さて、ここまで紹介してきた[Wareshare® 5.5 Inch AMOLED HDMI Display](https://www.banggood.com/Wareshare-5_5-Inch-AMOLED-HDMI-Display-Capacitive-Touch-Screen-with-Tempered-Glass-Support-for-NVIDIA-Jetson-Nano-Raspberry-Pi-p-1526354.html?p=0M092355466124202012)ですが、今回Banggoodの提供という事で、<span style="color:red">**$96.99**</span>で購入できるクーポンを頂いています。

コード：
<span style="color:red">**BG0e4c34**</span> (8/31まで)

[Wareshare® 5.5 Inch AMOLED HDMI Display](https://www.banggood.com/Wareshare-5_5-Inch-AMOLED-HDMI-Display-Capacitive-Touch-Screen-with-Tempered-Glass-Support-for-NVIDIA-Jetson-Nano-Raspberry-Pi-p-1526354.html?p=0M092355466124202012)をカートに入れ、チェックアウト後にこのクーポンコードを入力することで割引を受けることが出来ます。

有効期限は**2021/8/31**なので、買いたい方はお早めにどうぞ！（加えて、在庫に限りがあると思うのでお早目に！）

* [Wareshare® 5.5 Inch AMOLED HDMI Displayの購入はこちら](https://www.banggood.com/Wareshare-5_5-Inch-AMOLED-HDMI-Display-Capacitive-Touch-Screen-with-Tempered-Glass-Support-for-NVIDIA-Jetson-Nano-Raspberry-Pi-p-1526354.html?p=0M092355466124202012)

[Banggood](https://www.banggood.com/marketing-jpcoupon/tid-8783.html?utmid=17856&p=0M092355466124202012)では、8月の「日本限定日替わりセール」ということで、ほかにも様々なガジェットを格安で販売しているようです。気になる人はのぞいてみてください。
