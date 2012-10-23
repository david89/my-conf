This is a better way to keep my configuration files synchronized among all the computers I use.

1. Install:

```bash
cd ~
git clone git@github.com:david89/my-conf.git
ln -s ~/my-conf/vim ~/.vim           
ln -s ~/my-conf/vim/vimrc ~/.vimrc
ln -s ~/my-conf/bash/bashrc ~/.bashrc
ln -s ~/my-conf/bash/aliases ~/.bash_aliases
```

