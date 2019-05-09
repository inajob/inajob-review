---
title: 組み込みで動かすNode.jsとその評価ボード
date: 2019-05-09T23:00:59.647Z
description: Node.jsを組み込み機で動かすというプロダクトを紹介します
image: /img/neoniousone.jpg
---
[neonious one](https://www.neonious.com/neoniousOne)にて発見。画像もここから転載。

neonius oneはESP32-WROVERとLPC822を組み合わせたボードで、JavaScriptでの開発ができる。

ソフトウェア部分は[low.js](https://www.lowjs.org/)として公開されている。
ターゲットをESP32-WROVERに絞ることで、かなりパワフルな開発環境を実現している。（ESP-WROOM-32はメモリが少ない、WROVERは4MBのPSRAMが利用できる）
Webベースの開発環境も提供しており、かなり本格的にみえる。
