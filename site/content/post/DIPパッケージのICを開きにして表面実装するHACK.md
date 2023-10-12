---
title: DIPパッケージのICを開きにして表面実装するHACK
date: 2023-10-12T23:29:15.620242
description: DIPパッケージのICを開きにして表面実装するHACKを紹介します
image: /img/DIPパッケージのICを開きにして表面実装するHACK.jpg
tags:
  - HACK
---
[Chip Shortage Engineering: Misusing DIP Packages](https://hackaday.com/2023/10/03/chip-shortage-engineering-misusing-dip-packages/)から発見。画像もここから転載。

半導体不足の影響で、よく使われる部品が思わぬ高値になっていることがあります。
この記事の作者は8ピンDIPのATtiny85を大量に持っており、これを活用する方法を考えていたようです。

その方法は、画像のようにDIPのICの足を「開き」にすることです。
この「開き」にしたピンに合うような長いパッドのフットプリントを用意し、DIP部品をSMDパーツとして基板に実装しています。

まぁこんなことをしなくても、半導体不足の影響を受けにくい最新のIC（ATtinyでいうと、tinyAVR 2系のIC）を使う方がコスト的には安くつくようですが、家にDIP部品が余っている方は試してみるのはどうでしょう？



