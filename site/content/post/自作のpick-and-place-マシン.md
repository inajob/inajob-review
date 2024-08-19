---
title: 自作のPick And Place マシン
date: 2022-01-27T22:00:42.068Z
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

さらに、電子書籍も作成されており、日本語での最新のノウハウを知るには非常に有用そうです。

<table style="border:solid 1px;">
<tr><td style="border:solid 1px;vertical-align:middle;margin:3px;">
<a href="https://www.amazon.co.jp/dp/B09MDXVLVL?&linkCode=li3&tag=inajob-22&linkId=64f9f0f56ef0a6eb271cba16be0a5b15&language=ja_JP&ref_=as_li_ss_il" target="_blank"><img border="0" src="//ws-fe.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B09MDXVLVL&Format=_SL250_&ID=AsinImage&MarketPlace=JP&ServiceVersion=20070822&WS=1&tag=inajob-22&language=ja_JP" ></a><img src="https://ir-jp.amazon-adsystem.com/e/ir?t=inajob-22&language=ja_JP&l=li3&o=9&a=B09MDXVLVL" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
</td>
<td>
<a href="https://www.amazon.co.jp/dp/B09MDXVLVL?&linkCode=li3&tag=inajob-22&linkId=64f9f0f56ef0a6eb271cba16be0a5b15&language=ja_JP&ref_=as_li_ss_il" target="_blank">
3Dプリンタを改造してチップマウンタを作ってみたら趣味の王様だった件
</a>
</td>
</tr>
</table>


<iframe width="100%" height="315" src="https://www.youtube.com/embed/GtZcnIEi710" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
