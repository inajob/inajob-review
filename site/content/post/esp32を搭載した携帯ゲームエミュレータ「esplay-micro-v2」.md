---
title: ESP32を搭載した携帯ゲームエミュレータ「ESPlay Micro V2」
date: 2022-02-27T23:30:43.481Z
description: ESP32を搭載した携帯ゲームエミュレータ「ESPlay Micro V2」のレビュー記事です
image: /img/esplay-micro-v2-cover.jpg
tags:
  - ESP32
  - ゲーム機
  - Makerfabs
---
この記事はMakerfabsの提供でお届けします。

今回紹介する[ESPlay Micro V2](https://www.makerfabs.com/esplay-micro-v2.html)は[Makerfabs](https://www.makerfabs.com/)から提供いただいたものです。

（ですが、[ESPlay Micro V2](https://www.makerfabs.com/esplay-micro-v2.html)をレビューしたい！と言ったのは自分なので、[Makerfabs](https://www.makerfabs.com/)が無理やりこの商品を押しているわけではなく、inajobの一押しアイテム！、という感じです。）

## ESPlay Micro V2とは

[ESPlay Micro V2](https://www.makerfabs.com/esplay-micro-v2.html)はオープンソースの携帯ゲーム機です。

![](../../img/esplay-micro-v2-audio.jpg)

![](../../img/esplay-micro-v2-back.jpg)

コアとなるマイコンはESP32で、様々なレトロゲームのエミュレータが動作する、本格的なゲーム機です。

また、このゲーム機は以前紹介した[ESP32を搭載した携帯ゲーム機「ESPlay Micro」
](../esp32%E3%82%92%E6%90%AD%E8%BC%89%E3%81%97%E3%81%9F%E6%90%BA%E5%B8%AF%E3%82%B2%E3%83%BC%E3%83%A0%E6%A9%9Fesplay-micro/)の後継機種です。

## 仕様

* ESP32-WROOBER

  * という事で技適もあります。日本で使っても安心。
* 十字キー+ A,B, L,R, Start, Selectボタン
* I2C接続IOエキスパンダIC PCF8574
* I2S DAC IC UDA1334A (PAM8403?)
* イヤホンジャック端子
* USBシリアル変換IC CH340G
* 320*240 TFT ディスプレイ
* アクリル板による筐体
* MicroSDカードスロット搭載（MicroSDカードも8GBのものが同梱されていました）
* 拡張用I2C端子
* 800mAh LiPo電池
* 充電IC TP4054
* 電源スイッチ
* スピーカーは基板上にパターンはあるが、スピーカーが実装されていない

さらに細かい仕様は[公式サイト](https://hackaday.io/project/166707-esplay-micro)を見てみてください

![](../../img/esplay-micro-v2-inside.jpg)



## 遊んでみる

※SDカードに謎のROMファイルが入っている場合があります。内容によっては違法なものもあるかもしれないので、利用せず削除してください。

以下のゲームのエミュレータが搭載されています

* ファミコン
* ゲームボーイ
* ゲームボーイカラー
* セガマスターシステム
* ゲームギア
* Color Vision

また、オーディオプレイヤーも搭載されています。

設定画面からAP Modeにすることで、WiFiのアクセスポイントとしてふるまい、そのWiFiに接続することでブラウザ経由でROMファイルやオーディオファイルを簡単に転送できます。

ファミコンのROMとして[ブレイドバスター(BLADE BUSTER)](http://hlc6502.web.fc2.com/Bbuster.htm)を入れてみました。

<blockquote class="twitter-tweet" data-conversation="none"><p lang="ja" dir="ltr">ブレイドバスターで遊んでる様子<br>(スピーカーはパターンがあるが実装されてない。) <a href="https://t.co/RcchdepXR2">pic.twitter.com/RcchdepXR2</a></p>&mdash; ina_ani@1歳10ヶ月児のパパ (@ina_ani) <a href="https://twitter.com/ina_ani/status/1497754152122093568?ref_src=twsrc%5Etfw">February 27, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

![](../../img/esplay-micro-v2-blade-buster.jpg)

普通に遊べます。

ゲームボーイのソフトとしては[LSDj](https://www.littlesounddj.com/lsd/index.php)を入れてみました。

<blockquote class="twitter-tweet" data-conversation="none"><p lang="ja" dir="ltr">LSDjも動く！これでどこでも作曲できるね！ <a href="https://t.co/GhToN8oyWT">pic.twitter.com/GhToN8oyWT</a></p>&mdash; ina_ani@1歳10ヶ月児のパパ (@ina_ani) <a href="https://twitter.com/ina_ani/status/1497754379046518790?ref_src=twsrc%5Etfw">February 27, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

![](../../img/esplay-micro-v2-blade-lsdj.jpg)

これはゲームボーイで動作する作曲ソフトです。[ESPlay Micro V2](https://www.makerfabs.com/esplay-micro-v2.html)も持ち運びに便利なので、これで手軽な作曲マシンとして利用することができます。

## ハードウェア面での見どころ

### ケース

レーザーカットされたアクリル板2枚をスペーサで挟んでサンドイッチにしています。
よく見る構造ですが、強度はそこそこありますが、横はがら空きなので、ケースとしては頼りないです。

### スイッチ

ちょっと硬めのいかにも中国製のタクトスイッチですが、ゴムキャップが搭載されているおかげで、そこまで悪い操作性ではないです。

自分でゲーム機を作るときもこのテクニックは役立ちそうです。

### バッテリー

RaspberryPiベースのエミュレータと比べると省電力なので、800mAhバッテリーでも結構長時間遊べます。

## エミュレータ以外の遊び方

ちょっとまだ試していないのですが、ESP32を搭載した開発ボードとしても様々な利用方法がありそうです。

* MicroPython
* [Arduino](https://hackaday.io/project/166707-esplay-micro/log/197610-arduino-available)

I2C端子もあるので、センサーを外付けすることもできそうです。

## まとめ

ESP32を使ったゲーム端末として十分な機能を持った製品だと感じました。利用できるエミュレータの種類は比較的少ないので、エミュレータを目的で買う時は注意が必要です。

またESP32を元としたゲーム開発環境としても簡単に利用できそうです。価格も安いので、この製品にオリジナルゲームを同梱して再販するみたいなことも夢では無いかも？と思いました。

少し似たものとしてM5Stackなどががありますが、ゲームに特化した形状である点が大きな違いです。

原価を考えてもこの価格はありえない安さなので、気になる人は是非買ってみると良いと思います。
