---
title: とてもかわいいLISPポケコン
date: 2019-02-09T02:17:04.566Z
description: ATmega1284製のとてもかわいいLISPポケコンを紹介します
image: /img/lisp-badge.jpg
tags:
  - atmega1284
---
[Lisp Badge](http://www.technoblogy.com/show?2AEE) にて発見。

フルキーボード付きのLISP端末。CPUはATMega1284
タイトルにある”Badge”というのは、海外のIT系カンファレンスなどで流行っているらしい、こういう手のひらサイズのガジェットのことらしい。（カンファレンス中首から下げたり、シャツにバッジみたいに取り付けたりして、自己アピールするためのものらしい。）

日本ではbuildersconの[電子名札](https://blog.builderscon.io/entry/2018/08/09/100000)が記憶に新しい

![](/img/denshi-nafuda.png)

![](/img/lisp-badge.jpg)

ディスプレイは256x64のOLEDを利用している。（一般的に普及している128x64のものより高くなるが、こっちのほうがいい感じだったので使っているとのこと）

電源は単四電池サイズのLiPoバッテリを使っている。これだと3.7Vで、動作範囲外だが16MHzでCPUを動かしている。

GPIOを操作する命令も搭載されているので、これを使って電子部品を制御することもできそう。
回路図も余すことなく公開されているので、似たようなものを作りたい人には参考になるだろう。
