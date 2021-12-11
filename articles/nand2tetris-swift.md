---
title: "「コンピュータシステムの理論と実装」をSwiftで実装してみた"
emoji: "🖥"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [ios,swift]
published: false
---

一旦書くことを箇条書きでまとめる
図解するとおもしろそうな

（導入）

* 先人の事例
* なぜやろうと思ったのか
* どこまでの範囲を含むか

実装難易度表記

* ★☆☆☆☆ : 前提知識でほぼ完全に実装できる
* ★★☆☆☆ : 本の内容を追えば実装できる
* ★★★☆☆ : 本の内容を追いかつ少し考えれば実装できる
* ★★★★☆ : 本の内容を追いかつ熟考すれば実装できる
* ★★★★★ : 本の内容を追いかつ考えても実装が怪しく、深い理解が必要

## 1章　ブール論理

★★★☆☆
マルチプレクサのところで少し悩みましたが、地道に検討すればできました。
論理演算に慣れるまでがつらかったです。

* Nandゲートがベース
* 基本的なゲート

## 2章　ブール算術

★★☆☆☆


* 加算器
* ALU

## 3章　順序回路

★★★☆☆

* 順序回路としてDFF
* Register
* RAM
* PC

## 4章　機械語

★★★☆☆

* 機械語
* アセンブラ、アセンブリ言語

## 5章　コンピュータアーキテクチャ

★★★★☆

* CPU
* Computer

## 6章　アセンブラ

★★★☆☆
仕様通りに実装していけば良いのですが、テストで失敗することが多くまたその修正に時間がかかりました。

* アセンブラ詳細