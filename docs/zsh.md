# zsh

## インストール

```bash
sudo apt install zsh
```

## デフォルトシェルに設定

```bash
chsh -s $(which zsh)
```

ターミナルの再起動 (ログインシェルから zsh を起動させる。ターミナルを開き直しても同じこと。)

```bash
exec $SHELL -l
```
