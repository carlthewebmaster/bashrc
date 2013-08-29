# dotfiles how-to



```bash
git clone http://github.com/carlthewebmaster/dotfiles.git ~/.vim
cd ~/.vim
git submodule update --init
ln -s ~/.vim/vimrc ~/.vimrc
cat ~/.vim/local-bashrc >> ~/.bashrc
```

> Note: on a Windows machine, use the _vimrc
