---
title: ESP32で動くよう改造されたOpenCV
date: 2022-06-14T22:30:45.928458
description: ESP32で動くよう改造されたOpenCVについて紹介します。
image: /img/ESP32で動くよう改造されたOpenCV.jpg
tags:
  - ESP32
  - OpenCV
---
[OpenCV Running On A Tiny Microcontroller](https://hackaday.com/2022/05/19/opencv-running-on-tiny-microcontroller/)から発見。画像もここから転載。

ESP32でOpenCVを動かした話です。

そのまま動作させるのはパフォーマンス的に難しかったようで様々な改造を行っているようです。

Raspberry Piや他のLinuxが動作するボードなどの方がパワフルですが、ESP32はこれらに比べると非常に安価なので、この性能で事足りる場合は試してみる価値はありそうです。

[この成果はGitHubにて公開されています](https://github.com/joachimBurket/esp32-opencv)


<iframe width="100%" height="315" src="https://www.youtube.com/embed/7qPIRBY6C8c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

