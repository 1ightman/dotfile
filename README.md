## Install Vim Bundle and Plugins
```
mkdir -p ~/.vim/bundle
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
然后 进入vim
```
:PluginInstall
```
YCM 需要编译，安装以下依赖项（Arch Linux）：
```
sudo pacman -S cmake python nodejs npm go mono rust  
cd ~/.vim/bundle/YouCompleteMe
python3 install.py --all
```
