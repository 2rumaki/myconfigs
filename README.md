# myconfigs
dotfileなどの各種設定ファイルを管理

## ターミナル

### shell

`zsh`をインストール。

```bash
sudo apt install zsh
```

`zsh`をデフォルトシェルに設定。

```bash
chsh -s $(which zsh)
```

ターミナルの再起動 (ログインシェルから zsh を起動させる。ターミナルを開き直しても同じこと。)

```bash
exec $SHELL -l
```
