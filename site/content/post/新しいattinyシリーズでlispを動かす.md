---
title: 新しいATtinyシリーズでLispを動かす
date: 2020-07-20T23:00:17.773Z
description: 新しいATtinyシリーズでLispを動作させる方法を紹介します。
image: /img/attinylisp.jpg
tags:
  - attiny
  - lisp
---
[ATtiny Running Lisp](http://www.technoblogy.com/show?2R5C)から発見。画像もここから転載。

新しいATTinyシリーズはATMega級のパフォーマンスのものもあります。
ということで、この記事ではATTiny3216で動作するLispインタプリタを作成しています。

といってもuLispという非常に小さな仕様のLispですが、いつもと違う言語でマイコンプログラミングをするのも面白そうです。
またインタプリタ方式であるため、試行錯誤には適しているでしょう。
