# nvim-config
This is my personal nvim config, initial baseline is from 


## Config neovim as you default vim editor
###  GIT default editor 
```shell 
git config --global core.editor nvim
```

### Neovim alias to vim 
```shell
echo "alias vim=\"nvim\"" | tee -a ~/.zshrc
```

### For my mac enable and disable accents on hold 
```shell
defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool true
```


### my git alias 
#### Git status
```shell
git config --global alias.st 'status'
```

#### Git commit
```shell
git config --global alias.cm 'commit -m'
```

#### Git 
```shell
git config --global alias.cm 'commit -m'
```


