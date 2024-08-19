---
title: 気象衛星の通信データをSDRで受信する
date: 2021-08-17T12:00:16.994Z
description: 気象衛星のデータは個人でも比較的簡単に受信できるようです。
image: /img/noaa.png
tags:
  - HACK
  - SDR
---
[GET YOUR WEATHER IMAGES STRAIGHT FROM THE SATELLITE](https://hackaday.com/2020/03/14/get-your-weather-images-straight-from-the-satellite/)から発見。画像もここから転載。

気象衛星のデータは、地上に送信され続けていますが、その回線は暗号化などはされておらず、設備さえあれば、誰でも受信できるようです。


この記事では、SDRドングルで137MHzの気象衛星の電波を受信し、それをデコードするソフトに処理させることで、気象衛星からの画像を取得しています。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/PWWGDL5tC_I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
