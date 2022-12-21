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

[ABA](https://twitter.com/abagames) さんが作成した、ブラウザ用のミニゲーム作成ライブラリであるcrisp-game-libですが、[ご本人によりESP32などで動作するportable版が開発されています](../../post/組み込み用のゲームエンジンcrisp-game-lib-portable)。

しかし、いくらportableとはいってもESP32のようなパワフルなマイコンをターゲットにしたライブラリなので、Arduboyのような8bitのマイコンを搭載したゲーム機では動かすことはできませんでした。

そんなcrisp-game-libがついにArduboyにも移植されました。移植したのは[OBONO](https://twitter.com/OBONO) さん。
容量節約のテクニックの紹介も非常に参考になります。


