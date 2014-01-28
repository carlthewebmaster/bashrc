# dotfiles how-to



```bash
git clone http://github.com/carlthewebmaster/vimfiles.git 
cd ~/vimfiles
git submodule update --init
ln -s ~/vimfiles/vimrc ~/.vimrc
ln -s ~/vimfiles ~/.vim

# If desired:
cat ~/vimfiles/local-bashrc >> ~/.bashrc
```

> Note: on a Windows machine with git for windows (bash) use:

```
ln -s ~/vimfiles/vimrc ~/_vimrc
```
