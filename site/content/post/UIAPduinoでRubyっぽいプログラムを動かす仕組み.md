---
title: UIAPduinoでRubyっぽいプログラムを動かす仕組み
date: 2026-06-10T23:06:39.920566
description: UIAPduinoでRubyっぽいプログラムを動かす仕組み
image: /img/UIAPduinoでRubyっぽいプログラムを動かす仕組み.jpg
tags:
  - UIAPduino
  - Ruby
---
[UIAPruby Lab | UIAPduino](https://tarosay.github.io/uiap-hid-web/uiapruby.html)から発見。画像もここから転載。

UIAPduinoとは、CH32V003という安価かつ低スペックなマイコンを搭載した開発ボードであり、この種のマイコンを用いた電子工作では、メモリ資源の制限から一般的にC言語やC++を用いて開発を行うのが定石です。

ここで紹介するUIAPrubyというのは、UIAPduinoのメモリ容量の少なさを補うため、SDカード上のプログラムを逐一読み込んで実行する仕組みや、Ruby公式パーサーであるPrismをブラウザ上で動かし、Ruby風のDSLを抽象構文木（AST）へと変換して軽量バイトコード化する手法などを採用した開発環境です。

PC側に複雑な開発環境をインストールすることなく、ブラウザのみでコードの解析からマイコンへの書き込み、実行までを完結させる新しい開発体験を提示しています。

ブラウザのJavaScript環境で公式の解析器を利用し、Rubyの構文を模した独自のDSLを安価なマイコンで動かす仕組みは、メモリ制約がある環境でも高水準なコード記述を可能にする応用範囲の広い技術だと感じました。


