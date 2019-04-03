---
title: 基板が直刺しできるArduino互換機
date: 2019-03-31T11:44:54.763Z
description: 基板が直刺しできるArduino互換機を紹介します。
image: /img/miniduino-usb.png
---
[miniduino USB](https://www.open-electronics.org/miniduino-usb/)から発見。画像もここから転載。

基板がUSB端子の形をしていて、直接PCに接続できるという、開発ボードはいくつかありますが、これはArduino Leonardo互換のものです。

電源回りが少し特徴的で、まずは5Vのレギュレータを積んでいません。これはUSBに接続することが前提なので納得の仕様です。

代わりにバッテリーをチャージしたり、バッテリーの電圧を5Vに昇圧する仕組みが搭載されています。これらも含めて回路図が公開されているので、似たようなプロダクトを作る際は参考になりそうです。
