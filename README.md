# myconfigs

PCを買い替えた際などに開発環境の復旧を容易かつ確実に実行できるようにすることを目的としたリポジトリ。dotfile などの各種設定ファイルとそのセットアップ手順を管理する。

## 前提条件

以下のツールを事前にインストールしておくこと。

- [zsh](https://www.zsh.org/)
  - WSL2（Ubuntu 24.04）の場合: `sudo apt install zsh`
  - ログインシェルを zsh に変更: `chsh -s /bin/zsh`
- [mise](https://mise.jdx.dev/)

## 使い方

- 導入したいツールやサービスがあれば **Issue** として登録する
- Issue に対応する **PR** で、ツールの導入手順や設定をリポジトリに取り込む

各ツールの詳細は `docs/` ディレクトリを参照。
