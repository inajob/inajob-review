---
title: ESP32用のJavaScript OS 「KryonOS」
date: 2026-10-08T22:30:49.358338
description: ESP32用のJavaScript OS 「KryonOS」
image: /img/ESP32用のJavaScript OS 「KryonOS」.jpg
tags:
  - ESP32
  - JavaScript
  - Duktape
  - CYD
---
[A JavaScript OS For The ESP32](https://hackaday.com/2026/09/23/a-javascript-os-for-the-esp32/)から発見。画像もここから転載。

ESP32はパワフルなマイコンで、この上でOSのようなものを動かす試みは数多くあります。

この記事では、ESP32上で動作するグラフィックGUIを備えたJavaScriptベースのOS「KryonOS」が紹介されています。DuktapeをコアにしたJavaScript実行環境と独自描画ライブラリを統合し、タッチパネル付き液晶を搭載した各種ESP32ボード上で、アプリの動的ダウンロードや実行を可能にしています。

C++のツールチェーンを用意せずにJavaScriptだけで画面UIや周辺機器制御をまとめられるアプローチは手軽で面白いと感じました。



