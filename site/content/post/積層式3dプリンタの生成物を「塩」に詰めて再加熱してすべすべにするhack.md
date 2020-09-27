---
title: 積層式3Dプリンタの生成物を「塩」に詰めて再加熱してすべすべにするHACK
date: 2020-09-27T10:30:50.168Z
description: >-
  積層式3Dプリンタの生成物はいわゆる「積層痕」が表面に出てしまい、仕上がりの品質があまりよくありません。この問題を解消するために「塩」を使う方法があるようです。
image: /img/3d-printer-and-salt.png
tags:
  - 3Dプリンタ
  - HACK
---
[REFORMING 3D PRINTS WITH SALT AND HEAT](https://hackaday.com/2020/09/23/reforming-3d-prints-with-salt-and-heat/)から発見。画像もここから転載。

積層式3Dプリンタの生成物は、いわゆる「積層痕」が表面に出てしまうという品質上の問題があります。

この記事で紹介しているのは、この「積層痕」を解消する方法です。
3Dプリンタの生成物を、細かく砕いた「塩」の中に突っ込んで加熱するという、さながら「塩釜焼き」のような方法をとることで、生成物の形状を壊すことなく表面を滑らかにすることができるようです。

注意としては生成物はinfillを100%とし、内部に空洞を作らないことと、フィラメントの素材によって加熱の温度が違うという点です。

---
このURLと日本語の要約をTwitterに投稿したところ、多くの方に見ていただき、早速実践を試みている方も現れました。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">積層式の3Dプリンタの生成物を「塩」に詰めて再加熱することで表面の積層痕を無くすという話らしい。 まるで光造形式の3Dプリンタで作ったかのように滑らかになるらしい。 / “Reforming 3D Prints With Salt And Heat | Hackaday” (2 users) <a href="https://t.co/lSZxyHmEOr">https://t.co/lSZxyHmEOr</a></p>&mdash; ina_ani@育休中 (@ina_ani) <a href="https://twitter.com/ina_ani/status/1309651680607178752?ref_src=twsrc%5Etfw">September 26, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

ただ、ただ塩に詰めて加熱するだけではなく、様々なパラメータをうまく調整しないと、写真のようにきれいにはいかないようで、皆さん苦労しているようです。

この手法が確立すれば積層式の3Dプリンタの用途がぐっと広がる事でしょう。

---
# （以下この手法に挑戦されている方のTwitを載せておきます。）

---

加熱がまずかったのか、変形してしまっているけど、あと一息？

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">3Dプリント塩釜焼きテストその二。<br>ムクで造形した四角パイプがこうなりました…ました？？？<br><br>オーブン設定は230度の20分<br>前回と違い塩の中から浮き上がっては来なくなったのでムク造形でないといけないというのは確か。後は温度と時間か <a href="https://t.co/6DzuE34tQJ">pic.twitter.com/6DzuE34tQJ</a></p>&mdash; 45ACPなる、遥けき便り、うち捨てむ、そは呪われし、回文にして (@Giro_45ACP) <a href="https://twitter.com/Giro_45ACP/status/1310143345096761344?ref_src=twsrc%5Etfw">September 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

これから挑戦される様子・・どうなるでしょうか？

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">とりあえずこいつを塩漬けにしてみますぜ。 <a href="https://t.co/Vg1ngnvn6e">pic.twitter.com/Vg1ngnvn6e</a></p>&mdash; NN (@kiiimlo) <a href="https://twitter.com/kiiimlo/status/1310126242708951040?ref_src=twsrc%5Etfw">September 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

積層痕は残っているようですが、表面の性質が変化したようで、やすり掛けするとつるつるになったようです。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">塩による積層痕処理試してみました<br>予想はできてたけどもっと細かい塩でやらんとダメですね<br>こんがり美味しそうな色になったのは温度か時間か...<br>なんにしても色々検証すればつかえそう <a href="https://t.co/riiiUNN7ad">https://t.co/riiiUNN7ad</a> <a href="https://t.co/gnltv4wjHE">pic.twitter.com/gnltv4wjHE</a></p>&mdash; 手のひと ハマー (@hama_lo_0l) <a href="https://twitter.com/hama_lo_0l/status/1310083062282121221?ref_src=twsrc%5Etfw">September 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

かなりうまくいっているのでは・・？

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">ABSの塩焼き2回目(^^)<br><br>前回より良くなったかな<br>ツルツルな面とザラザラな面が有るのと<br>端が外側に広がってるのは塩を固める力が足りてないのかな？？<br><br>何にせよ一回目よりは良くなった(^^)<br>次はより強く塩を固める方法を考えるか… <a href="https://t.co/K3GAt88IJ2">pic.twitter.com/K3GAt88IJ2</a></p>&mdash; 🦮いけのり / sion-e (@sione21230094) <a href="https://twitter.com/sione21230094/status/1310138706322366464?ref_src=twsrc%5Etfw">September 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

こちらも、かなりうまくいっている様子。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">うぉおお！積層跡が消えて、ショットブラスト肌みたいになってる！(右下) <a href="https://t.co/6y89PLmzmS">pic.twitter.com/6y89PLmzmS</a></p>&mdash; Nii (@neet2121) <a href="https://twitter.com/neet2121/status/1310169332370923520?ref_src=twsrc%5Etfw">September 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

皆さん行動が早くてすごいですね・・
