---
title: 生成AIとコーディング
type: concept
tags: [AI, LLM, Claude Code, MCP, 開発]
sources: [https://blog.champierre.com/1470, https://blog.champierre.com/1404, https://blog.champierre.com/1371, https://blog.champierre.com/1503]
created: 2026-04-06
updated: 2026-04-07
---

# 生成AIとコーディング

石原淳也が近年注力しているテーマ。LLMを活用したソフトウェア開発の実践と、その教育的意義への考察。

## Dynabookビジョンとの接続

ブログ記事「[生成AIによるコーディングはDynabook完成の最後のピース](https://blog.champierre.com/1470)」（2025年11月）は、15年間の[[concepts/programming-education|プログラミング教育]]実践を踏まえた核心的な論考。

**問題意識**: [[entities/scratch|Scratch]]で重力シミュレーションを実装するには、変数・ループ・演算などの高度な習熟が必要。一般的な40人クラスで[[entities/coderdojo|CoderDojo]]の常連レベルに達する生徒は極めて限定的。「観察から実装への大きなジャンプ」が存在する。

**提案**: [Devin](https://devin.ai/)、[Cline](https://github.com/cline/cline)、[Claude Code](https://claude.ai/code)などの生成AIコーディングツールにより、子どもが自然言語で「重力で引っ張られるようにしたい」と指示するだけでAIがコードを生成する。この障壁の解消が、[アラン・ケイ](https://ja.wikipedia.org/wiki/%E3%82%A2%E3%83%A9%E3%83%B3%E3%83%BB%E3%82%B1%E3%82%A4)のDynabookビジョンを完成させる「最後のピース」になる。

記事中では[[entities/abe-kazuhiro|阿部和広]]の「伝説のプレゼン」（Apple本社での「ｉのある教育と学習」セミナー）にも言及されている。

## Claude Codeによる個人開発

「[Claude Codeと作った完全自分専用アプリ — MOTC（Master Of The Chessboard）](https://blog.champierre.com/1404)」（2025年8月）。

1923年出版の古典チェス書を学習するためのアプリをClaude Codeで開発。棋譜と解説が混在する原文をAIに読ませ、以下の機能を実装：
- 盤面のビジュアル化・アニメーション
- 駒の軌跡表示
- 手番の色分け
- 日本語解説

**開発手法**: 全文をClaude Codeに渡し、細かいタスクに分割して段階的に指示。`CLAUDE.md`ファイルでAIへの指示を管理する手法を確立。棋譜の正確性は`chess_validator.py`（Pythonバリデータ）で100%保証。

**所感**: 「日曜大工で自分専用の道具を作るように、AIに頼めば自分専用のアプリを手軽に作れる」— 極めてニッチだが個人的には最高に便利なツール。

## MCP（Model Context Protocol）

「[CloudflareにリモートMCPサーバーをデプロイし、各種MCPクライアントからSSEで接続する](https://blog.champierre.com/1371)」（2025年5月）。

[Cloudflare Workers](https://workers.cloudflare.com/)上にMCPサーバーを構築し、AI Playground・Claude Desktop等から接続する実践。

- **デプロイ**: 「Deploy to Cloudflareボタンを押すだけ」で実施可能
- **AI Playground**: SSE形式で直接接続
- **Claude Desktop**: 無料・Proでは「[mcp-remote](https://github.com/anthropics/mcp-remote)」ブリッジが必要（SSE→stdio変換）
- GitHub: [image-mcp-server](https://github.com/champierre/image-mcp-server)（★7）も公開

## LLMの創作能力

「[GPT 5.4にScratchを題材にした小説を書かせてみた](https://blog.champierre.com/1503)」（2026年3月）— LLMの創作能力の実験。

## 関連プロジェクト

- [ChatGPT2Scratch](https://github.com/champierre/chatgpt2scratch) — ChatGPTと[[entities/scratch|Scratch]]の接続（[[entities/scratch-extensions|Scratchエコシステム]]の延長線上）
- [OpenAI2Scratch](https://github.com/champierre/openai2scratch) — OpenAI × Scratch
- [image-mcp-server](https://github.com/champierre/image-mcp-server)（★7）— MCPサーバーの実装
- [threejs-mcp](https://github.com/champierre/threejs-mcp)（★3）— Three.js MCPサーバー

## 関連ページ

- [[concepts/programming-education|プログラミング教育]]
- [[entities/scratch|Scratch]]
- [[entities/abe-kazuhiro|阿部和広]]
- [[entities/coderdojo|CoderDojo]]
- [[overview|石原淳也 — 概要]]
