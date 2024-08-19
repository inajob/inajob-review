---
title: I2C接続のOLEDを少ないピンで複数制御する裏技
date: 2019-07-04T23:00:41.695Z
description: I2C接続のOLEDを少ないピンで複数制御する裏技を紹介します
image: /img/multi_oled.jpg
tags:
  - OLED
---
[Controlling lots of OLED displays with a few GPIO pins 
](http://bitbanksoftware.blogspot.com/2019/01/controlling-lots-of-oled-displays-with.html)から発見。写真もここから転載

安いI2C接続のOLEDは大体同じI2Cアドレスです（0x3Cとか、0x3Dとか）。I2Cの利点の一つとして異なるアドレスのデバイスであればバスが共有できるというのがありますが、このようにアドレスが同じモジュールではバスを共有することができません。

これを解決する方法はいくつもありますが、この記事では、I2C接続のClockの線だけを共用にしてDataの線を別のGPIOに割り当てることで、ピンを節約する方法を紹介しています。

通常ArduinoではAVRに内蔵されているハードウェアI2Cの機能を使いますが、この方法を使うためにはソフトウェアでI2Cを扱う必要があるため、そのためのライブラリを作ったようです。 [bitbank2/Multi_OLED](https://github.com/bitbank2/Multi_OLED)

I2C接続のOLEDは非常に安く手に入るので、これらを複数組み合わせて作品を作るのは良いアイデアのように思います。
<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=inajob-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B017M15KX6&linkId=522cafab1cce68443faaf880201addaa"></iframe>

ぜひこのライブラリで挑戦してみてください。


<iframe width="100%" height="315" src="https://www.youtube.com/embed/adc9y-w7V3g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

