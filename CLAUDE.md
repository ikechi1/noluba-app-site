# CLAUDE.md

このファイルはClaude Codeがこのリポジトリを操作する際のガイドです。

## プロジェクト概要

Noluba AppsのGitHub Pagesサイト。アプリのランディングページやプライバシーポリシーをホストしている。

## 構造

```
/
├── index.html                      # メインページ（アプリ一覧）
└── ssh-samurai/
    └── privacy-policy.html         # SSH SAMURAIのプライバシーポリシー
```

## アプリ一覧

- **SSH SAMURAI**: iOS向けSSHクライアントアプリ

## 技術スタック

- 静的HTML/CSS
- GitHub Pagesでホスティング
- ビルドツールなし（そのまま配信）

## 開発ガイドライン

- HTMLファイルは日本語（lang="ja"）で記述
- CSSはインラインスタイルを使用
- 新しいアプリを追加する場合:
  1. `index.html`のapp-listにアプリ項目を追加
  2. 必要に応じて`{app-name}/privacy-policy.html`を作成
