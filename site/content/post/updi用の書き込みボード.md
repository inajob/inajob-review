---
title: UPDI用の書き込みボード
date: 2019-11-11T09:52:57.053Z
description: 新しいATtinyに書き込むために使えるUPDI書き込み器の作例を紹介します。
image: /img/updiprogrammerstick.jpg
tags:
  - 開発ボード
  - ATtiny
---
[UPDI Programmer Stick](http://www.technoblogy.com/show?2OJT)から発見。画像もここから転載。

新しいATtinyシリーズはブートローダーの書き換え方法が今までのICSPとは違いUDPIというプロトコルになっています。

一度書き込んでArduino化してしまえばそれ以降はシリアルで書き換えられる点は今までと同じですが、初回はこのUDPIを使ってブートローダを書き換える必要があります。

そこで必要となるのがUDPIライターです。もちろん公式のライターを使うというのが一番良いのでしょうが、この記事ではUDPIライターを自作しています。

UDPIライターの実体はArduino UNO互換の基板で、ソフトウェアとしては、[jtag2udpi](https://github.com/SpenceKonde/jtag2updi)を使っています。

つまり手元にArduino UNOがあればだれでも比較的簡単にUDPIライターが作れるということです。
とはいえ、この記事で紹介されているライターは非常にコンパクトで、新しいATTinyの開発のお供として非常に魅力的です。
