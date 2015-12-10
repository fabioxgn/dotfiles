### Windows

- Install Vundle: https://github.com/VundleVim/Vundle.vim/wiki/Vundle-for-Windows
  - Tutorial says to clone Vundle in %USERPROFILE% then use `$VIM/vimfiles/bundle/Vundle.vim/` this did not work, using `$HOME` instead of `$VIM` works.

### vim-go

https://github.com/fatih/vim-go

Needs to add `GOPATH` to `~/.profile` for gvim to find it.

### fonts

#### Poweline

Poweline fonts required by vim-airline: https://github.com/powerline/fonts

To Install:

- Clone the repo (added as submodule)
- Run the `install.sh` script
- follow the docs at: https://powerline.readthedocs.org/en/master/installation/linux.html#fonts-installation
  - Remember to use `xset q` to list valid fonts path, `~/.fonts` doesn't work
  - On eOS (Ubuntu 14.4) correct path is: `/usr/local/share/fonts`
  - After copying the font run `fc-cache /usr/local/share/fonts`
  - More info: http://stackoverflow.com/q/29866035/727
