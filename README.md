# doom.d
Doom Emacs configuration

## Installation

```bash
$ snap install emacs --classic
$ sudo apt install fd-find shellcheck pandoc
$ git clone git@github.com:alberto-miranda/doom.d.git ~/.config/doom
$ cd ~/.emacs.d
$ curl -LO https://github.com/BurntSushi/ripgrep/releases/download/14.1.0/ripgrep_14.1.0-1_amd64.deb
$ sudo dpkg -i ripgrep_14.1.0-1_amd64.deb && rm ripgrep_14.1.0-1_amd64.deb
$ git clone --depth 1 https://github.com/doomemacs/doomemacs ~/.config/emacs
$ export PATH=$PATH:$HOME/.config/emacs/bin
$ doom install
```
