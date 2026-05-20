---
title: JLCPCBの部品番号からKiCADのデータを作るWebサービス
date: 2026-05-20T22:50:35.107484
description: JLCPCBの部品番号からKiCADのデータを作るWebサービスを紹介します
image: /img/JLCPCBの部品番号からKiCADのデータを作るWebサービス.jpg
tags:
  - JLCPCB
  - KiCAD
---
[JLC2KiCad Web UI](https://jlc2kicad-webui.manus.space/)から発見。画像もここから転載。

JLCPCBの部品番号からKiCADのデータを作るWebサービスです。
JLCPCBの部品にはEasyEDAというオンラインCAD向けの部品データが関連付けられていますが、オープンソース基板CADの定番であるKiCADで利用するためのデータは用意されていません。

このWebサービスではJLCPCBの部品番号を与えると裏でEasyEDAのデータを取得しそれをKiCAD用に変換してくれるというものです。
仕掛けとしては https://github.com/tomorrow56/JLC2KiCad_lib を実行してEasyEDA用のデータをKiCAD用に変換しているようです。

基板CAD用のフットプリントを0から作るのは結構面倒なので、こういう変換ツールがあると非常に助かります。




<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">JLCPCB(EasyEDA)のパーツからKiCadのパーツを生成するWebUI、ここで一旦完成とします<a href="https://t.co/mby9xApB94">https://t.co/mby9xApB94</a></p>&mdash; tomorrow56 (@tomorrow56) <a href="https://twitter.com/tomorrow56/status/2055045655085842574?ref_src=twsrc%5Etfw">May 14, 2026</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



