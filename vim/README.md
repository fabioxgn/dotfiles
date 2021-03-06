### Shortcuts

- Ctrl + t: Toogle NERDTree
- Ctrl + h: Previous buffer
- Ctrl + l: Next buffer
- Ctrl + q: Close current buffer
- Ctrl + s: Save current buffer
- F5: Open current file on browser

### Markdown preview

For markdown preview use <F5> plus this extension on chrome: [Markdown preview plus](https://chrome.google.com/webstore/detail/markdown-preview-plus/febilkbfcbhebfnokafefeacimjdckgl)
Obs: É necessário ir nas extensões do Chrome e permitir que a extensão acesse URLs de arquivos.

### Linux

- Clone the repository, ex in `~/dev/dotfiles`
- Init the submodules: `git submodule update --init`
- Create the symbolic links as below:
```
ln -s ~/dev/dotfiles/vim ~/.vim
ln -s ~/dev/dotfiles/vim/vimrc ~/.vim/.vimrc
```
- Start vim and execute `:PluginInstall`

### Windows

- Install Vundle: https://github.com/VundleVim/Vundle.vim/wiki/Vundle-for-Windows
  - Tutorial says to clone Vundle in %USERPROFILE% then use `$VIM/vimfiles/bundle/Vundle.vim/` this did not work, using `$HOME` instead of `$VIM` works.

### vim-go

https://github.com/fatih/vim-go

Needs to add `GOPATH` to `~/.profile` for gvim to find it.

### Monaco font

- Download from: https://gist.github.com/epegzz/1634235
- Download to `~/.fonts` dir and run `fc-cache -vf`
