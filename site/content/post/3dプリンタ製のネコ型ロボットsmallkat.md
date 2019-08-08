---
title: 3Dプリンタ製のネコ型ロボットSmallKat
date: 2019-04-13T06:26:52.432Z
description: 3Dプリンタ製のネコ型ロボットSmallKatを紹介します。
image: /img/small-katjpg.jpg
tags:
  - 3Dプリンタ
  - ロボット
  - ESP32
---
[SmallKat: An adorable dynamics oriented quadruped](https://hackaday.io/project/164727-smallkat-an-adorable-dynamics-oriented-quadruped)から発見。画像もここから転載。

SmallKatは3Dプリンタで作られた猫型のロボットです。
動画を見る限り、まだ動きがたどたどしいですが、止まっている写真を見る限りはかなり「猫っぽい」仕上がりとなっています。

コアとなるモジュールはESP32で、加えて16個のサーボモーター、IMUなどで構成されており、比較的安価なのが特徴のようです。

制御は遠隔で行いWiFi経由で指示を送るという設計なので、開発は普通にパソコン上のプログラムで行います。もう一つの方法としてはロボットにRaspberryPiを搭載し、そこから制御を行う、というのがあるようですが、開発段階においては前者のほうが便利だし、安い、とのことです。

確かにロボットを一気に作り上げるより、パソコンから簡単に試行錯誤できるようなプラットフォームを作るというのは良い方法だと感じました。

オープンソースで[公開されて](https://github.com/OperationSmallKat/SmallKat_V2)おり、さらには[キットも販売している](https://www.tindie.com/products/madhephaestus/smallkat-an-dynamics-oriented-robot-cat-kit/)ので、気になる方は作ってみてはどうでしょう？

<iframe width="100%" height="315" src="https://www.youtube.com/embed/0kAPtRiv94w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
