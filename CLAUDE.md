# LLM Wiki — 石原淳也

このリポジトリは石原淳也に関するLLM Wikiです。LLMが継続的に構築・維持するマークダウンベースのナレッジベースです。

## ディレクトリ構造

```
raw/          # 生のソースドキュメント（不変）
wiki/         # LLMが生成・管理するWikiページ
  index.md    # 全ページのカタログ（カテゴリ別）
  log.md      # 時系列の操作ログ
llm-wiki.md   # LLM Wikiパターンの説明
CLAUDE.md     # このファイル（スキーマ・規約）
```

## Wiki規約

### ページ形式
- すべてのWikiページはMarkdown形式
- 各ページの先頭にYAMLフロントマターを含める：
  ```yaml
  ---
  title: ページタイトル
  type: entity | concept | source | overview | comparison | synthesis
  tags: [タグ1, タグ2]
  sources: [参照元URL or ファイル名]
  created: YYYY-MM-DD
  updated: YYYY-MM-DD
  ---
  ```
- ページ間リンクは `[[ページ名]]` 形式（Obsidian互換）
- 画像は `raw/assets/` に配置

### ページタイプ
- **entity**: 人物、組織、プロジェクトなど固有名詞のページ
- **concept**: 技術、概念、テーマのページ
- **source**: ソースドキュメントの要約ページ
- **overview**: トピックの俯瞰ページ
- **comparison**: 比較・分析ページ
- **synthesis**: 複数ソースを統合した考察ページ

## ワークフロー

### インジェスト
1. `raw/` にソースを配置
2. ソースを読み、主要な情報を抽出
3. `wiki/sources/` にソース要約ページを作成
4. 関連するエンティティ・コンセプトページを作成または更新
5. `wiki/index.md` を更新
6. `wiki/log.md` にエントリを追加

### クエリ
1. `wiki/index.md` を読んで関連ページを特定
2. 該当ページを読んで回答を合成
3. 有用な回答は新しいWikiページとして保存可能

### リント
- 矛盾の検出
- 古い情報の特定
- 孤立ページの発見
- 欠落しているクロスリファレンスの追加
- 新しい調査すべき質問の提案
