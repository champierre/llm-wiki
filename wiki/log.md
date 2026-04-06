---
title: Log
type: overview
created: 2026-04-06
updated: 2026-04-06
---

# Wiki Log

## [2026-04-06] init | Wiki初期構築

- **ソース**: blog.champierre.com, github.com/champierre, x.com/jishiha（Twitter/Xは取得不可）
- **作成ページ**: overview, ml2scratch, scratch-extensions, coderdojo, libron, machiquest, books, programming-education, generative-ai
- **作成ファイル数**: 8ページ + index + log + CLAUDE.md
- **備考**: Twitter/Xからの情報取得は402エラーで不可。ブログとGitHubの公開情報を基に初期Wikiを構築。

## [2026-04-06] ingest | blog.champierre.com

- ブログトップページからプロフィール、経歴、著書、プロジェクト、最近の記事一覧を抽出
- 確認できた記事（2023〜2026年）: 8件
- 主要な発見: 生成AIへの関心（Claude Code、GPT、MCP）、Dynabookとの接続、CoderDojoオープンデータのWell-Being指標採用

## [2026-04-06] ingest | github.com/champierre

- プロフィール: 279リポジトリ、215フォロワー、つくる社LLC所属
- ピン留めリポジトリ6件、スター数トップ20リポジトリを分析
- 主要な発見: 「〇〇2Scratch」命名規則の一貫したScratch拡張機能群、多言語対応（JS/Ruby/Rust/Swift/ObjC）

## [2026-04-06] ingest | sites.google.com/view/tukumanalab

- 青学つくまなラボの公式サイトおよびメンバーページからの情報抽出
- 石原淳也が総合文化政策学部プロジェクト准教授・フェローであることが判明
- 阿部和広氏（シニア・フェロー）との協働関係を確認
- 作成ページ: entities/tukumana-lab.md
- 更新ページ: programming-education.md（大幅拡充）、overview.md、coderdojo.md、index.md
- 主要な発見: プログラミング教育活動が「草の根（CoderDojo）」と「大学制度（つくまなラボ）」の二軸構造であること

## [2026-04-06] update | 青学つくまなラボページ掘り下げ

- つくまなラボ公式サイトのメニューページ、トップページから詳細情報を追加取得
- 設備一覧（レーザーカッター、3Dプリンター、Meta Quest3等）を追加
- ワークショップ10種類を3カテゴリ（デジタルファブリケーション/プログラミング/VR・メタバース）に整理
- 初等部〜大学の垂直統合型教育連携の構造を明確化
- メディア掲載情報（インプレス、読売オンライン）を追加
- ブログ記事「生成AIによるコーディングはDynabook完成の最後のピース」から阿部和広との関係性の詳細を取得
- 新規作成: entities/abe-kazuhiro.md（阿部和広）

## [2026-04-07] update | 阿部和広ページ掘り下げ

- Web検索（coeteco.jp、Wikipedia、津田塾大インタビュー、Amazon）から詳細経歴を取得
- 経歴年表: 1965年倉敷生まれ → 広島工業大 → 富士ゼロックス情報システム → 2001年アラン・ケイに師事 → 教育へ転身
- 知的系譜を整理: アラン・ケイ → Smalltalk → Squeak Etoys → Scratch → 石原淳也のScratch拡張
- 重要な発見: 『Raspberry Piではじめるどきどきプログラミング』が阿部和広・石原淳也の共著だった — 二人の関係は「つくまなラボの同僚」だけでなく「共著者」
- 教育思想を整理: 「表現教育」「教えない教育」「構築主義」
- NHK Eテレ『Why!? プログラミング』の監修・出演情報を追加
- 著書一覧を大幅拡充（単著、共著、監修）
- entities/books.md も共著情報で更新

## [2026-04-07] research | 横川耕二ページ作成

- Web検索およびYengawa Lab、Maker Faire Tokyo、Microbit Moreサイトから情報取得
- 経歴: IPA未踏プロジェクト（2004-2005、アラン・ケイ博士のもと）→ NHK『Why!? プログラミング』Scratch制作 → つくまなラボフェロー
- 代表プロジェクト: Microbit More（micro:bitの全機能をScratchから利用可能にする拡張機能の開発者）
- 石原淳也との関係を「Scratch拡張の二つの方向」（AI/ML vs フィジカルコンピューティング）として構造化
- 新規作成: entities/yokokawa-koji.md

## [2026-04-07] ingest | github.com/champierre/resume

- GitHubレジュメから石原淳也の完全な経歴を取得
- 学歴判明: 筑波大学附属駒場中高 → 東京大学工学部機械情報工学科（1995年卒）
- 職歴年表を大幅更新: iDC国際デジタル通信 → ジェネシス・ジャパン → Genesys米国本社 → ウノウ → 個人事業主 → つくる社LLC → まちクエスト → Geolonia → 青山学院大学
- 受賞歴追加: Drecom Award on Rails 2006、Mashup Award複数回、カーリルAPIコンテスト準グランプリ
- overview.md の経歴セクションを年表形式に全面改訂

## [2026-04-07] create | 宮田和樹・吉田葵ページ

- 宮田和樹: researchmap.jpから情報取得。VR/AR・デジタルストーリーテリング専門、つくまなラボフェロー
- 吉田葵: 青山学院大学教員情報から取得。学習支援システム・教育工学・プログラミング教育専門、津田塾大出身（阿部和広との接点）
- 新規作成: entities/miyata-kazuki.md, entities/yoshida-aoi.md

## [2026-04-07] create | プロジェクト一覧・Scratchページ + リンク修正

- entities/projects.md: 279リポジトリから主要プロジェクトをカテゴリ別に整理（ML系、ハードウェア系、地理情報系、MCP系等）
- entities/scratch.md: Scratchの概念ページ（知的系譜、石原淳也との関わり）
- Scratch拡張5ページ新規作成: facemesh2scratch, tm2scratch, posenet2scratch, handpose2scratch, tmpose2scratch
- 全ファイルのwikilinks修正（[[Scratch]]→[[entities/scratch|Scratch]]、[[プロジェクト一覧]]→[[entities/projects|プロジェクト一覧]]等）
- 著書ページ拡充: 出版情報・ISBN・内容詳細を追加
