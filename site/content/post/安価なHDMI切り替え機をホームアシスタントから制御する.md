---
title: 安価なHDMI切り替え機をホームアシスタントから制御する
date: 2024-07-04T23:50:12.106142
description: 安価なHDMI切り替え機をホームアシスタントから制御する方法を紹介します
image: /img/安価なHDMI切り替え機をホームアシスタントから制御する.jpg
tags:
  - 赤外線
---
[Interfacing A Cheap HDMI Switch With Home Assistant](https://hackaday.com/2024/06/07/interfacing-a-cheap-hdmi-switch-with-home-assistant/)から発見。画像もここから転載。

安価なHDMI切り替え機をホームアシスタントから制御する手法を紹介しています。

安価なHDMI切り替え機の中には、赤外線で入力チャンネルを切り替えられる機能を持つものがありますが、その赤外線信号をESP32から出すことで、WiFi経由でHDMI切り替えできるようにしています。

赤外線信号を受け付ける機器をWiFi対応させるのは応用のききそうなテクニックです。



