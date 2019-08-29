---
title: ビデオに文字をオーバーレイするOSDのオープンソース実装
date: 2019-08-29T09:13:44.368Z
description: ビデオに文字をオーバーレイするOSDのオープンソース実装であるtinyOSDを紹介します。
image: /img/tinyosd.jpg
---
[tinyOSD & tinyFINITY – a tiny opensource video tx with full graphic OSD](https://fishpepper.de/2019/03/11/tinyosd-tinyfinity-a-tiny-opensource-video-tx-with-full-graphic-osd/)から発見。画像もここから転載。

OSDというビデオに文字をオーバーレイをする仕組みの紹介です。一般的にこの手のOSDを実現するためには専用のチップ（MAX7456など）を使うことが多いのですが、この記事ではそれを汎用的なマイコンで実現しています。

その理由としてMAX7456は古いチップで非常に電気を食いチップが熱くなることを挙げています。

ここで使っているのはSTM32F3です。オープンソースになっており、フォントも好きに差し替えられるようなので、日本語版なども作ってみると面白いかもしれません。
