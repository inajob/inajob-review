---
title: 水道メーターの表示をカメラで取得しデータをWiFiで送信する
date: 2019-09-08T02:46:44.808Z
description: ESP8285を使って水道メーターのデータをWiFiで送信する作例を紹介します。
image: /img/water-mater.png
tags:
  - ESP8265
  - 3Dプリンタ
---
[Integrating my Neptune Water Meter with HomeAssistant](https://medium.com/@trumpetgod/integrating-my-neptune-water-meter-with-home-assistant-896712a8c893)から発見。画像もここから転載。

水道メーターの値を読み取ってWiFiで送信する、というお題に対して、画像認識で答えを出したのがこの記事です。

メモリがそこそこあるESP8265を使い、カメラモジュールから来た画像を解析しています。解析のためにいくつかの方法を試しているようですが、最終的には数字部分の画素による決定木を生成しAIもどきを作ることで対応したようです。

非常にアナログで泥臭い方法ですが、プロトコルもわからない機器のセンシングをする際には意外と役に立ちそうなテクニックだと感じました。
