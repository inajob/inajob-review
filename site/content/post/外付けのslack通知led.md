---
title: 外付けのSlack通知LED
date: 2019-07-14T12:21:02.929Z
description: パソコンに外付けするSlack通知LEDの作例を紹介します
image: /img/slack-notification.jeg.jpeg
tags:
  - 作例
---
[Build a Slack Status Indicator for Your Desk to Keep Coworkers at Bay](https://blog.hackster.io/build-a-slack-status-indicator-for-your-desk-to-keep-coworkers-at-bay-ea3a229be1f9)から発見。画像もここから転載。

Adafruit Trinket M0を使ったSlack通知のLEDです。

[GitHub](https://github.com/codybuell/donotdisturb)にソースコードも公開されているので、気になる人は見てみてください。

Adafruit Trinket M0はPythonで開発できるので組み込みといいつつ、気軽に開発できそうです。
PCとはUSBで接続しシリアル経由でやり取りします。PC側のサーバはGo言語で書かれていて今風です。
