
# Steps

## vimrc
 add `~/.vimrc`
##  nvim

- `brew install neovim`
- add `~/.config/nvim/init.vim` following [FAQ](https://github.com/neovim/neovim/wiki/FAQ)

## plugins
```
cd ~/.vim/pack/plugins/start 

git clone --depth=20 https://github.com/fatih/vim-go.git 
git clone --depth=20 https://github.com/fatih/molokai.git 
git clone --depth=20 https://github.com/AndrewRadev/splitjoin.vim.git
git clone --depth=20 https://github.com/ctrlpvim/ctrlp.vim 
git clone --depth=20 https://github.com/mdempsky/gocode 
git clone --depth=20 https://github.com/sebdah/vim-delve 
git clone --depth=20 https://github.com/scrooloose/nerdtree.git 
git clone --depth=20 https://github.com/MarcWeber/vim-addon-mw-utils.git
git clone --depth=20 https://github.com/garbas/vim-snipmate.git
```

using `:GoInstallBinaries` to install golang plugins 

## alias

add following into .zshrc:
```
alias vi="nvim"
alias vim="nvim"
```

## [optional] oh-my-zsh theme

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## [optional] dracula theme

```
mkdir -p ~/vim/theme
git clone --depth=20 https://github.com/dracula/iterm.git ~/.vim/theme/iterm

# iTerm2 > Preferences > Profiles > Colors Tab
# Open the Color Presets... drop-down in the bottom right corner
# Select Import... from the list
# Select the Dracula.itermcolors file
# Select the Dracula from Color Presets..
```