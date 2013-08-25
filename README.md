dotfiles how-to
========

```
git clone http://github.com/carlthewebmaster/dotfiles.git ~/.vim
cd ~/.vim
git submodule update --init
ln -s ~/.vim/vimrc ~/.vimrc
cat ~/.vim/local-bashrc >> ~/.bashrc

