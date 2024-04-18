---
title: "Unilab 電車App"
date: 2023-08-01T02:34:27+09:00
draft: false
toc: false
images:
tags:
  - engineering
  - project
  - ML
---

## 概要
イベントの催し物を作成する課題で
機械学習のポーズの推定をwebカメラを使用して行うことで可能にしました。
グループでポーズを受け取って電車を動かす担当とカメラからのポーズを推定する担当で分かれて作業を行いました。困難だったのはデータの受け渡しの形のやり取りやデータのやり取りでソケット通信を行う必要があることで困難でしたが相互にこまめにやり取りを行うことで達成しました。

## 使用技術
ML, python, docker, Go

## Reference
https://github.com/Rwatana/unilab_train