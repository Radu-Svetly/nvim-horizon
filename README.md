# TODO

Rewrite in lua. Keep vimscript as legacy

# Horizon

Horizon is a beautifully warm dark colorscheme for NeoVim inspired by [Visual Studio Code Horizon Theme](https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode)

## Installation

- Use [Packer](https://github.com/wbthomason/packer.nvim)

```
use('Radu-Svetly/nvim-horizon')
```

- Other Vim Plugin Management Tools should be the same.

## Usage

init.lua:

```vim
vim.opt.termguicolors = true

" No native lua implementation as of yet
vim.cmd(colorscheme horizon)  
```

init.vim:

```vim
set termguicolors

colorscheme horizon
```

## Screenshots



## Compatibility

I only tested this theme with Neovim, but it might work with Vim as well.
