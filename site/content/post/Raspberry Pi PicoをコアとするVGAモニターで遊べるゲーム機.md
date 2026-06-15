---
title: Raspberry Pi PicoをコアとするVGAモニターで遊べるゲーム機
date: 2026-06-15T22:15:00.394311
description: Raspberry Pi PicoをコアとするVGAモニターで遊べるゲーム機
image: /img/Raspberry Pi PicoをコアとするVGAモニターで遊べるゲーム機.jpg
tags:
  - Raspberry PI Pico
  - ゲーム機
---
[Pico VGA BLASTER](https://hackaday.io/project/205792-pico-vga-blaster)から発見。画像もここから転載。

Raspberry Pi PicoのPIOは、プログラマブルI/Oとして周辺機器との通信をCPUから独立して高速かつ正確に制御できる機能で、この機能を使えば、CPUの負荷を抑えつつ安定した描画タイミングを維持できるため、多くのVGA出力プロジェクトで活用されています。

Pico VGA Blasterは、このRaspberry Pi Picoの能力を活用し、レトロなゲームをVGAモニターで遊べるようにしたプロジェクトです。専用ボードには、Picoのデジタル信号をVGA規格に適した電圧へ調整する抵抗ネットワークやD-SUB15ピンコネクタ、電源レギュレータが実装されており、これに3Dプリントした筐体と操作用ボタンを組み合わせることで、本格的なアーケードゲーム機のような外観と操作性を再現しています。

マイコン1つで信号のタイミング生成からゲームの演算処理までを完結させ、アナログディスプレイで映像を出力してしまうという、ハードウェアの限界を引き出すような構成が面白いです。




<iframe width="100%" height="315" src="https://www.youtube.com/embed/wCntdiy6IZs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

