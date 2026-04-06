---
title: 石原淳也 — 概要
type: overview
tags: [人物, 概要]
sources: [https://blog.champierre.com/, https://github.com/champierre, https://github.com/champierre/resume, https://www.itmedia.co.jp/bizid/articles/0705/23/news096.html]
created: 2026-04-06
updated: 2026-04-07
---

# 石原淳也（Junya Ishihara）

東京在住のソフトウェアエンジニア。株式会社まちクエスト代表、つくる社LLC（Tsukurusha, LLC）代表。青山学院大学 総合文化政策学部プロジェクト准教授、[[entities/tukumana-lab|青学つくまなラボ]]フェロー。プログラミング教育、特に[[entities/scratch|Scratch]]と機械学習の教育応用を軸に、OSS開発・執筆・コミュニティ運営を幅広く手がける。

## プロフィール

- **所在地**: 東京
- **会社**: 株式会社まちクエスト / つくる社LLC
- **ブログ**: https://blog.champierre.com/
- **GitHub**: https://github.com/champierre（279リポジトリ、215フォロワー）
- **Twitter/X**: [@jishiha](https://x.com/jishiha)
- **Email**: webmaster at champierre dot com

## 学歴

- **筑波大学附属駒場中学校**（1988年卒）
- **筑波大学附属駒場高等学校**（1991年卒）
- **東京大学 工学部 機械情報工学科**（1995年卒）

## 経歴

| 年 | 所属 | 役割 |
|---|---|---|
| 1995〜1998年 | iDC国際デジタル通信 | 交換機エンジニア |
| 1998〜2000年 | ジェネシス・ジャパン | QAエンジニア |
| 2000〜2004年 | Genesys米国本社（サンフランシスコ） | 国際化QAエンジニア |
| 2004〜2005年 | ジェネシス・ジャパン | テクニカルサポート |
| 2005〜2006年 | ウノウ | ディレクター |
| 2006〜2010年 | 個人事業主 | Web・iPhone・Androidアプリ受託開発。おでかけマペタ、あとで行く等の個人サービスをRuby on Railsで開発 |
| 2010年〜 | 合同会社つくる社（代表社員） | — |
| 2013年〜 | 株式会社まちクエスト（代表取締役） | — |
| 2022〜2023年 | 株式会社Geolonia | エンジニア |
| 2024年〜 | 青山学院大学 | プロジェクト准教授、[[entities/tukumana-lab|青学つくまなラボ]]フェロー |

## 受賞歴

- Drecom Award on Rails 2006
- Mashup Award 2nd
- Mashup Award 3rd（Skype賞）
- カーリルAPIコンテスト 準グランプリ
- Mashup Awards オープンデータ部門賞

## 主な活動領域

### プログラミング教育
二つの軸で展開：地域コミュニティベースの[[entities/coderdojo|CoderDojo]]調布の運営と、大学制度内の[[entities/tukumana-lab|青学つくまなラボ]]でのSTEAM教育。Scratchを中心とした子ども向けプログラミング教育に注力。[[entities/ml2scratch|ML2Scratch]]をはじめとする一連のScratch拡張機能を開発し、機械学習を子どもにもアクセスしやすい形で提供している。→ [[concepts/programming-education|プログラミング教育]]

### OSS開発
GitHub上で279のリポジトリを公開。特にScratchと各種技術を接続する拡張機能群が代表的：
- [[entities/ml2scratch|ML2Scratch]]（★120） — 機械学習 × Scratch
- [[entities/facemesh2scratch|Facemesh2Scratch]]（★41） — 顔メッシュ検出 × Scratch
- [[entities/tm2scratch|TM2Scratch]]（★31） — Google Teachable Machine × Scratch
- [[entities/posenet2scratch|PoseNet2Scratch]]（★30） — ポーズ検出 × Scratch
- [[entities/libron|Libron]]（★18） — Amazonから図書館蔵書を検索

### 執筆
- 『[[entities/books|Scratchで楽しく学ぶ アート&サイエンス]]』
- 『[[entities/books|Raspberry Piではじめる どきどきプログラミング]]』

### コミュニティ
- [[entities/coderdojo|CoderDojo]]調布の運営（2025年現在も継続）
- RubyKaigi参加・講演
- Scratch Day開催
- coderdojo-tokyo（GitHub Organization）メンバー

## 初期のOSS・Webサービス活動

個人事業主時代（2006年〜）以前から、OSSへの貢献やWebサービス開発に取り組んでいた（[ITmedia BizID「ひとりで始めるネットサービス」2007年](https://www.itmedia.co.jp/bizid/articles/0705/23/news096.html)）。

- **POPFile日本語化** — ベイズ統計による迷惑メールフィルタリングソフトPOPFileをSourceForge.netで発見し、日本語ローカライズパッチを作成・コントリビュート
- **おでかけマペタ** — 位置情報ブックマークサービス。Ruby on Rails + Google Maps連携。一人でネットサービスを立ち上げる実践
- **あとで行く** — おでかけマペタの後継。タグベースの整理機能を追加

これらの経験がのちの[[entities/libron|Libron]]（2009年〜）や[[entities/machiquest|まちクエスト]]（2013年〜）の開発につながっている。

## 技術スタック

- **言語**: Ruby, JavaScript, Rust, Swift, Objective-C
- **フレームワーク**: Ruby on Rails
- **ML/AI**: TensorFlow.js, MediaPipe, Google Teachable Machine
- **インフラ**: Cloudflare, Heroku, さくらVPS, Kamal
- **その他**: GIS（PostGIS）, ARKit

## 関心・最近の動向

### 生成AIによるコーディング
Claude Codeを使い、「[MOTC（Master Of The Chessboard）](https://blog.champierre.com/1404)」という自分専用チェス学習アプリを開発（2025年8月）。1923年出版の古典チェス書をAIに読ませ、棋譜のビジュアル化・アニメーション・日本語解説を実装。「日曜大工で自分専用の道具を作るように、AIに頼めば自分専用のアプリを手軽に作れる」という実感を得ている。開発時にはCLAUDE.mdファイルでAIへの指示を管理する手法を確立。

### LLMとプログラミング教育の融合
ブログ記事「[生成AIによるコーディングはDynabook完成の最後のピース](https://blog.champierre.com/1470)」（2025年11月）で、15年間の[[concepts/programming-education|プログラミング教育]]実践を踏まえた論考を発表。[[entities/scratch|Scratch]]で重力シミュレーションを実装するには変数・ループ等の高度な習熟が必要で、40人クラスでそこに達する生徒は限定的。生成AIが自然言語での指示を受けてコードを生成することで、この「観察から実装への大きなジャンプ」を埋め、アラン・ケイのDynabookビジョンを完成させるという主張。→ [[concepts/generative-ai|生成AIとコーディング]]

### CoderDojoのオープンデータとWell-Being指標
[[entities/coderdojo|CoderDojo]]のオープンデータがデジタル庁推進の「[地域のWell-Being指標のデジタル生活指数](https://blog.champierre.com/1437)」に採用（2025年10月）。CoderDojoの有無や開催数が市区町村の暮らしやすさの間接的指標として使われるようになった。全国200以上の拠点での無償活動が「地域の暮らしやすさを上げる具体的な活動」として公的に位置づけられた意義は大きい。

### Cloudflare MCPサーバー
「[CloudflareにリモートMCPサーバーをデプロイし、各種MCPクライアントからSSEで接続する](https://blog.champierre.com/1371)」（2025年5月）。Cloudflare Workers上にMCP（Model Context Protocol）サーバーを構築し、AI Playground・Claude Desktop等から接続する実践。Claude Desktopでは「mcp-remote」ブリッジを使ったSSE→stdio変換が必要。GitHubリポジトリ [image-mcp-server](https://github.com/champierre/image-mcp-server)（★7）も公開。

### Rails 8 + Kamalデプロイ
「[さくらVPSにRails 8をKamalでデプロイする](https://blog.champierre.com/1338)」（2025年5月）。Rails 8の新しいデプロイツールKamalを使い、さくらVPSへのデプロイ手順を記録。ポイントはSSHユーザーのubuntuへの変更、Dockerグループ権限、サブドメイン+SSL初期設定。

## 関連ページ

- [[concepts/programming-education|プログラミング教育]] — 教育活動の全体像
- [[entities/tukumana-lab|青学つくまなラボ]] — 大学メイカースペースでの活動
- [[entities/scratch-extensions|Scratchエコシステム]] — Scratch拡張機能群の詳細
- [[entities/projects|プロジェクト一覧]] — 開発プロジェクトの網羅的リスト
- [[ブログ記事一覧]] — ブログ記事の時系列リスト
