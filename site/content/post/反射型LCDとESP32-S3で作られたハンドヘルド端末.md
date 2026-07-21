---
title: 反射型LCDとESP32-S3で作られたハンドヘルド端末
date: 2026-07-21T22:44:05.710825
description: 反射型LCDとESP32-S3で作られたハンドヘルド端末
image: /img/反射型LCDとESP32-S3で作られたハンドヘルド端末.jpg
tags:
  - ESP32-S3
---
[Reflective LCD Slabtop Terminal Runs Homebrewed Solar OS](https://hackaday.com/2026/06/26/reflective-lcd-slabtop-terminal-runs-homebrewed-solar-os/)から発見。画像もここから転載。

反射型LCDというのは、バックライトを使わず、周囲の光を背面の反射層で反射させて画面を表示する液晶ディスプレイのことです。直射日光の下でも高い視認性を保ちながら、消費電力を極めて低く抑えられる特徴を持っています。

この記事では、ESP32-S3と4.2インチの反射型LCDを組み合わせたボードを核に、FreeRTOSベースの自作OSを搭載したポータブル端末を紹介しています。

3Dプリンタで出力した筐体にミニキーボードとバッテリーを収めた筐体で、シェルコマンドによる操作のほか、PythonやLuaでのスクリプト開発環境や、ファイルマネージャ、ブラウザなどのテキストアプリが動作する仕組みになっています。

ハードウェア構成からOSまで自分の好みに合わせて構築していくアプローチは、個人開発の究極の形としてとても魅力的だと感じました





