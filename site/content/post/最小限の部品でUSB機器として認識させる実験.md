---
title: 最小限の部品でUSB機器として認識させる実験
date: 2023-05-23T23:03:48.701132
description: 最小限の部品でUSB機器として認識させる実験を紹介します。
image: /img/最小限の部品でUSB機器として認識させる実験.jpg
tags:
  - USB
  - HACK
---
[Minimal USB Device Connects With Just A Couple Of Resistors](https://hackaday.com/2023/05/09/minimal-usb-device-connects-with-just-a-couple-of-resistors/)から発見。画像もここから転載。

最小限の部品でUSB機器として認識させる実験です。
レギュレータと抵抗とDIPスイッチ、電解コンデンサだけで「不明なデバイス」とPCに認識させられるようです。

まだDIPスイッチのパターンに応じて、low-speedモードや通常のモードであることを伝えることが出来るため、この手法を応用するとフルでUSBスタックを実装しなくてもPCにUSBケーブル経由で情報を伝えることが出来るようです。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/VG5bWzEPfsg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

