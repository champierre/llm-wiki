---
title: PoseNet2Scratch
type: entity
tags: [プロジェクト, Scratch, 機械学習, OSS]
sources: [https://github.com/champierre/posenet2scratch]
created: 2026-04-07
updated: 2026-04-07
---

# PoseNet2Scratch

PoseNetを使ったポーズ検出とScratchを接続するScratch 3拡張機能（GitHub ★30）。[[entities/ml2scratch|ML2Scratch]]から派生したプロジェクトの一つ。

## 概要

PoseNetによる人体のポーズ検出をScratch 3で利用できるようにする拡張機能。カメラから取得した映像をもとに、鼻・目・肩・肘・手首・腰・膝・足首などの身体のキーポイントをリアルタイムで検出し、その座標データをScratchのブロックとして利用可能にする。体の動きを使ったゲームやインタラクティブな作品をブロックプログラミングで作成できる。

## 技術

- **言語**: JavaScript
- **ML**: PoseNet（TensorFlow.js）
- **プラットフォーム**: Scratch 3

## 関連ページ

- [[entities/ml2scratch|ML2Scratch]] — 起点となったプロジェクト
- [[entities/scratch-extensions|Scratchエコシステム]]
- [[overview|石原淳也 — 概要]]
