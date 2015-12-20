Configs
=======

Used to save my personnal configs and profiles like my vimrc or my awesome wm rc.lua

Vim
---
Contains
  - .vimrc
  - colors
  I used tango2 color scheme, that is in the folder vim colors.
  - autoload
  - plugins
  I use vundle as a plugin manager.
  `https://github.com/gmarik/vundle
  git clone`


Installation

      ```Clone the repo configs
      ```Clone the repo configs
      cd ~
      git clone https://github.com/luohoufu/configs.git
      " Make a link to vim parameters
      ln -s ~/configs/vim ~/.vim
      ln -s ~/.vim/.vimrc .vimrc
      mkdir ~/.vim/bundle
      " Clone vundle
      git clone https://github.com/gmarik/vundle.git $CLONEDIR/configs/vim/bundle/vundle
      ```

      # Vimrc is already configured for vundle
      Launch `vim`, run `:BundleInstall`

Awesome
-------

1. Contains
  - rc.lua
  - themes/rmoutard

2. Installation

`aptitude install awesome awesome-extra`
`mkdir ~/.config/awesome`
      ```
      ln -s ~/.config/awesome $CLONEDIR/configs/awesome
      ```
  - See the doc for more informations.
  http://doc.ubuntu-fr.org/awesome
