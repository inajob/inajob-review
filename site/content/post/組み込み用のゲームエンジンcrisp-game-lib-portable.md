---
title: 組み込み用のゲームエンジンcrisp-game-lib-portable
date: 2022-10-12T23:18:46.565108
description: 組み込み用のゲームエンジンcrisp-game-lib-portableを紹介します
image: /img/組み込み用のゲームエンジンcrisp-game-lib-portable.jpg
tags:
  - ゲーム
  - M5stickC PLUS
---
[abagames/crisp-game-lib-portable: Minimal C-lang library for creating classic arcade-like mini-games running on devices and browsers (Experimental)](https://github.com/abagames/crisp-game-lib-portable)から発見。画像もここから転載。

この界隈で有名な[ABAさん](https://twitter.com/abagames) が開発している組み込み向けのミニゲーム開発用ライブラリです。

このライブラリはJavaScript向けに作られていた[crisp-game-lib](https://github.com/abagames/crisp-game-lib) をもとに作られています。
このライブラリは普通のゲーム向けのライブラリとは異なり「ミニゲーム」を作ることに特化しています。

それっぽいプリセットサウンドや、プリミティブ図形の描画機能、画面を華やかにするパーティクル機能、衝突判定など、ミニゲームを作るために特化した内容となっており、これによりミニゲームを、素早く・簡単に作ることが出来ます。

crisp-game-libを使ったゲームはたくさん作られており、このことからもこのライブラリの利便性は証明済みです。

現在はM5StickC PLUSでのみ動作を確認しているようですが、移植性高く開発されているようで、ほかのマイコンボードで動作させるのも簡単そうです。

<iframe sandbox="allow-popups allow-scripts allow-modals allow-forms allow-same-origin" style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=inajob-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B09MVQD8QJ&linkId=60cd813f85d28b265cd5689b99516eef"></iframe>

またWebAssemblyにも対応しており、組み込み機器向けに作ったゲームをブラウザでも遊ぶことが出来、作品のデモや、デバッグなどが簡単にできるというのも面白い特徴です。


<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">THUNDERがM5StickC PLUSで動くようになったので、主要機能はだいたい移植できたのでは <a href="https://t.co/h3xEIFCaDT">https://t.co/h3xEIFCaDT</a> <a href="https://t.co/IRUO0hq5Ko">pic.twitter.com/IRUO0hq5Ko</a></p>&mdash; ABA (@abagames) <a href="https://twitter.com/abagames/status/1579422839907954689?ref_src=twsrc%5Etfw">October 10, 2022</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



