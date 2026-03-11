# コミットメッセージ規約

## 形式

Conventional Commits 形式に従う。

```
<type>: <subject>
```

## type

- `docs`: ドキュメント変更（README、セットアップ手順の追加・修正）
- `feat`: 新しいツールや設定ファイルの追加
- `fix`: 手順の誤りや設定ミスの修正
- `chore`: CI・リポジトリ設定の変更

## ルール

- **日本語**で記述
- subject は **50文字以内**
- 末尾にピリオドをつけない
- 命令形で書く（「追加する」ではなく「追加」）

## 例

```
docs: シェルのコマンド実行履歴の曖昧検索 Atuin を追加
feat: Lazygit の設定ファイルを追加
fix: Starship のインストールコマンドの誤りを修正
chore: propose-tool スキルを追加
```
