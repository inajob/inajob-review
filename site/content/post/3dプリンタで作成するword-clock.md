---
title: 3Dプリンタで作成するWord Clock
date: 2019-06-02T06:20:08.427Z
description: 3Dプリンタで文字の表示を実現したWord Clockの作例を紹介します。
image: /img/3d-printed-word-clock.jpg
tags:
  - WordClock
  - 3Dプリンタ
  - Arduino
---
[Animated Word Clock](https://www.instructables.com/id/Matrix-Word-Clock/)から発見。画像もここから転載（CC BY-NC-SA By TechKiwiGadgets）

またまたWordClockです。

3Dプリンタで文字をくりぬいて、写真のように文字が浮かび上がるような効果を演出しています。

LEDの手前に製氷皿のように格子状のマス目のボードを用意し（これがグレーのフィラメントであるのも意味がありそう？）その底面にはアルファベットの形状でくりぬきを開けておきます。

さらにそれを覆うケースにはアルファベットの形状でエンボスが刻まれています。

この二重のアルファベット形状のくりぬきとエンボスにより、文字の投影を実現しています。
マイコンはArduino、LEDはよく使われるWS2812Bを使っています。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/_8R0CA6hrJg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
