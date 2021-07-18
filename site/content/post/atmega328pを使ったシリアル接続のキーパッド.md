---
title: ATmega328Pを使ったシリアル接続のキーパッド
date: 2021-07-18T11:00:10.633Z
description: ATmega328Pをつかったシリアル接続のキーパッドの作例を紹介します。
image: /img/macro-keypad.jpg
tags:
  - Arduino
---
[Ardu Keyboard](https://hackaday.io/project/170092-ardu-keyboard)から発見。画像もここから転載。

Arduinoを使ってUSBキーボードを作るという事例は星の数ほどありますが、それらはATmega32u4にUSB HIDのファームウェアを焼きこんで作られているものがほとんどです。
この方法も、今やかなり簡単に実現することが出来ますが、ファームウェアの部分が複雑ですし、安価なマイコンでは利用できません。

そこでこの記事では、ATmega328Pを利用してシリアル接続のキーパッドを作成しています。
しかし、シリアル接続のキーパッドは、シリアルコンソールで入力を確認できますが、USB HID接続のようにパソコンに接続したキーボードのように利用することはできません。

Ardu Keyboardが工夫しているのはこれからです。[PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)というPythonのライブラリを使ったプログラムをPC上で動作させ、シリアル接続で得たキー入力の情報をOSにキーストロークとして送信します。

この方式を使えば、パソコン側に専用ソフトを入れる必要があるものの、シリアル接続さえできればどんなに低スペックなマイコンでもパソコン用の入力装置を作ることが出来ます。

<iframe width="100%" height="315" src="https://www.youtube.com/embed/4IlrUkVi8kw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
