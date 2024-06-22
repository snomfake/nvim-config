<h1 align="center">:star2: Nvim Dotfiles :star2:</h1>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/snomfake/bspwm-dotfiles?style=for-the-badge">
  </br>
</p>

<br>

<p align="center">This is my minimalistic Neovim configuration for Python development</p>

## :camera: Gallery

![gallery](/screenshots/1.png)
![gallery](/screenshots/2.png)
![gallery](/screenshots/3.png)


## :keyboard: Keymaps

| Keys | Function |
| :--: | :------: |
| `db` | Backward Remove |
| `ctrl` `a` | Select All |
| `esc` | Off Hilight |
| `space` `x` | Close Buffer |
| `tab` | Next Buffer |
| `ctrl` `h`/`l` | Change Window |
| `ctrl` `p` | Telescope |
| `alt` `1` | NvimTree |


## :bookmark_tabs: Prerequisites
- neovim v0.10.0+
- git
- python and pip


## :floppy_disk: Installation

```bash
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.cache/nvim
mkdir -p .config/nvim
git clone https://github.com/snomfake/nvim-config.git ~/.config/nvim
nvim -c "MasonInstall jedi-language-server ruff-lsp black"
nvim
```
