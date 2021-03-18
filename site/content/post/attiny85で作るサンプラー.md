---
title: ATTiny85で作るサンプラー
date: 2021-03-18T11:00:32.713Z
description: 4つのボタンを押すとそれぞれに対応したサウンドが再生されるサンプラーの作例です。
image: /img/foursampleplayer.jpg
tags:
  - attiny85
  - 音楽
---
[Four Sample Player](http://www.technoblogy.com/show?2XJD)から発見。画像もここから転載。

ATTiny85を使って作られた4音源のサンプラーです。
ATTiny85のメモリに4つの音源は入りきらないので、4MByteのフラッシュメモリICと組み合わせて作成されています。これにより8kHzの音源であれば44秒まで格納することが出来ます。

ATTiny85はかなり機能が限定されたICですが、必要な機能を別ICとして組み合わせる事で様々な用途に使用できる良い例です。
