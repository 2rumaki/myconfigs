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

#### [HackGen](https://github.com/yuru7/HackGen/)

プログラミング向けのフォント。Starshipでアイコンを表示するために Nerd Font 系のフォントが必要で、HackGenにはそれが含まれているため採用。

Windows の場合、まずは Windows 側にインストールしてから、Windowsターミナルにフォント設定する必要がある。

1. [HackGen](https://github.com/yuru7/HackGen/) の Releases ページからzipファイルをダウンロード
2. ダウンロードしたzipファイルを解凍
3. `*.ttf` ファイルが展開されるので、すべて右クリックor左ダブルクリックで開いて「インストール」を選択
4. Windowsターミナルで、Settings → Profiles → Ubuntu → Appearance → Font face で HackGen Console NF を選択

### [neovim](https://neovim.io/)

#### [LazyVim](https://www.lazyvim.org/)

#### [Catppuccin](https://github.com/catppuccin/nvim)

neovim のカラースキームを提供するプラグイン

### [Lazygit](https://github.com/jesseduffield/lazygit)

### [delta](https://github.com/dandavison/delta)

`git diff` の可読性を高める
