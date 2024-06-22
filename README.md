# :star2: Nvim Dotfiles :star2:

<p align="center">
  <img src="https://img.shields.io/github/repo-size/snomfake/bspwm-dotfiles?style=for-the-badge">
  </br>
</p>

This is just my little config for nvim for Python development

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
rm -rf ~/.config/nvim ~/.local/share/nvim ~/.local/state/nvim ~/.cache/nvim
git clone https://github.com/snomfake/nvim-config.git ~/.config/nvim
nvim -c "MasonInstall jedi-language-server ruff-lsp black"
nvim
```
