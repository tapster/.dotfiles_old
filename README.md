first, install [janus](https://github.com/carlhuda/janus)

then install tmux:

    brew install tmux

then:

    cd ~
    git clone git@github.com:tapster/.dotfiles.git
    ln -s .dotfiles/.tmux.conf .tmux.conf
    ln -s .dotfiles/.vimrc.after .vimrc.after
    ln -s .dotfiles/.zshrc .zshrc
