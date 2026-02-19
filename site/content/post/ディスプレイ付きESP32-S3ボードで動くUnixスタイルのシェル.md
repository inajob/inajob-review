---
title: ディスプレイ付きESP32-S3ボードで動くUnixスタイルのシェル
date: 2026-02-19T23:05:06.056716
description: ディスプレイ付きESP32-S3ボードで動くUnixスタイルのシェルの作例を紹介します
image: /img/ディスプレイ付きESP32-S3ボードで動くUnixスタイルのシェル.jpg
tags:
  - ESP32-S3
---
[BreezyBox: A BusyBox-Like Shell And Virtual Terminal For ESP32](https://hackaday.com/2026/02/06/breezybox-a-busybox-like-shell-and-virtual-terminal-for-esp32/)から発見。画像もここから転載。

ディスプレイ付きESP32-S3ボードで動くUnixスタイルのシェルの作例です。
Unixライクな使い慣れたコマンドはもちろん、WiFiの設定やHTTPサーバ、ELFローダーまで、スタンドアロンの端末として動作させるための様々な機能が実装されています。

適切にモジュール化されていることにより、この作例とは違うモジュールで動かすことも比較的簡単そうです。
写真で紹介しているのは、画面表示も含めた作例で。高速に描画するための工夫も施されています。

日本語ネイティブの自分としては、この端末でマルチバイト文字も表示できると嬉しいのですが・・、ちょっと改造が必要そうですね。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/wlDsaQgWCaI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



