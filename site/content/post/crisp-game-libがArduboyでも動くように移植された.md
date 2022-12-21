---
title: crisp-game-libがArduboyでも動くように移植された
date: 2022-12-21T22:49:08.184194
description: crisp-game-libがarduboyでも動くように移植されたたようです。
image: /img/crisp-game-libがArduboyでも動くように移植された.jpg
tags:
  - ゲーム
  - Arduboy
---
[crisp-game-lib-arduboy - OBONO’s Diary](https://obono.hateblo.jp/entry/20221126/1669437227)から発見。画像もここから転載。

[ABA](https://twitter.com/abagames) さんが作成した、ブラウザ用のミニゲーム作成ライブラリであるcrisp-game-libですが、[ご本人によりESP32などで動作するportable版が開発されています](https://inajob.github.io/iroiro-review/post/%E7%B5%84%E3%81%BF%E8%BE%BC%E3%81%BF%E7%94%A8%E3%81%AE%E3%82%B2%E3%83%BC%E3%83%A0%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%B3crisp-game-lib-portable/)。

しかし、いくらportableとはいってもESP32のようなパワフルなマイコンをターゲットにしたライブラリなので、Arduboyのような8bitのマイコンを搭載したゲーム機では動かすことはできませんでした。

そんなcrisp-game-libがついにArduboyにも移植されました。移植したのは[OBONO](https://twitter.com/OBONO) さん。
容量節約のテクニックの紹介も非常に参考になります。


