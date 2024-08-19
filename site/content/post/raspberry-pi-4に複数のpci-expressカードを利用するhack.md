---
title: Raspberry Pi 4でPCI Expressカードを利用するさらなるHACK
date: 2019-09-30T23:00:44.221Z
description: Raspberry Pi 4でPCI Expressカードを利用するHACKの続編を紹介します。
image: /img/raspi-multi-pci-express.jpg
tags:
  - Raspberry Pi 4
---
[Raspberry Pi 4 PCI Express: It actually works! USB3, SATA… GPUs?](http://labs.domipheus.com/blog/raspberry-pi-4-pci-express-it-actually-works-usb-sata-gpu/)から発見。画像もここから転載。

以前[Raspberry Pi 4にPCI Expressのボードを接続する裏技
](https://inajob.netlify.com/post/raspberry-pi-4%E3%81%ABpci-express%E3%81%AE%E3%83%9C%E3%83%BC%E3%83%89%E3%82%92%E6%8E%A5%E7%B6%9A%E3%81%99%E3%82%8B%E8%A3%8F%E6%8A%80/)を紹介しましたが、今回はさらに上をいくHACKを紹介します。

前回のHackではうまくデバイスを認識できていませんでしたが、この記事では、デバイスツリーのバイナリを逆コンパイルして改変することで、デバイスの認識に成功し、USB3カードを使ってキーボードやマウスを動かすことに成功しています。

しかもこのHackではPCI Expressの複数搭載したスイッチボードを利用しています。これにより複数のPCI Expressのボードを利用することができます。

SATAのコントローラも認識はしているようですがドライバないので動いていないようです、さらにグラフィックカードも動作を検証しているところのようです。
