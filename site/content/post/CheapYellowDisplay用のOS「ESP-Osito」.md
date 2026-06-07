---
title: CheapYellowDisplay用のOS「ESP-Osito」
date: 2026-06-07T22:44:43.956394
description: CheapYellowDisplay用のOS「ESP-Osito」
image: /img/CheapYellowDisplay用のOS「ESP-Osito」.jpg
tags:
  - CYD
  - ESP32
---
[ESP-Osito Eschews Retrocomputing For Modern Code On Modern, Equivalent Hardware](https://hackaday.com/2026/05/29/esp-osito-eschews-retrocomputing-for-modern-code-on-modern-equivalent-hardware/)から発見。画像もここから転載。

通常、ESP32のプログラムはコンパイル時にバイナリへと変換され、Flashメモリ上に固定的に焼き付けられることで電源投入と同時に実行されます。そのため、実行時に動的にプログラムを読み込んで動作を切り替えるという動きを実現するためには工夫が必要です。

この記事で紹介されているESP-OstioではSDカード内に保存された個別のアプリケーションファイルを、実行時にメモリ上の固定アドレスへ直接ロードし、プログラムカウンタをその先頭へジャンプさせるという、いわばベアメタルに近いローダーを自作しています。ファイルシステムから読み取ったバイナリをそのまま実行可能なコードとしてメモリへ配置する手法は、複雑な抽象化を省いた非常に軽量な仕組みです。

限られたメモリ空間でプログラムを入れ替えるために、OSのローダー機能をシンプルに自作してSDカードを「ストレージ付きの実行媒体」のように扱っている点が興味深く、応用範囲が広い技術だと思います。




