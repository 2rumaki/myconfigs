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

## zsh-abbr

- 参考: https://zsh-abbr.olets.dev/

### インストール

```bash
git clone --recurse-submodules https://github.com/olets/zsh-abbr ~/.local/share/zsh-abbr
```
