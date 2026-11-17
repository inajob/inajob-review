---
title: ESP32-S3用のWasmが動く小さなOS「KoaOS」
date: 2026-11-17T21:00:30.051771
description: ESP32-S3用のWasmが動く小さなOS「KoaOS」
image: /img/ESP32-S3用のWasmが動く小さなOS「KoaOS」.jpg
tags:
  - ESP32-S3
  - WASM
---
[A Tiny OS For A Tiny Board](https://hackaday.com/2026/11/05/a-tiny-os-for-a-tiny-board/)から発見。画像もここから転載。

WebAssembly(Wasm)というのは特定のCPUアーキテクチャに依存せず、軽量かつ安全なサンドボックス上でプログラムを実行できるバイナリ形式のことです。

この記事紹介されているのは、ESP32-S3を搭載したHeltecのボード向けに開発された、C言語のSDKやUNIX風のシェルを備えるヘッドレスな軽量環境「KoaOS」です。
さらGitHubのにリポジトリの方を見るとFreeRTOSを土台にしつつ、シリアル経由での操作やWasmによるアプリの動的追加、ケイパビリティベースの権限管理といったユニークな仕組みが実装されている点が詳しく解説されています。

マイコンの上で動くこうした簡易的なランタイム環境やシェルの試みは、ファームウェアを丸ごと書き換えることなく安全に小規模デバイスの可能性を広げるアプローチとして面白いと感じました。




