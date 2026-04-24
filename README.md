# Claude Code基礎勉強会

> 〜なんとなく使うから、仕事を任せられる状態へ〜

業務スタッフ（非エンジニア）のための、Claude Code 基礎勉強会の教材一式です。

## 公開サイト（おすすめの読み方）

教材は GitHub Pages で公開されており、検索・サイドバー目次・スマホ対応つきで読めます。

**https://masaki-sigoto.github.io/claude-code-foundation-training/**

### PDF版（印刷・配布用）

[配布用PDFを直接開く](https://masaki-sigoto.github.io/claude-code-foundation-training/assets/claude-code-foundation-training.pdf)（または公開サイトのトップページ内でもプレビュー可能）。

## このリポジトリの構成

```
.
├── README.md              # 本ファイル
├── CLAUDE.md              # 教材制作プロジェクト用のClaude向けルール
├── mkdocs.yml             # 公開サイトの設定
├── .github/workflows/     # GitHub Pages 自動デプロイ
└── docs/                  # 教材本体（公開サイトに表示される内容）
    ├── index.md
    ├── 01_curriculum/     # 60分版の講座設計
    ├── 02_slides/         # スライド構成と本文＋講師補足
    ├── 03_scripts/        # 講師台本（60分版）
    ├── 04_handouts/       # 受講者ハンドアウト
    ├── 05_exercises/      # 演習1〜5
    ├── 06_templates/      # CLAUDE.md・memory・依頼テンプレ
    ├── 07_skills/         # skills 説明とサンプル5種
    ├── 08_mcp/            # MCP 説明資料
    ├── 09_faq/            # よくある質問16問
    └── 10_cheatsheets/    # 印刷配布用チートシート
```

## 利用方法

| 立場 | おすすめの入り口 |
|---|---|
| 講師 | `docs/01_curriculum/` → `docs/03_scripts/` → `docs/02_slides/` |
| 受講者 | `docs/04_handouts/` → `docs/05_exercises/` → `docs/09_faq/` |
| 自習者 | 公開サイトの `はじめに` → `カリキュラム` の順で読む |

## 教材を編集したい場合

1. 該当の `docs/**/*.md` を編集
2. main ブランチに push
3. GitHub Actions が自動でサイトを再ビルドします（数分）

## 注意

- 本教材は 2026 年 4 月時点の Claude Code を前提にしています
- 仕様は変わる可能性があります。最新情報は [Claude Code 公式ドキュメント](https://docs.claude.com/claude-code) で確認してください

## ライセンス

社内勉強会用途で自由に複製・改変可能です。
