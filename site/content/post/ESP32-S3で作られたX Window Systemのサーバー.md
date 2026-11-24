---
title: ESP32-S3で作られたX Window Systemのサーバー
date: 2026-11-24T21:25:09.39875
description: ESP32-S3で作られたX Window Systemのサーバーの作例を紹介します
image: /img/ESP32-S3で作られたX Window Systemのサーバー.jpg
tags:
  - ESP32-S3
  - X11
---
[X Window System On The ESP32](https://hackaday.com/2026/11/13/x-window-system-on-the-esp32/)から発見。画像もここから転載。

X11（X Window System）は、LinuxやUNIX系のOSで昔から使われている「画面にウィンドウやボタンを表示し、マウスやキーボードの操作を受け付ける仕組み（ウィンドウシステム）」のことです。

この記事では、ESP32-S3搭載のタッチ液晶付き端末向けにX11のコアサーバを動かした「Woodland X11」が紹介されており、タッチ操作や二本指スクロールでxclockやxeyesなどの定番アプリを表示できる様子が取り上げられています。拡張機能を削った構成ですが、小さな画面端末をLinuxアプリの表示先として活かす発想があるので、細かい仕様や動作確認の内容は元記事を見てみてください。

小さなマイコンの画面側をXサーバにして別のマシンのアプリを表示できる点が面白いと感じました。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/asiljNp275Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



