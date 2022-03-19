# .dotfiles

A compilation of the various dot configuration files I find useful.

## .vimrc

Vim runtime config file:

To set up vim with this file begin by

1. Delete your existing ~/.vim/ folder and ~/.vimrc file:

```
rm -rf ~/.vim && rm -f ~/.vimrc
```  

2. Download the `.vimrc` file into your home directory:

```
wget https://raw.githubusercontent.com/carlosvq1337/dotfiles/main/.vimrc -P ~/
```
3. Install *Plug*, a Vim plugin manager:

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
4. Open the freshly downloaded `.vimrc` file in Vim (You might encounter an error related to the chosen colorscheme, press Enter when prompted):
```
vim ~/.vimrc
```
5. Install the listed plugins via *Plug*, with the vim command:

> :PlugInstall

