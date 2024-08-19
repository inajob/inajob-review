---
title: Raspberry Pi PicoのためのJavaScriptエンジン
date: 2021-09-28T13:00:36.014Z
description: Raspberry Pi PicoのためのJavaScriptエンジン「Kaluma」を紹介します。
image: /img/kaluma.png
tags:
  - RaspberryPiPico
  - JavaScript
---
[Kaluma](https://kaluma.io/)から発見。画像もここから転載。

Rasberry Pi Picoは比較的パワフルなマイコンモジュールです。開発には通常C/C++言語を用いますが、このスペックがあればスクリプト言語も動作させることが出来ます。

KalumaはRaspberryPiPicoの用のJavaScriptランタイムです。ブラウザ上で動作するIDEも提供されており、まるでWebサービスを開発するかのようにマイコンボードのプログラミングができます。

ランタイムコアには[JerryScript](http://jerryscript.net/)を用いているようです。
