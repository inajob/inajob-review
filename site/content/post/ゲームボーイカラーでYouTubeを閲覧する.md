---
title: ゲームボーイカラーでYouTubeを閲覧する
date: 2026-07-09T23:54:12.019989
description: ゲームボーイカラーでYouTubeを閲覧する事例を紹介します
image: /img/ゲームボーイカラーでYouTubeを閲覧する.jpg
tags:
  - ゲームボーイ
  - ESP32-C6
  - RP2350
---
[Watch YouTube On A Game Boy Color With A Special Cartridge](https://hackaday.com/2026/06/26/watch-youtube-on-a-game-boy-color-with-a-special-cartridge/)から発見。画像もここから転載。

ゲームボーイカラーというのは、160×144ピクセルの限定された液晶画面を持ちながらも、カートリッジバスを介して外部ハードウェアを直接接続できる仕様から、現代でも自作のオリジナルカートリッジを作って機能を拡張する事例を見かけます。

この記事では、Wi-Fi通信用のESP32-C6とメイン制御を担うRP2350Bを搭載した自作カートリッジを使い、ゲームボーイカラーでYouTube動画をストリーミング再生する試みを紹介しています。

ホストPC側で動画のダウンロードと変換を行い、マイコンを経由してゲームボーイカラーの画面へデータを送り出す構成になっており、詳細なシステム構成や実際の動作デモが気になる方は本文を読むことをお勧めします。

レトロゲーム機の厳しいハードウェア制限に対して、外部のマイコンとPCによる処理を組み合わせて力技で解決するアプローチが面白いと感じました。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/_GlYnN9JK1k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



