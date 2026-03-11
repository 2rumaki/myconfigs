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

#### [Starship](https://starship.rs/)

インストール

```zsh
curl -sS https://starship.rs/install.sh | sh
```

プリセットがあるので好みのものを選択する。

[Bracketed Segments Preset](https://starship.rs/presets/bracketed-segments) の場合

```zsh
starship preset bracketed-segments -o ~/.config/starship.toml
```
