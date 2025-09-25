---
title: ESP32で動くマインクラフトサーバー
date: 2025-09-25T23:03:59.087166
description: ESP32で動くマインクラフトサーバー
image: /img/ESP32で動くマインクラフトサーバー.jpg
tags:
  - ESP32
---
[ESP32 Hosts Functional Minecraft Server](https://hackaday.com/2025/09/13/esp32-hosts-functional-minecraft-server/)から発見。画像もここから転載。

ESP32はかなりパワフルなマイコンですが、それでもPCに比べると全然性能は低いです。
そんなESP32を使ったマインクラフトサーバーを作ったというのがこの例です。

さすがにフルスペックは難しく、様々な方法で処理の最適化や簡素化を行うことでこれを実現しているようです。

Minecraftのプロトコルは有志により解析されているようで、これを利用することでクライアントはMincreft本家のものを使い、サーバだけこのような別の実装に取り換えることが可能なようです。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/p-k5MPhBSjk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



