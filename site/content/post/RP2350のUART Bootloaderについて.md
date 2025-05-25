---
title: RP2350のUART Bootloaderについて
date: 2025-05-25T23:54:16.644979
description: RP2350のUART Bootloaderについて紹介します
image: /img/RP2350のUART Bootloaderについて.jpg
tags:
  - RP2350
---
[Exploring The RP2350’s UART-Bootloader](https://hackaday.com/2025/05/11/exploring-the-rp2350s-uart-bootloader/)から発見。画像もここから転載。

RP2350にはUART Bootloaderという機能があるようで、ほかのマイコンなどからUART経由でこれから実行するコードを転送することができるようです。

2つ以上のRP2350を搭載した機器を作る際に2つそれぞれファームウェアを焼くのが面倒という問題がありますが、この機能を利用して、1つのRP2350に両方のマイコン向けのファームウェアを書き込んだうえで、もう1つのRP2350は1つ目のマイコンからファームウェアを転送しつつ実行するということで、書き込みの複雑さを減らすことができるようです。

UART経由であれば何でも良いので、ほかにもいろいろな応用例がありそうな機能です。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/eno0hiFSr18" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



