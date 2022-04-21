---
title: HDMIのI2C端子をOLEDにつなげてディスプレイにするHACK
date: 2022-04-21T22:10:56.692883
description: HDMIの本来制御用のI2C端子をOLEDにつなげてディスプレイとして利用するというHACK
image: /img/HDMIのI2C端子をOLEDにつなげてディスプレイにするHACK.jpg
tags:
  - HDMI
  - OLED
  - I2C
---
[DDC OLED](https://mitxela.com/projects/ddc-oled)から発見。画像もここから転載。

HDMIには制御信号をやり取りするためのI2Cのピンがあります。
この記事ではこのI2Cの信号を使いOLEDを制御し、小さなディスプレイとして利用しています。

PCの画面を出すためにxrandrを使って仮想ディスプレイの設定を行っているようです。

5~10FPS程度で画面が更新できるようです。
https://hackaday.com/2022/04/01/making-your-own-technically-hdmi-oled-monitor/

<iframe width="100%" height="315" src="https://www.youtube.com/embed/8UbVgUFfN8U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

