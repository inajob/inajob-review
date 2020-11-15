---
title: 3DプリンタのXY軸移動の最新版Core XYの紹介
date: 2020-01-03T09:45:28.808Z
description: 3DプリンタのXY軸を制御する最近の方法の一つであるCore XYについて紹介します。
image: /img/corexy.png
tags:
  - 3Dプリンタ
---
[CORE XY EXPLAINED](https://hackaday.com/2019/11/12/core-xy-explained/)から発見。画像もここから転載。

3DプリンタのX,Y軸の制御の方法の一つであるCore XYについて紹介しています。

最もわかりやすい、X,Y軸をそれぞれのステッピングモータが担当する方式はCartesianと呼ばれており、またもう一つ、よく聞く方式にDeltaがあります。

CoreXYはこのどちらとも違う方式です。
ちょっとトリッキーに接続された2本のベルトを2個のステッピングモーターで引っ張ることで、X,Y軸の移動を実現しており、この方式のほうがCartesianよりも正確で、また速い速度で移動できるようです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/_ramiM3KHYE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
