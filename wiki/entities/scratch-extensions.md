---
title: Scratchエコシステム
type: entity
tags: [プロジェクト, Scratch, 機械学習, ハードウェア, OSS]
sources: [https://github.com/champierre]
created: 2026-04-06
updated: 2026-04-06
---

# Scratchエコシステム

石原淳也が開発したScratch拡張機能・関連プロジェクト群の全体像。Scratchと機械学習・ハードウェア・ARなどを接続し、プログラミング教育の可能性を広げるツール群。

## 機械学習系

| プロジェクト | 説明 | ★ |
|---|---|---|
| [[entities/ml2scratch|ML2Scratch]] | 機械学習 × Scratch | 120 |
| [[entities/facemesh2scratch|Facemesh2Scratch]] | 顔メッシュ検出 × Scratch | 41 |
| [[entities/tm2scratch|TM2Scratch]] | Google Teachable Machine × Scratch | 31 |
| [[entities/posenet2scratch|PoseNet2Scratch]] | ポーズ検出 × Scratch | 30 |
| [[entities/handpose2scratch|HandPose2Scratch]] | 手のポーズ検出 × Scratch | 18 |
| [[entities/tmpose2scratch|TMPose2Scratch]] | Teachable Machine + ポーズ認識 | 6 |
| [[ChatGPT2Scratch]] | ChatGPT × Scratch | — |

## ハードウェア制御系

| プロジェクト | 説明 | ★ |
|---|---|---|
| Scratch2Sphero | Scratch 1.4からSphero 2.0を制御 | 24 |
| Scratch2Airborne | Parrot mini droneをScratchから制御 | 18 |
| Scratch2MiP | WowWee MiPロボットをScratchから制御 | 12 |
| Scratch2Romo | RomoロボットをScratchから制御 | 10 |

## AR・その他

| プロジェクト | 説明 | ★ |
|---|---|---|
| S2AR | Scratch × iOS ARKit | 6 |
| Live-Scratch | （Rust製） | 7 |

## 特徴

- 「**〇〇2Scratch**」という一貫した命名規則
- 各種センサーやAIモデルの出力をScratchのブロックとして利用可能にするブリッジ型アーキテクチャ
- [[entities/coderdojo|CoderDojo]]や教育現場で実際に活用されている

## 関連ページ

- [[entities/ml2scratch|ML2Scratch]]
- [[overview|石原淳也 — 概要]]
