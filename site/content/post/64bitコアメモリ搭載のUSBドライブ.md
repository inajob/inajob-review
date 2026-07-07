---
title: 64bitコアメモリ搭載のUSBドライブ
date: 2026-07-07T23:10:35.310384
description: 64bitコアメモリ搭載のUSBドライブ
image: /img/64bitコアメモリ搭載のUSBドライブ.jpg
tags:
  - コアメモリ
  - ESP32
---
[Making A Magnetic Core Memory USB Drive](https://hackaday.com/2026/06/29/making-a-magnetic-core-memory-usb-drive/)から発見。画像もここから転載。

64bitコアメモリ搭載のUSBドライブ磁気コアメモリというのは、ドーナツ状の小さなフェライトコアにワイヤーを通し、電流による磁化の向きでデータを保持する記憶装置です。

この技術はデータを読み出す際にセルの磁化状態が反転してデータが消失する破壊読み出しという現象が起きるため、読み出し直後に再び同じデータを書き戻すための複雑な周辺回路や制御ロジックを必要とします。

この記事では、この懐かしい64ビットの磁気コアメモリをあえて現代のUSBドライブとして復活させた自作プロジェクトを紹介しています。

製作者は小型のCNCルーターで削り出した基板にフェライトコアを並べ、極細のワイヤーを1本ずつ手配線で通してメモリを自作したほか、安定したビット反転を行うために筐体内部をシリコンオイルで満たすというユニークな工夫を施しています。

このようなレトロな技術で作られたストレージを手配線で組み上げ、USBを介して現代のPCで実際にデータを読み書きできている点が面白いと感じました。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/IOtf85sHRlg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



