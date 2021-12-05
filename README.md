# Vim-zsh-config
#### vimsetting, config for vim, need to be renamed (abandoned)

#### init.vim (neovim config, path: ~/.config/nvim/init.vim)
use vim-plug plugs manager
```(cammand for neovim)
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
```
:PlugInstall 
```
coc-nvim extensions lists:
```
:CocInstall
coc-html
coc-git
coc-css
coc-vimtex
coc-tsserver
coc-sh
coc-pyright
coc-json
coc-go
```

#### zshrc (oh-my-zsh config, path: ~/.zshrc)
use antigen plugs manager
```
curl -L git.io/antigen > antigen.zsh
```
The path to antigen.zsh wrote in zshrc must match with the true path.
