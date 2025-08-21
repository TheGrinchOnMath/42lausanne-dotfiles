# 42lausanne-dotfiles
dotfiles for 42 Lausanne Piscine
## Installation:
clone this repository wherever
```bash
git clone git@github.com:TheGrinchOnMath/42lausanne-dotfiles.git && cd 42lausanne-dotfiles
```
copy the `nvim` folder to `$HOME/.config/nvim`

```bash
cp 42lausanne-dotfiles/nvim $HOME/.config/nvim
```

## customizing the Stdheader, plugin keybinds
you can look in the `lua/plugins` subfolder to find all the used plugins for the neovim dotfiles.
of particular note are `42-header.lua` and `norminette-lint.lua`.
42-header can be called using `:Stdheader` in neovim,
norminette-lint` can be activated using `<Space>Fn` by default.
