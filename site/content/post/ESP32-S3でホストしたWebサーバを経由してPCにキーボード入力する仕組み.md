---
title: ESP32-S3でホストしたWebサーバを経由してPCにキーボード入力する仕組み
date: 2026-02-15T21:55:21.495357
description: ESP32-S3でホストしたWebサーバを経由してPCにキーボード入力する仕組みを紹介します
image: /img/ESP32-S3でホストしたWebサーバを経由してPCにキーボード入力する仕組み.jpg
tags:
  - ESP32-S3
---
[A Keyboard For Anything, Without A Keyboard](https://hackaday.com/2026/02/04/a-keyboard-for-anything-without-a-keyboard/)から発見。画像もここから転載。

ESP32-S3でホストしたWebサーバを経由してPCにキーボード入力する仕組みです。

ESP32-S3はUSBケーブルでPCと接続され、キーボードとして認識されます。
さらにWiFiを利用してWebサーバとしてふるまうので、スマートフォンなどでこのWubサーバに接続します。
そして、Webブラウザでテキストエリアに文字を入力することで、PCにキー入力を送り込むことが出来ます。

これだけでは単なる実験ですが、どんな活用方法があるか考えてみるのも面白いです。




