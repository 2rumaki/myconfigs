# Copilot 指示

## 言語

すべての出力（PR、Issue、コミットメッセージ）は**日本語**で記述すること。

## リポジトリ概要

開発環境の復旧を容易にするためのリポジトリ。dotfile などの設定ファイルとセットアップ手順を管理している。

## ワークフロー

- 導入したいツールやサービスを Issue として登録する
- Issue に対応する PR で、ツールの導入手順や設定をリポジトリに取り込む

## 構成

- `README.md` - ターミナル環境のセットアップガイド
- `docs/` - 各ツールの詳細ドキュメント
- `.claude/` - Claude Code のスキル・設定

## コミットメッセージ規約

Conventional Commits 形式に従う。詳細は `.github/git-commit-instructions.md` を参照。

## 後方互換性は不要

deprecated マーク、互換shim、旧名称の再エクスポートは禁止。
