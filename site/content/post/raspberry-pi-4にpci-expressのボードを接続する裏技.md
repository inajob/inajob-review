---
title: Raspberry Pi 4にPCI Expressのボードを接続する裏技
date: 2019-08-04T23:00:40.999Z
description: Raspberry Pi 4にPCI Expressのボードを接続する裏技を紹介します。
image: /img/raspberry-pi-4-get-pciexpress.jpg
tags:
  - Raspberry Pi
---
[Raspberry Pi 4 B+ - PCI Express](http://mloduchowski.com/en/blog/raspberry-pi-4-b-pci-express/)から発見。画像もここから転載。

Raspberry Pi 4は様々な面で性能が向上していますが、この記事で扱っているのはUSB3.0のコントローラ部分です。
Raspberry Pi 4ではUSB3.0はPCI Expressのインターフェースで接続されています。PCI Expressのスロットが出ているわけではありませんが、制御チップはボード上にあります。

そこで、この記事ではPCI Expressの制御チップから無理やり配線を変更して、PCI Expressのライザーカードに接続し、SASコントローラボードをつなげています。

このライザーカードはUSB3.0のケーブルを使ってPCI Expressの信号を伝えるもののようで、つまりPCI-ExpressとつながっているUSB3.0のコントローラのICをひっぺがして、PCI-Expressの信号をそのままUSB3.0の端子に出るようにすれば、このライザーカードを経由してPCI Expressボードが使えるようになるという算段です。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/_4YRZRCE5z4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
