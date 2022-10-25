---
title: 3DプリンタのExtruderを斜めにして回転するようにした4軸3Dプリンター
date: 2022-10-25T23:20:42.299686
description: 3DプリンタのExtruderを斜めにして回転するようにした4軸3Dプリンターの作例を紹介します
image: /img/3DプリンタのExtruderを斜めにして回転するようにした4軸3Dプリンター.jpg
tags:
  - 3Dプリンタ
  - HACK
---
[RotBot Adds A Extra Dimension To 3D Printing, With A Twist](https://hackaday.com/2022/10/09/rotbot-adds-a-extra-dimension-to-3d-printing-with-a-twist/)から発見。画像もここから転載。

よく見かける3DプリンタはX,Y,Zの3軸です。
それゆえにオーバーハングなど、造形にいくらかの制限がかかります。

軸を増やすことでより自由な造形を行うことが出来、産業用では3軸以上の工作機などもよく見かけます。

この記事で紹介しているのは市販の3Dプリンタを改造して4軸化した作例です。

4軸目を追加する改造は様々ありますが、この作例では、ヘッド部分を45度傾けたうえでこれを回転させることで1軸追加しています。

この手法の特徴はプリントヘッド部分のみ改造すればよいので比較的簡単に実現できるという点です。

スライサーは独自に開発する必要がありますが、この変形であれば比較的簡単に既存のスライサーの入出力に前処理・後処理することで実現できるようです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/7LRWuccMGjc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
