---
title: マトリクスLED表示機をセンサーとしても利用する
date: 2024-08-09T00:00:28.641034
description: マトリクスLED表示機をセンサーとしても利用する
image: /img/マトリクスLED表示機をセンサーとしても利用する.jpg
tags:
  - ドットマトリクスLED
  - センサー
  - HACK
---
[Programming Tiny Blinkenlight Projects With Light](https://hackaday.com/2024/08/01/programming-tiny-blinkenlight-projects-with-light/)から発見。画像もここから転載。

マトリクスLED表示機をセンサーとしても利用する作例です。

表示機として配置されたLEDを、逆に光センサーとして利用するテクニックです。
スマートフォンの画面にこの表示器を接した状態で、スマートフォンの画面を白黒に点滅させることでデータ転送を実現しています。

CH32V003に内蔵されたオペアンプを活用することで、この動作を実現しています。

表示機がセンサーにもなるというのは部品点数が減らせる点でも面白いです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/IHD3ji-F600" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



