---
title: 3Dプリントの失敗を監視するAIカメラ
date: 2022-05-22T22:39:13.307868
description: 3Dプリントの失敗を監視するAIカメラを紹介します。
image: /img/3Dプリントの失敗を監視するAIカメラ.jpg
tags:
  - 3Dプリンタ
  - AIカメラ
  - Raspberry Pi Pico
---
[Machine Vision Helps You Terminate Failing 3D Print Jobs](https://hackaday.com/2022/04/25/machine-vision-helps-you-terminate-failing-3d-print-jobs/)から発見。画像もここから転載。

HuskyLens AI cameraというAIカメラをつかって、3Dプリンタの各所に貼り付けたARマーカーを認識し、Raspberry Pi PicoとイーサーネットHATを使ってそのデータをインターネットに送信しているようです。

失敗検知と聞くと複雑な仕組みが必要そうだと感じますが、ARマーカーで各軸の動きを検知するという割と素朴な方法で実現できるんですね。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/gIvlC43ikNE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

