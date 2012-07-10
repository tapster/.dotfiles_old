first, install [janus](https://github.com/carlhuda/janus)

and add vim-powerline

  cd ~/.janus
  git clone git://github.com/Lokaltog/vim-powerline.git


then install tmux:

    brew install tmux

then:

    cd ~
    git clone git@github.com:tapster/.dotfiles.git
    ln -s .dotfiles/.tmux.conf .tmux.conf
    ln -s .dotfiles/.vimrc.after .vimrc.after
    ln -s .dotfiles/.vimrc.before .vimrc.before
    ln -s .dotfiles/.zshrc .zshrc
    ln -s .dotfiles/.gitconfig .gitconfig
