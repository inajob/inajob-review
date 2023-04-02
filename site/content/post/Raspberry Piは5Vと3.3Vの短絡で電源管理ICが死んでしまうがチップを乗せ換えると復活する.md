---
title: Raspberry Piは5Vと3.3Vの短絡で電源管理ICが死んでしまうがチップを乗せ換えると復活する
date: 2023-04-02T23:34:56.496394
description: Raspberry Piは5Vと3.3Vの短絡で電源管理ICが死んでしまうがチップを乗せ換えると復活する
image: /img/Raspberry Piは5Vと3.3Vの短絡で電源管理ICが死んでしまうがチップを乗せ換えると復活する.jpg
tags:
  - RaspberryPi
  - HACK
---
[Dead Raspberry Pi Boards, PMICs, And New Hope](https://hackaday.com/2023/03/24/dead-raspberry-pi-boards-pmics-and-new-hope/)から発見。画像もここから転載。

Raspberry Piを壊してしまったことはありませんか？

幸いにして自分はまだその経験はないのですが、故障パターンの一つとして電源管理IC(MxL7704)が壊れてしまうというのがあるようです。
これは5Vと3.3Vを直結してしまうと起きるようで、Raspberry Piで電子工作をしている際には、ついやってしまいそうな故障パターンです。

壊れているのは電源管理ICのみなので、これを付け替えると復活する可能性があります。

この記事では電源管理ICを乗せ換える方法について紹介しています。

ただし、乗せ換えるICはBGPで再はんだ付けするのはテクニックが必要ですし、ただ乗せ換えるだけではだめでI2Cのアドレスを適切に設定する必要があるようです。


