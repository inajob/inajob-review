---
title: Raspberry Pi Pico WでPCMCIAで動作するWiFiカードの作例
date: 2022-10-17T23:12:00.322964
description: Raspberry Pi Pico WでPCMCIAで動作するWiFiカードの作例を紹介します
image: /img/Raspberry Pi Pico WでPCMCIAで動作するWiFiカードの作例.jpg
tags:
  - Raspberry Pi Pico W
  - PIO
  - PCMCIA
---
[Pi Pico W Does PCMCIA, Gets This IBM PC110 Online](https://hackaday.com/2022/09/25/pi-pico-w-does-pcmcia-gets-this-ibm-pc110-online/)から発見。画像もここから転載。

最近では見なくなりましたが、かつてノートパソコンには「PCカード」などと呼ばれる拡張端子がありました。

クレジットカードサイズの拡張カードを差し込むことで、ストレージやネットワーク機能を追加することが出来るものです。

この記事ではこのPCカードのインターフェースをRaspberry Pi Pico Wで喋らせるというものです。
こういったパソコンのバスの制御はタイミングが高速で、マイコンから扱うのは難しいことが多いですが、Raspberry Pi PicoにはPIOというメインCPUとは別に高速に簡単なロジックを実現する仕組みがあり、これを活用することで実現しているようです。

加えて簡単な電圧変換、アドレス変換のためにCPLDも利用しているようです。

Raspberry Pi PicoのPIOはほかのマイコンにはない特徴的な機能で、今後も面白い作例がたくさん出てきそうです。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/Pc2PUysWG2E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

