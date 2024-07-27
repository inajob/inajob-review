---
title: KiCADの基板データからケースを自動生成する仕組み
date: 2024-07-22T00:29:43.503903
description: KiCADの基板データからケースを自動生成する仕組み
image: /img/KiCADの基板データからケースを自動生成する仕組み.jpg
tags:
  - KiCAD
  - OpenSCAD
---
[Turbocase Generates A PCB Shell For You](https://hackaday.com/2024/06/03/turbocase-generates-a-pcb-shell-for-you/)から発見。画像もここから転載。

KiCADの基板データの情報を参考にして、自動的にOpenSCAD用のケースのデータを生成するスクリプトです。

自分も手動で似たようなことを実行し、ケースを作っているので、次からこのスクリプトを使ってみようかなと考えています。

開口部やねじ穴なども、うまいことKiCAD側で設定をマッピングして、ケース生成のための情報として利用できるようになっています。




