---
title: 簡単に制御できる7セグLEDモジュール
date: 2019-02-16T01:49:26.443Z
description: 意外と面倒な7セグLEDの制御を簡単にするモジュールを紹介します
image: /img/addressable-7seg.png
---
[Addressable 7-Segment Display
](https://shop.idlehandsdev.com/products/addressable-7-segment-display)
で発見。
残念ながらもうキャンペーン期間は終わってしまっている。

しかし、プロジェクトは[オープンソース化](https://github.com/IdleHandsProject/addr_7seg)されているので、どんなものかはわかります。

これはフルカラーLEDの制御でよく使われているWS2811を使って、7セグメントLEDを制御するためのボードです。WS2811はデイジーチェーンによる接続ができるため、写真のように、次々モジュールをつなげることで桁を増やすことができます。

WS2811をフルカラーLED以外の制御に使うというのはもしかしたらほかにも応用が聞くのでは?と思いました（あと安そう [10PCS WS2811S SOP-8](http://s.click.aliexpress.com/e/jk3MkCo) 1つ9円くらい？）
