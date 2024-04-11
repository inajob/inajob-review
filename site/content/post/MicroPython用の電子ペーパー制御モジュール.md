---
title: MicroPython用の電子ペーパー制御モジュール
date: 2024-04-11T23:58:23.721659
description: MicroPython用の電子ペーパー制御モジュール
image: /img/MicroPython用の電子ペーパー制御モジュール.jpg
tags:
  - MicroPython
  - 電子ペーパー
  - HACK
---
[Clever E-Ink Driver Does 32 Levels Of Grey, Avoids Update Flicker, And More](https://hackaday.com/2024/03/23/clever-e-ink-driver-does-32-levels-of-grey-avoids-update-flicker-and-more/)から発見。画像もここから転載。

MicroPython用の電子ペーパー制御モジュールを紹介します。
一般的に白黒2色の電子ペーパーでは中間色を表現するためにはディザパターンを用いますが、このライブラリでは電子ペーパー本来の仕様を超えて、中間色の表現もできる機能があるようです。

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Rendering time at 4, 8, 16, 32 colors. <a href="https://t.co/KvU9BKmdoW">pic.twitter.com/KvU9BKmdoW</a></p>&mdash; antirez (@antirez) <a href="https://twitter.com/antirez/status/1770207433828237447?ref_src=twsrc%5Etfw">March 19, 2024</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



