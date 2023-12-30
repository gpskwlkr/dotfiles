<h1 align="center">...Dotfiles</h1>

<div align="center">
    <img alt="i3" src="https://img.shields.io/badge/i3-gray?style=flat-square&logo=i3" width="50" height="30">
    <img alt="alacritty" src="https://img.shields.io/badge/alacritty-gray?style=flat-square&logo=alacritty" width="100" height="30">
    <img alt="neovim" src="https://img.shields.io/badge/neovim-gray?style=flat-square&logo=neovim" width="100" height="30">
</div>

# What's configured

- [tmux](.tmux.conf)
- [zsh](.zshrc)
- [kitty](kitty)
  - Custom theme with nerd font
- [picom](picom)
  - Transparency
- [rofi](rofi)
  - Custom theme
- [i3](i3)
  - vim movements
  - custom workspaces
  - custom colors/theme
- [i3blocks](i3blocks)
  - CPU usage
  - RAM/SWAP usage
  - Disk usage
  - Local IP address
  - Volume indicator
- [nvim](nvim)
  - [lazy.nvim](https://github.com/folke/lazy.nvim)
  - [bufferline](https://github.com/akinsho/bufferline.nvim)
  - [colorizer](https://github.com/norcalli/nvim-colorizer.lua)
  - [comment](https://github.com/numToStr/Comment.nvim)
  - [dressing](https://github.com/stevearc/dressing.nvim)
  - [formatting](https://github.com/mhartington/formatter.nvim)
  - [gitsigns](https://github.com/lewis6991/gitsigns.nvim)
  - [linting](https://github.com/mfussenegger/nvim-lint)
  - lsp
    - [lspconfig](https://github.com/neovim/nvim-lspconfig)
    - [mason](https://github.com/williamboman/mason.nvim)
    - [none-ls](https://github.com/nvimtools/none-ls.nvim)
  - [lualine](https://github.com/nvim-lualine/lualine.nvim)
  - [autopairs](https://github.com/windwp/nvim-autopairs)
  - [autocompletion](https://github.com/hrsh7th/nvim-cmp)
  - [surround](https://github.com/kylechui/nvim-surround)
  - [nvim-tree](https://github.com/nvim-tree/nvim-tree.lua)
  - [treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
  - [telescope](https://github.com/nvim-telescope/telescope.nvim)

> Some of nvim keymaps require `ripgrep` to be installed.

| Distribution              | Command                    |
| ------------------------- | -------------------------- |
| Debian, Ubuntu, Mint etc. | `sudo apt install ripgrep` |
| Arch, Manjaro etc.        | `sudo pacman -S ripgrep`   |
| Fedora                    | `sudo dnf install ripgrep` |
| RHEL/CentOS               | `sudo yum install ripgrep` |
| Mac OS (brew)             | `brew install ripgrep`     |
| Cargo                     | `cargo install ripgrep`    |
