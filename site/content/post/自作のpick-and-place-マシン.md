---
title: 自作のPick And Place マシン
date: 2021-12-13T11:21:02.960Z
description: OpenPNPを利用して作られた自作のPick And Placeマシンの作例を紹介します。
image: /img/open-soure-pick-and-place-machine.jpg
tags:
  - DIY
  - OpenPNP
---
[OPEN SOURCE PICK AND PLACE HAS A $450 BOM COST](https://hackaday.com/2020/05/11/open-source-pick-and-place-has-a-450-bom-cost/)から発見。画像もここから転載。

表面実装基板を作るようになると、様々な機材が欲しくなりますが、 Pick And Placeマシンもその一つです。

といいつつ、このマシン、非常に高いので、個人で買うのは難しいです。

しかしオープンソースの[OpenPNP](https://github.com/openpnp/openpnp)を参考にすると自分でもこのマシンを作ることが出来るようです。

必要なのは部品のフィーダーと、X,Y,Z軸に駆動するヘッド、部品を吸いつけるためのバキューム装置です。

部品の認識は画像処理により行いますが、この部分は前述のOpenPNPが利用できるようです。

日本だと最近は [@akita11](https://twitter.com/akita11)さんが挑戦しており、[その記録はnoteにまとめられています。](https://note.com/akita11/n/ne17326245943)

<iframe width="100%" height="315" src="https://www.youtube.com/embed/GtZcnIEi710" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
