---
title: 電解コンデンサを64個並べて8バイトのDRAMを作る
date: 2026-07-05T23:40:02.278301
description: 電解コンデンサを64個並べて8バイトのDRAMを作る
image: /img/電解コンデンサを64個並べて8バイトのDRAMを作る.jpg
tags:
  - 電解コンデンサ
---
[Dynamic RAM From First Principles](https://hackaday.com/2026/06/22/dynamic-ram-from-first-principles/)から発見。画像もここから転載。

DRAMというのは、コンデンサに蓄えた電荷の有無で1と0の情報を記憶する仕組みですが、時間が経つと電気が漏れてデータが消えてしまうため、定期的にデータを再書き込みするリフレッシュ動作が必要となるメモリのことです。

この記事では、市販のメモリを使わず、電解コンデンサやダイオード、トランジスタといった個別のディスクリート部品のみを組み合わせて、合計8バイト（64ビット）のDRAMを原理から完全自作したプロジェクトを紹介しています。

現代のICチップ内では目に見えないほど微細なコンデンサが使われますが、ここではあえて巨大な電解コンデンサを使用することで、リフレッシュが必要になる電荷の蓄積プロセスやアドレッシングの仕組みを物理的な回路として可視化しています。

集積回路のブラックボックスをあえてディスクリート部品に分解して再現するアプローチは、仕組みの根本的な理解につながる点が面白いと感じました。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/lYUuGf6b0IQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



