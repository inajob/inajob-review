---
title: 符号付き距離感数ベースのCADプログラミングフレームワーク
date: 2022-12-18T23:14:40.548589
description: 符号付き距離関数ベースのCADプログラミングフレームワークを紹介します。
image: /img/符号付き距離感数ベースのCADプログラミングフレームワーク.jpg
tags:
  - 3DCAD
---
[Taking Distance Based CAD To The Next Level](https://hackaday.com/2022/11/28/taking-distance-based-cad-to-the-next-level/)から発見。画像もここから転載。

コーディングで3D図形を定義する3DCADは、ある種の設計において非常に便利です。
代表的なものとしてOpenSCADがありますが、これはフィレットの処理をを扱うのが苦手です。

この記事で紹介するのはsigned distance functionsを使ったCADというもので直訳すると「符号付き距離関数ベースが使えるCAD」？

コーディングによる3D図形の設計ツールですが、うまくフィレットなども扱うことが出来るようです。

その実態はGo言語のライブラリで、これを実行することで3D図形のデータが出力されるようです。

[これを利用した開発環境](https://github.com/Yeicor/sdfx-ui) などもあるようで、コードで立体を設計するのが好きな人は試してみるとよさそうです。



